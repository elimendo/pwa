# Text Editor Web Application
This is a text editor web application built with a client-server architecture, utilizing modern JavaScript and IndexedDB for local storage. It also incorporates webpack for bundling JavaScript files, workbox for service worker management, and deployment scripts tailored for the Render platform. Below are detailed instructions on setting up and using this application.

# Folder Structure
The application follows a client-server folder structure, with separate directories for frontend and backend components.
text-editor/
├── client/             # Frontend files
├── server/             # Backend files
├── webpack.config.js   # Webpack configuration file
├── package.json        # npm package configuration
└── README.md           # Readme file
# Installation and Usage
## Starting the Application:

Navigate to the root directory of the project.
Run npm run start to start the backend server and serve the client.

## Bundling JavaScript Files:

Ensure that webpack is configured properly (webpack.config.js) to bundle JavaScript files.
Run webpack plugins to generate HTML, service worker, and manifest files.

# Using Next-Gen JavaScript:

Develop the application using modern JavaScript features.
Verify that the text editor functions correctly without errors.
## IndexedDB Implementation:

Upon opening the text editor, IndexedDB should immediately create a database storage.
Enter content into the text editor, and it should be saved automatically to IndexedDB when clicking off the DOM window.
Upon reopening the text editor, the content should be retrieved from IndexedDB.

## Install Button:

Implement an "Install" button to allow users to download the web application as an icon on their desktop.

## Service Worker and Workbox:

Ensure that a service worker is registered upon loading the web application.
Utilize workbox for service worker management.
Pre-cache static assets upon loading, including subsequent pages and static assets.
# Build Scripts:
Ensure that proper build scripts are set up for webpack applications.
Prepare deployment scripts tailored for the Render platform.

# Deployment 
![Capture](https://github.com/elimendo/pwa/assets/148833152/a48b586e-3470-4db4-9d4a-cf6822a02111)

## Render
[https://github.com/elimendo/pwa](https://pwa-lzjx.onrender.com/)https://pwa-lzjx.onrender.com/



