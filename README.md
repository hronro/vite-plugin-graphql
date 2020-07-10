# vite-plugin-graphql

Similar to [graphql-tag/loader](https://github.com/apollographql/graphql-tag#webpack-loading-and-preprocessing), but for [vite](https://github.com/vitejs/vite).

## Installation

```sh
npm i vite-plugin-graphql
```

```sh
yarn add vite-plugin-graphql
```

```sh
pnpm i vite-plugin-graphql
```

## Usage

```javascript
const graphqlPlugin = require('vite-plugin-graphql');

const config = {
  plugins: [graphqlPlugin],
};
```

Now all the files ends with `.gql` or `.graphql` will be handled by `vite-plugin-graphql`.
