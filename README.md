# Asimov: Widget Framework for ePubs

This open source framework is a collection of interactive widgets based on the Open Web Platform. The goal is to form a common, standards-based foundation for ePubs.

## Contributing to Asimov

Looking to contribute something to Asimov? **Here's how you can help.**


### Reporting issues

We only accept issues that are bug reports or feature requests. Bugs must be isolated and reproducible problems that we can fix within the Asimov. Please read the following guidelines before opening any issue.

1. **Search for existing issues.** We get a lot of duplicate issues, and you'd help us out a lot by first checking if someone else has reported the same issue. Moreover, the issue may have already been resolved with a fix available.
2. **Create an isolated and reproducible test case.** Be sure the problem exists in Asimov's code with a [reduced test case](http://css-tricks.com/reduced-test-cases/) that should be included in each bug report.
3. **Include a live example.** Make use of jsFiddle or jsBin to share your isolated test cases.
4. **Share as much information as possible.** Include operating system and version, browser and version, version of Asimov, customized or vanilla build, etc. where appropriate. Also include steps to reproduce the bug.



### Pull requests

- CSS changes must be done in `.less` files first, never just the compiled `.css` files
- If modifying the `.less` files, always recompile and commit the compiled files `asimov.css` and `asimov.min.css`
- Try not to pollute your pull request with unintended changes--keep them simple and small
- Try to share which browsers your code has been tested in before submitting a pull request
- Pull requests should always be against the `master` branch, never against `gh-pages`.



### Coding standards

#### HTML

- Two spaces for indentation, never tabs
- Double quotes only, never single quotes
- Always use proper indentation
- Use tags and elements appropriate for an HTML5 doctype (e.g., self-closing tags)
- Use CDNs and HTTPS for third-party JS when possible. We don't use protocol-relative URLs in this case because they break when viewing the page locally via `file://`.

#### CSS

- Adhere to the [RECESS CSS property order](http://markdotto.com/2011/11/29/css-property-order/)
- Multiple-line approach (one property and value per line)
- Always a space after a property's colon (e.g., `display: block;` and not `display:block;`)
- End all lines with a semi-colon
- For multiple, comma-separated selectors, place each selector on its own line
- Attribute selectors, like `input[type="text"]` should always wrap the attribute's value in double quotes, for consistency and safety (see this [blog post on unquoted attribute values](http://mathiasbynens.be/notes/unquoted-attribute-values) that can lead to XSS attacks).

#### JS

- No semicolons
- Comma first
- 2 spaces (no tabs)
- strict mode
- "Attractive"



### License

By contributing your code, you agree to license your contribution under the [MIT](http://opensource.org/licenses/MIT) license.
