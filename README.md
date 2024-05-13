# Nestjs with Prisma REST API create Tasks

<p align="justify">
Nestjs framework backend Prisma ORM RESTAPI sqlite where you create title and description in sqlite.
</p>


GET
<p align="center">
  <img src="README-images/getnestjs.PNG" alt="Step1">
</p>

POST
<p align="center">
  <img src="README-images/postnestjs.PNG" alt="Step1">
</p>

PUT
<p align="center">
  <img src="README-images/pustnestjs.PNG" alt="Step1">
</p>

DELETE
<p align="center">
  <img src="README-images/deletenestjs.PNG" alt="Step1">
</p>



## Installation

```bash
$ npm install
```

## Running the app

```bash
# development
 #npm run start

# watch mode
 npm run start:dev

# production mode
 npm run start:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

<p align="justify">
if you get a lot of red underline because of prettier syntax and the code is good to use in  .eslintrc.js :
</p>


```bash
module.exports = {
  parser: '@typescript-eslint/parser',
  parserOptions: {
    project: 'tsconfig.json',
    tsconfigRootDir: __dirname,
    sourceType: 'module',
  },
  plugins: ['@typescript-eslint/eslint-plugin'],
  extends: [
    'plugin:@typescript-eslint/recommended',
    'plugin:prettier/recommended',
  ],
  root: true,
  env: {
    node: true,
    jest: true,
  },
  ignorePatterns: ['.eslintrc.js'],
  rules: {
    '@typescript-eslint/interface-name-prefix': 'off',
    '@typescript-eslint/explicit-function-return-type': 'off',
    '@typescript-eslint/explicit-module-boundary-types': 'off',
    '@typescript-eslint/no-explicit-any': 'off',
    'prettier/prettier': ['error', { 'endOfLine': 'auto' }],
  },
};

```


inspitation [Fatz nestjs & Prisma ](https://www.youtube.com/watch?v=vUcNydH1tz0)
