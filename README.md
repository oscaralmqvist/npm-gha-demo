# Demo: Automatically publishing tested Node.js packages on npm with Github Actions
A repository for the demo of publishing tested Node.js packages to NPM using Github Actions.

## Package structure
- [calculator.js](./calculator.js) contains the functions exported from this package,
- [calculator.test.js](./calculator.test.js) contains the tests for the package,
- [.github/workflows/publish.yml](./.github/workflows/publish.yml) contains the action for publishing the repository to NPM using the repository secret containing the `NODE_AUTH_TOKEN`. This is executed when pushing to the main branch.
- [.github/workflows/testing.yml](.github/workflows/testing.yml) contains the action for running the tests when submitting a pull request.

## Demo showcase
[YouTube link](https://www.youtube.com/watch?v=Kz7HkpfNCF0)
