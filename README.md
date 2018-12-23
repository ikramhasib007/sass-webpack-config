# SASS Webpack Configuration
Webpack Configuration for SASS, Images and also JS Files

## Require 
  -	Node.js install on your PC
  -	Go to [Node.js](https://nodejs.org/en/download/) download and install
	
## Require Dev Dependencies
  -	`style-loader` For Any embadded style need to add
  -	`css-loader`    Webpack needs specific loaders to support CSS
  -	`sass-loader`    Webpack needs specific loaders to support Sass
  -	`file-loader`   Provides support for files (images) in our CSS rules
  -	`cssnano`    CSS minifier
  -	`node-sass`   Bindings for Node to LibSass; provides support for Sass
  -	`postcss-loader`   PostCSS loader for Webpack to process autoprefixing and minification
  -	`postcss-preset-env`  PostCSS Environment Preset
  -	`cross-env`   Provides support to Windows users for environment variables. We will use NODE_ENVenvironment variable
  -	`mini-css-extract-plugin`   Extracts the CSS to a separate file
  -	`webpack`   Module bundler
  -	`webpack-cli`   Module bundler

## Installation scripts
	npm install style-loader css-loader sass-loader file-loader cssnano node-sass postcss-loader postcss-preset-env cross-env mini-css-extract-plugin webpack webpack-cli --save-dev

## Useful links
  >	[mini-css-extract-plugin](https://webpack.js.org/plugins/mini-css-extract-plugin/)

## Start development
  - `npm run dev` For developerment
  - entry point `scss/main.scss`
  - `npm run build` For production
