# live-reload-vanilla-sample-website-template

Sample single page website build without using any front-end framework but making use of Webpack to support writing modern JavaScript (ES6+), including ES Modules and Sass.

H + Sport is a fictional website and company offering vitamin supplements in sports and outdoor activities.

## Features

- Simple weather update widget using vanilla js.
- Live reload in development
- Webpack
- Sass compilation (and minification/autoprefixing in production)
- ES6+ transpilation (and minification/uglyfication in production)
- ES Modules

## Usage

- Install dependencies

```
yarn
```

- Run development server

```
yarn dev
```

Will open your default browser to http://localhost:8080/public

Webpack will watch for changes in the `./src` directory and output the bundled assets to `./public/assets`. In parellel, the development server will watch for changes in the `./public` directory and live reload the browser.

- Build production bundles

```
yarn build
```

Will compile, minify and autoprefix Sass to CSS. Will Minify and uglify JavaScript and output the bundled assets to `./public/assets`.

After building for production you can take the `./public` directory and deploy it.
