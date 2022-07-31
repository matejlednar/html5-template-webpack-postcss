# HTML5 Template + webpack + PostCSS - full version

HTML5 template with CSS, JS, images, and fonts support with CSS and JS optimization (minimizers).

## Prerequisites

- Node.js
- npm

## Installation

```npm install```

### Run template/server

``` npm run start ```

### Build template/HTML website

``` npm run build ```

### Run production version

Run index.html file.
You can use the Live server to run index.html.

Location: dist/index.html

### Configuration

#### webpack 

Edit webpack.config.js file.
Use development value for application development.
Use production value for the build.

``` mode: "production", // production | development```

#### npm 

Edit package.json file.

Change the entry point here.

``` "main": "src/js/script.js",```