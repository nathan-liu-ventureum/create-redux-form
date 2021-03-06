See [kleros.md](https://kleros.gitbooks.io/kleros-md).

## Prerequisites

[Node.js](http://nodejs.org/) >= v4 must be installed.

## Installation

* Running `yarn` in the component's root directory will install everything you need for development.

## Running Tests

* `yarn run start:test` will run the tests on every change.

* `yarn test` will run the tests and produce a coverage report in `coverage/`.

## Demo Development Server

* `yarn start` will run a development server with the component's demo app at [http://localhost:3000](http://localhost:3000) with hot module reloading.

## Building

* `yarn run clean` will delete built resources.

* `yarn run build` will build the component for publishing to npm and also bundle the demo app.
