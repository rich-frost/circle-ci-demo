# CircleCI demo

This is an example project using CircleCI as it's CI runner.

## Setup

Run the following to setup this project locally:

1. Clone and setup the repo:

   ```bash
   git clone git@github.com:rich-frost/circle-ci-demo.git
   cd circle-ci-demo/
   npm install
   ```

2. To run the project:

   ```bash
   npm run start
   ```

3. Go to http://localhost:8080/ in your browser

### Scripts

- `npm run start` - runs the project locally
- `npm run build` - builds the project for production and outputs to `dist/` folder (TODO)
- `npm run dev` - builds the project for development and outputs to `dist/` folder
- `npm run test` - runs unit tests
- `npm run test-dev` - runs unit tests with watch mode
- `npm run test-coverage` - runs unit tests with coverage report
- `npm run lint` - lints the project
- `npm run tsc` - compile the project with Typescript
- `npm run tsc-dev` - compile the project with Typescript and watch for changes
