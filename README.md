# Lexicon UI

Frontend for Lexicon - Built with VueJS 3 and Vite. Hosted on Vercel

## Project Setup - Local

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Run Unit Tests with [Vitest](https://vitest.dev/)

```sh
npm run test:unit
```

### Run End-to-End Tests with [Cypress](https://www.cypress.io/)

```sh
npm run test:e2e:dev
```

This runs the end-to-end tests against the Vite development server.
It is much faster than the production build.

But it's still recommended to test the production build with `test:e2e` before deploying (e.g. in CI environments or, in our case, Vercel):

```sh
npm run build
npm run test:e2e
```

### Lint with [ESLint](https://eslint.org/)

Fix issues with code formatting in the repo with the following command. It will automatically scan through the repo and fix all linting issues.

```sh
npm run lint
```

### Prod deployment

1. Create a PR
2. Get PR approved
3. Once approved, Vercel will automatically pick up the changes and deploy to prod