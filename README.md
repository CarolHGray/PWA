# PWA
Getting to use React!
## 19 Progressive Web Applications (PWA) : Text Editor

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

The application is a web text editor where the user can create notes or code snippets with or without an internet connection and where the user can reliably retrieve them for later use.  The integrated service worker and Cache API's ensure that the application will remain fully functional even without and active internet connection.  This application allows the user to access visited pages even if the application is offline.

The URL of the GitHub repository is https://carolhgray.github.io/PWA/ and the repository location is https://github.com/CarolHGray/PWA


🚀The application has been deployed to Heroku and the URL of the deployed application is:-
 
https://dry-meadow-36769-8282e75c59b0.herokuapp.com/



## Table of Contents

* [Installation](#installation)
* [Usage](#usage)
* [License](#license)

## Installation

* This text editor requires multiple methods and stores data to an IndexedDB database to build up.

* This application will require the installation of Node.js and various npm packages.


*  This application will use the following npm packages:-

         * npm install express (express.js)
         * npm install --save-dev webpack (Webpack)
         * npm install webpack-dev-server --save-dev (webpack-dev-server)
         * npm install --save-dev webpack-pwa-manifest (WebpackPwaManifest)
         * npm install babel (Babel)
         * npm install --save-dev css-loader (CSS-loader)
         * npm install concurrently --save (run multiple commands concurrently.) 
         * npm npm install idb (IndexedDB)

* The required modules are bundled in the package.json file and at CLI or integrated terminal type in **npm run install**, the modules will be installed.       

## Usage

1.
``````    
GIVEN a text editor web application, 
WHEN I open my application in my editor
THEN I should see a client server folder structure``````

    WHEN I run `npm run start` from the root directory
    THEN I find that my application should start up the backend and serve the client
    WHEN I run the text editor application from my terminal
    THEN I find that my JavaScript files have been bundled using webpack
    WHEN I run my webpack plugins
    THEN I find that I have a generated HTML file, service worker, and a manifest file

WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor

*Below is the screenshot of the text editor "Just Another Text Editor (J.A.T.E)"*

![alt text](./src/images/Screenshot 2024-04-13 at 8.41.52PM.png)

THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop

WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets

WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application 
 
## License

This project is licensed under the terms of the MIT license.