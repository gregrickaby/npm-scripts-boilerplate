# npm-scripts-boilerplate

No need for Gulp, Grunt, or Webpack here... this is a collection of packages that build a website using `npm scripts` instead. Thanks to Damon Bauer for his post on [CSS Tricks](https://css-tricks.com/why-npm-scripts/) and his [NPM Build Boilerplate](https://github.com/damonbauer/npm-build-boilerplate) for which this is based.

## Quick Start

**Clone**
```bash
git clone https://github.com/gregrickaby/npm-scripts-boilerplate.git
```

**Install**
```bash
npm i
```

**Set your proxy URL in `package.json` under the `serve` task.**
```bash
browser-sync start --https --proxy 'https://gregrickaby.test' --files \'dist/css/*.css, dist/js/*.js, **/*.html, !node_modules/**/*.html\'
```
(or you could remove the proxy... your choice!)

**Watch**
```bash
npm run watch
```

## Use with WordPress

If you want to use this workflow with a WordPress Theme, checkout my [WP Starter Theme](https://github.com/gregrickaby/wp-starter-theme).

## Need help?
Feel free to [create an issue](https://github.com/gregrickaby/npm-scripts-boilerplate/issues) or [tweet me](https://twitter.com/gregrickaby).
