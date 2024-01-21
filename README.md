<h1 align="center">Payment Application </h1>
<h3  align="center"><img alt="Cypress Real World App Logo" width="150px" src="./src/svgs/rwa-logo-light.svg#gh-dark-mode-only" /></h3>
<p align="center">
<i>By ThuyHo</i>
</p>
<p align="center">
  
  <img alt="Cypress Real World App Logo" src="./src/svgs/rwa-logo.svg#gh-light-mode-only" />
</p>

<p align="center">
A payment application to demonstrate <strong>real-world</strong> usage of <a href="https://cypress.io">Cypress</a> testing methods, patterns, and workflows.
This project explores various aspects of Cypress testing, including API interactions, UI validation, and security checks, within the context of a payment application.
</p>

<p align="center">
  <img style='width: 70%' alt="Cypress Real World App" src="./public/img/rwa-readme-screenshot.png" />
</p>

## Features

### Developments

- 🛠 Built with: [React], [XState], [Express], [lowdb], [Material-UI] and [TypeScript]
- ⚡️ Zero database dependencies
- 🚀 Full-stack [Express][express]/[React][reactjs] application with real-world features and tests
- 👮‍♂️ Local Authentication
🔥 Database Seeding with End-to-end Tests
- 💻 CI/CD + [Cypress Cloud][cypresscloud]

### Tests

- API Testing: [cypress/tests/api](./cypress/tests/api)
- UI Testing: [cypress/tests/ui](./cypress/tests/ui)  
- Component Testing: [src/(next to component)](./src) 
- Unit Testing: [`src/__tests__`](./src/__tests__)
- DB Testing: Local JSON database [data/database.json](./data/database.json) and is managed with [lowdb].

## Getting Started

### Prerequisites

* [Node.js](https://nodejs.org/en/) to be installed on your machine
* [Yarn Classic](https://classic.yarnpkg.com/) is also required.Install the npm module [yarn](https://www.npmjs.com/package/yarn) (Classic - version 1) globally.

```shell
npm install yarn@latest -g
```

### Installation

```shell
yarn
```

### Run the app

```shell
yarn dev
```
- Run on port `3000` (frontend) and `3001` (API backend) by default. 
- URL: http://localhost:3001

### Start Cypress

```shell
yarn cypress:open
```

## Code Coverage Report

The Cypress Real-World App uses the [@cypress/code-coverage](https://github.com/cypress-io/code-coverage) plugin to generate code coverage reports for the app frontend and backend.

To generate a code coverage report:

1. Start the development server with coverage enabled by running `yarn dev:coverage`.
2. Run `yarn cypress:run --env coverage=true` and wait for the test run to complete.
3. Once the test run is complete, you can view the report at `coverage/index.html`.

## 3rd Party Authentication Providers

Support for 3rd party authentication is available in the application to demonstrate the concepts on logging in with a 3rd party provider. 

- [Auth0](#auth0) (index.auth0.tsx)
- [Okta](#okta) (index.okta.tsx)
- [Amazon Cognito](#amazon-cognito) (index.cognito.tsx)
- [Google](#google) (index.google.tsx)

## Author ✨

This project is a personal learning exercise focused on practicing Cypress testing with a payment application.


<table>
  <tr>
    <td align="center"><a href="https://drive.google.com/drive/my-drive"><img src="Avatar.png" width="100px;" alt=""/><br /><sub><b>Thuy Ho</b></sub></a></td>
  </tr>
</table>

I re-built this project to use Cypress and gain experience testing a payment application.

Project explores various aspects of Cypress testing, including API interactions, UI validation, and security checks, within the context of a payment application.

_Reference: https://github.com/cypress-io/cypress-realworld-app_