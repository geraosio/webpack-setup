# Webpack setup example

This is an example of a website built using a simple Webpack configuration.

## Instructions

1. Install npm packages

  ```
  npm install
  ```

2. Either run the Webpack server for development or build the site ready for deployment (targer dist/)

  * To run Webpack server:

    ```
    npm start

    // Shortcut for
    webpack-dev-server --open --mode development
    ```

  * To build the site:

    ```
    npm run-script build

    // Shortcut for
    webpack --progress --mode production
    ```

## NPM Packages

#### Dependencies

| npm package                    | version |
| ------------------------------ | ------- |
| bootstrap                      | 4.1.2   |
| jquery                         | 3.3.1   |
| popper.js                      | 1.14.3  |

#### Dev Dependencies

| npm package                    | version |
| ------------------------------ | ------- |
| autoprefixer                   | 8.6.5   |
| babel-core                     | 6.26.3  |
| babel-loader                   | 7.1.5   |
| babel-preset-env               | 1.7.0   |
| css-loader                     | 1.0.0   |
| file-loader                    | 1.1.11  |
| html-loader                    | 0.5.5   |
| html-webpack-inline-svg-plugin | 1.2.4   |
| html-webpack-plugin            | 3.2.0   |
| imagemin                       | 5.3.1   |
| img-loader                     | 3.0.0   |
| mini-css-extract-plugin        | 0.4.1   |
| node-sass                      | 4.9.2   |
| postcss-loader                 | 2.1.6   |
| sass-loader                    | 7.0.3   |
| style-loader                   | 0.21.0  |
| url-loader                     | 1.0.1   |
| webpack                        | 4.16.0  |
| webpack-cli                    | 3.0.8   |
| webpack-dev-server             | 3.1.4   |
