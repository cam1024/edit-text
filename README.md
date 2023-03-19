# Edit-Text
## Description

The application is a web text editor where the user can create notes or code snippets with or without an internet connection and where the user can reliably retrieve them for later use.  The integrated service worker and Cache API's ensure that the application will remain fully functional even without and active internet connection.  This application allows the user to access visited pages even if the application is offline

The application has been deployed to Heroku and the URL of the deployed application is:

 https://text-editers.herokuapp.com/

## Table of Contents

* [Installation](#installation)
* [Usage](#usage)
* [References](#references)
* [License](#license)

## Installation

* This text editor require a number of methods and store data to an IndexedDB database to be builded up.

* This application will require the installation of Node.js and various npm packages.

*   Node Package Manager (npm) is a software manager and installer which puts the modules in place so that the node project can utilize it, and also, it manages dependency conflicts intelligently and initialized using **npm init**. The package.json will be generated and will contains all the details of the application in which the user have inputted during the npm initialization. 

*  This application will use the following npm packages:-

         * npm install express (express.js)
         * npm install --save-dev webpack (Webpack)
         * npm install webpack-dev-server --save-dev (webpack-dev-server)
         * npm install --save-dev webpack-pwa-manifest (WebpackPwaManifest)
         * npm install babel (Babel)
         * npm install --save-dev css-loader (CSS-loader)
         * npm install concurrently --save (run multiple commands concurrently.) (Concurrently)
         * npm install idb (IndexedDB)

* The required modules are bundled in the package.json file and at CLI or integrated terminal type in **npm run install**, the modules will be installed.       

## License

This project is licensed under the terms of the MIT license.