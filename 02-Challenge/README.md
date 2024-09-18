# **Text Editor PWA**

## **Description**

The **Text Editor PWA** is a single-page text editor that works both online and offline. It is designed to meet Progressive Web Application (PWA) criteria, utilizing a variety of data persistence methods with redundancy for different browser support. The application stores data using IndexedDB through the `idb` package and allows for saving and retrieving content. This text editor is fully functional even without an internet connection and can be installed as a desktop application.

## **Features**
- **Offline Capability**: The application works without an internet connection and can be installed locally as a PWA.
- **IndexedDB Integration**: Utilizes `idb` to store and retrieve text editor content.
- **Automatic Saving**: Saves the text automatically when the DOM window loses focus.
- **Service Worker**: A service worker caches static assets and ensures the application is accessible offline.
- **Webpack**: JavaScript files are bundled using Webpack, with a generated `manifest.json`, service worker, and HTML file.
- **Next-Gen JavaScript**: The application supports next-gen JavaScript through Babel, allowing the use of async/await.

## **Technologies Used**
- **IndexedDB**: Local database for storing text data.
- **idb**: A lightweight wrapper for the IndexedDB API.
- **Webpack**: Bundles JavaScript files and creates the manifest and service worker files.
- **Workbox**: Caches static assets and enables offline functionality.
- **Babel**: Transpiles next-gen JavaScript to ensure compatibility across browsers.
- **Node.js & Express**: Backend server that serves the application.

## **User Story**

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## **Installation**

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Run the application**:
   ```bash
   npm run start
   ```

This will start both the backend and the frontend in development mode.

## **Deployment**

This application is deployed on Render. Visit the live application [here](#).

You can find the GitHub repository for this project [here](https://github.com/fredonyjr/text-editor-pwa).