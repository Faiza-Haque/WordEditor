# WordEditor

WordEditor is a Progressive Web Application (PWA) designed to function both online and offline, allowing users to create and edit text documents. This application uses modern web technologies including Webpack, Workbox, IndexedDB, and Babel.

## Deployed Link
[WordEditor](https://wordeditor-7f6j.onrender.com)

## Screenshots
![Screenshots](./screenshots/wordeditor.png)


## Features

- **PWA Capabilities**: Installable on desktop and mobile devices, with offline functionality.
- **IndexedDB Integration**: Stores and retrieves text data using IndexedDB.
- **Service Worker**: Caching and offline functionality implemented using Workbox.
- **Webpack**: Efficient build process with bundling, manifest generation, and more.

## Getting Started

### Prerequisites

Ensure you have the following software installed:

- [Node.js](https://nodejs.org/) (version 12 or higher)
- [npm](https://www.npmjs.com/get-npm) (comes with Node.js)

### Installation

1. Clone the repository:

  ```
  git clone git@github.com:Faiza-Haque/WordEditor.git
   ```
2. Navigate to the project directory:
   ```
   cd wordeditor
   ```
   3. Install the necessary dependencies:
   ```
   npm install
    ```
3. Development
To start the development server, run:
```
npm run start
```
*** This will start the app in development mode and should automatically open it in your default web browser.

Building for Production
To build the project for production, run:
```
npm run build
```
*** This will create an optimized production build in the dist directory.

Testing the Service Worker
To test the service worker and PWA functionality, you'll need to serve the dist directory with a local server. One way to do this is by using serve:

1. Install serve globally:
```
npm install -g serve
```
2. Serve the dist directory:
```
serve -s dist
```
Installing the PWA
You can install WordEditor as a PWA on your desktop or mobile device. Click the install button that appears in your browser's address bar or in the app's UI to install the PWA.

Project Structure
* src: Contains the source code for the application.
* js: JavaScript files.
* images: Images used in the application.
* dist: Contains the production build of the application.
* webpack.config.js: Configuration file for Webpack.

Key Files and Code
* webpack.config.js: Webpack is configured to bundle JavaScript files, handle CSS, and generate a PWA manifest.
* src-sw.js: The service worker script, generated by Workbox, which handles caching and offline functionality.
* idb.js: A utility script for interacting with IndexedDB using the idb library.
* index.js: The main entry point for the application.
* install.js: Handles the PWA installation logic.

Technologies Used
* Webpack: Module bundler.
* Babel: JavaScript compiler.
* Workbox: Service worker and offline caching.
* IndexedDB: Client-side storage solution.
* HTML: Markup language.
* CSS: Stylesheet language.

Contributing
Contributions are welcome! Please feel free to submit a Pull Request or open an issue for any bugs or feature requests.