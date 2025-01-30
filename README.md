# LEARN DOCUSAURUS

This website is built using [Docusaurus](https://docusaurus.io/), a modern static website generator.

### Installation Node Module

using yarn
```
$ yarn
```

using npm
```
$ npm i / npm install
```

### Local Development

```
$ yarn start
```

or you can use npm

```
$ npm run start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.


## How To Install Bootstrap in project docusaurus

Instalasi bootstrap
```
$ npm install bootstrap
```

Import Bootstrap to <strong>custom.css</strong>
```
@import "bootstrap/dist/css/bootstrap.min.css";
```

Don't Forget to update <strong>docusaurus.config.ts</strong> ,  if you use javascript config.js
```
theme: {
  customCss: require.resolve('./src/css/custom.css'),
}
```

