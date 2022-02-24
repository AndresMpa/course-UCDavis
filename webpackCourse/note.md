This project is an example taken from

https://github.com/gndx/js-portfolio.git

## Webpack.config.js

Este archivo sirve para extender las configuraciones de webpack de ese modo se pueden agregar
plugin entre otras cosas

## Babel

npm install -D babel-loader @babel/core @babel/preset-env @babel/plugin-transform-runtime

- babel-loader nos permite usar babel con webpack
- @babel/core es babel en general
- @babel/preset-env trae y te permite usar las ultimas características de JavaScript
- @babel/plugin-transform-runtime te permite trabajar con todo el tema de asincronismo como ser async y await
- Debes crear el archivo de configuración de babel el cual tiene como nombre .babelrc

## HTML Webpack

Ayuda a poder usar HTML en webpack, ya que este no esta por defecto

npm i html-webpack-plugin -D

## CSS Webpack

Este plugin ayuda a que webpack pueda procesar directamente el CSS que se tiene, esto además hace que no se tenga
que cargar el CSS sobre HTML, pues se puede montar directamente sobre el archivo main.js que es el archivo que
genera webpack al final

npm i mini-css-extract-plugin css-loader -D
npm i node-sass sass-loader -D
npm i stylus-loader -D

## Copy webpack

Este plugin ayuda a mover archivos a carpetas para poder tener assent dentro de dist

npm i copy-webpack-plugin -D