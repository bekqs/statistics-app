# Statistics app

JavaScript budgeting app that calculates income and expenses and generates chart using using localStorage.
Application's design is currently only considered only for mobile devices, soon it will be updated to make it desktop friendly. The app has 2 pages only available at the moment:

__Feed__ - Static page.

__Statistics__ - lets you create and manage charts using data from local storage.


## Built With
  * Webpack
  * Babel
  * SASS
  * Chart.js
  * CSS loaders
    * Style loader
    * CSS loader
    * Post CSS loader
    * SASS loader
  * [mini-css-extract-plugin](https://github.com/webpack-contrib/mini-css-extract-plugin) - Replaces extract-text-webpack-plugin, which doesn't work properly with the last Webpack
  * [css-hot-loader](https://github.com/shepherdwind/css-hot-loader) - Enables Hot Module Replacement for mini-css-extract-plugin

## Features
List of current functionalities

  * Chart creation
  * Save/edit/get data from localStorage
  * Calculate and display total sum
  * Show data from each chart segment when segment is clicked
  * Save data separately for each month
  * Display chart according to the selected month from top menu
  
List of functionalities to add

  * Calculate annual savings