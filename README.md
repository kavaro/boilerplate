# Work in progress, use at own risk

# Boilerplate with rollup and jest

Configures a project to create a nodejs library with rollup and jest

## Create a new project using "create-project" (recommended)

Step 1: Make sure the create-project package is installed globally

```bash
yarn global add create-project
```

Step: Create a new project

```bash
create-project PROJECT_NAME kavaro/boilerplate
cd PROJECT_NAME
git init
yarn
# Rename package.json "name" field
```

## Create a new project manually 

```bash
git clone https://github.com/kavaro/boilerplate.git PROJECT_NAME
cd PROJECT_NAME
git remote rm origin
yarn
# Rename package.json "name" field
```

## Usage

```bash
yarn start: watch source files for development, compiles ./src/index.js to ./dist/index.js
yarn build: build for production
yarn test: watch source files for testing
yarn coverage: generate coverage report
yarn publish-patch: publish patch update to npm
yarn publish-minor: publish minor update to npm
yarn publish-major: publish major update to npm
```
