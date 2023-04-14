# Contributing

## Table of Contents
- [Newcomer](#newcomer)
- [Open an Issue](#open-an-issue)
- [Submit a Pull Request](#submit-a-pull-request)
- [Style guide](#style-guide)
- [Testing](#testing)
- [Code of Conduct](#code-of-conduct)
- [License](#license)

## Newcomer
If you are a newcomer contributor, look for the label Good first issue. Issues labeled like that can be resolved without having an in depth knowledge about the codebase you are contributing to.

## Open an Issue
[Open an Issue](https://github.com/brand-ui-framework/brand-ui/issues/new) to report any problems or improvements. When necessary, use [Codepen](http://codepen.io/) to show the problem. Be sure to include some description to explain the problem.

## Submit a Pull Request
To submit a new feature, make sure that changes are done to the source code. Do not forget the tests and attach the link [Codepen](http://codepen.io/) along with the description.

Try to solve a problem for each pull request, this increases the chances of acceptance. When in doubt, open a [new issue](https://github.com/brand-ui-framework/brand-ui/issues/new) so we can answer you. Look existing issues for ideas or to see if a similar issue has already been submitted.

1. Fork the Github repo: `git clone https://github.com/brand-ui-framework/brand-ui.git`
1. Create a new branch: `git checkout -b issuenumber-feature-name`
1. Commit your changes: `git commit -m 'issuenumber-feature-name'`
1. Push to the branch: `git push origin my-feature-name`
1. Submit a pull request!

## Style guide
Brand UI use only CSS, so plase make shure that you have no SCSS files in your code.

- The selector and the bracketts are on the same line with one space between
- Properties and selectors are sorted in alphabetical order
- Always use tab to indentation, no spaces
- Always use single quote, i.e. `content: ''`
- Quote attribute values in selectors, i.e. `input[type='checkbox']`
- Use lowercase and long hex values, i.e. `#ffffff`
- Include a single space after colon and after each comma
- Separate each ruleset by a blank line
- Use camelCase

```css
.primaryButton {
  background-color: var(--primary);
  color: var(--white);
  padding: 16px 32px;
}
```

## Testing
Breaking CSS is easy. Checking every responsive page element is hard. That's why Milligram uses automated visual regression testing for responsive web UI by comparing DOM screenshots at various viewport sizes. To view the comparison run `npm run visual-regression` after making changes to the source code.

## Code of Conduct
Help us keep Milligram open and inclusive. Please read and follow our thoughts on [Code of Conduct](http://confcodeofconduct.com/).

## License
By contributing your code, you agree to license your contribution under the [MIT license](https://github.com/brand-ui-framework/brand-ui/blob/main/.LICENSE).
