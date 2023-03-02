# Text-Editor-PWA-

This is a browser-based text editor that is built as a single-page application and meets the criteria of a Progressive Web App (PWA). The application is designed to be resilient, incorporating several data persistence techniques to ensure that data is never lost, even if one or more of the options is not supported by the user's browser.

## Features
A simple and intuitive user interface that allows users to create and edit text documents.
Ability to save documents locally in the browser, allowing users to access their documents at a later time.
Data persistence using IndexedDB, allowing users to save their documents on the browser even after the browser is closed or the device is restarted.
Cloud synchronization using Firebase, which allows users to access their documents from any device with an internet connection.
Offline support, allowing users to create and edit documents even when they are not connected to the internet.
Keyboard shortcuts for common editing tasks such as copy, paste, undo and redo.

## Technologies Used

HTML5
CSS3
JavaScript
IndexedDB
Firebase
Service Workers
Web App Manifest
Getting Started

To use the text editor, simply open the URL in a web browser that supports PWAs. The application will automatically detect whether the browser supports IndexedDB and Firebase, and will use the appropriate persistence method accordingly.

Running the Application Locally
To run the application locally, clone the repository and open the index.html file in a web browser that supports PWAs.

Link to the app: https://mw-jate.herokuapp.com/
