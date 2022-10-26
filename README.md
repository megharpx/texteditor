# Text Editor

## Description
his project is a text editing Progressive Web Application (PWA) modified to store and retrieve data, as well as offline capabilities. This has been achieved by using the IndexedDB API, idb npm wrapper for the IndexedDB API, Webpack as a module bundler, and a service worker using Workbox

## Table of Contents

- [User Story](#user-story)
- [Installation and Usage](#installation-and-usage)
- [Contributers](#contributors)

## User Story 
<pre><code class="md language-md">AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use</code></pre>
<h2 id="acceptance-criteria">Acceptance Criteria</h2>
<pre><code class="md language-md">GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client-server folder structure
WHEN I run `npm start` from the root directory
THEN I find that my application should start up the back end and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB database
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using Workbox
WHEN I register a service worker
THEN I should have my static assets precached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application</code></pre>

## Installation and Usage

In order to run this application, you will want to `git clone` this repository so that the code is on your local machine. Run `npm i` while in the root directory in order to install all necessary Node.js dependencies. Then run `npm start` to launch the server.

This application is hosted at Port 3000, put `http://localhost:3000/` in to the address bar of your browser while the server is running should display the user interface.

Hitting the "Install!" button allows you to save changes to the text editor regardless of whether you are online or offline.

## Contributors
 Please contact Meghan Harper at meghaneharper@gmail.com with any questions/concerns
