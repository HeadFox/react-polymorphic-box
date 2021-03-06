# Contributing

Thank you for taking the time to contribute! Guidelines below are meant to help you along the way. All contributions are welcome, including ideas, tweaks and more.

## Code of Conduct

This project is governed by the [Contributor Covenant Code of Conduct](./CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## Proposing a change

Before making a non-trivial change, please discuss it via [issues].

## Development process

Please keep the scope of each pull request to **one** specific feature or fix.

### Prequisites

- [Node.js](https://nodejs.org/) >=10

### Workflow

0. Assign related [issues] to yourself
1. Clone a fork of the `main` branch and install all the required dependencies with `npm install`
1. Make changes to the codebase
1. Before pushing, fix any errors possibly emitted by the following commands:

   - `npm run format` fixes stylistic issues using [Prettier]
   - `npm run lint` enforces coding rules based on the [Airbnb JavaScript Style Guide]
   - `npm run type-check` checks for errors in TypeScript code

1. Record your changes with `npm run commit`, adhering to the [Conventional Commits] specification
1. Open a new pull request, [referencing corresponding issues] if available

## License

As a collaborator, you agree to license your contributions under the project's [MIT license](./LICENSE).

[issues]: https://github.com/kripod/react-polymorphic-box/issues
[prettier]: https://prettier.io/
[airbnb javascript style guide]: https://github.com/airbnb/javascript
[conventional commits]: https://www.conventionalcommits.org/en/v1.0.0/
[referencing corresponding issues]: https://help.github.com/en/articles/closing-issues-using-keywords
