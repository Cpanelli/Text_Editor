# Text_Editor

## Overview

This project is a Progressive Web Application (PWA) that serves as a text editor with syntax highlighting for JavaScript. It allows users to take notes, write code snippets, and store them locally in their browsers using IndexedDB. The application features service worker integration for offline functionality and follows PWA best practices for a seamless user experience.

## Features

Text Editing: Users can create, edit, and delete text notes directly within the application.
Syntax Highlighting: JavaScript code snippets are displayed with syntax highlighting for improved readability.
Local Storage: Notes are stored locally in the user's browser using IndexedDB, allowing for persistent data storage.
Offline Functionality: The application works offline thanks to service worker integration, enabling users to access their notes even without an internet connection.
Responsive Design: The user interface is designed to be responsive and optimized for various screen sizes, including desktop and mobile devices.

 ##  Screenshots


## Installation and Setup

Clone the repository to your local machine:

Copy code

git clone <[repository-url](https://github.com/Cpanelli/Text_Editor.git)>

cd text-editor
Install dependencies using npm

Copy code
npm install

Build the project:

Copy code
npm run build

Copy code
npm start

## Technologies Used

JavaScript: The primary programming language used for the application logic.
HTML/CSS: Used for structuring the user interface and styling.
Webpack: Bundles JavaScript and other assets for deployment.
Babel: Transpiles modern JavaScript code to ensure compatibility with older browsers.
IndexedDB: Provides a local database for storing text notes.
Service Worker: Enables offline functionality and caching of assets for improved performance.
HTML Webpack Plugin: Simplifies HTML generation for Webpack bundles.
Workbox Webpack Plugin: Integrates service worker functionality into the webpack build process.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Links 

https://pwa-text-editor-4-910873dba0e2.herokuapp.com/

https://github.com/Cpanelli/Text_Editor