# PWA-Text-Editor

This project is a text editor web application designed to allow users to create notes or code snippets with or without an internet connection. It provides offline capabilities through IndexedDB and service worker integration, allowing users to reliably retrieve their content for later use.

## Features
- Offline Functionality: Users can access and edit their notes or code snippets even without an internet connection.
-IndexedDB Integration: Content entered in the text editor is immediately saved to IndexedDB, ensuring data persistence.
-Service Worker: A service worker is registered using Workbox, providing caching of static assets and subsequent pages for improved performance and offline access.
-PWA Installation: Users can install the web application as a progressive web app (PWA) on their devices with a simple click of the Install button.
-Webpack Bundling: JavaScript files are bundled using webpack, allowing for efficient code organization and deployment.

## Link to deployed site
https://pwa-text-editor-4-var1.onrender.com/
