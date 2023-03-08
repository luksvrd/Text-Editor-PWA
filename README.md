# 19 Progressive Web Applications (PWA): Text Editor


![J.A.T.E.](https://github.com/luksvrd/Text-Editor-PWA/blob/main/jate.jpg)


## Built Using

JavaScript, Node.js, Express.js, IndexedDB, idb, webpack, babel, and Heroku

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Questions](#questions)
- [Contributing](#contributing)
- [License](#license)

### \* [Description](#description)

This is a text editor that runs in the browser and can function offline. Its a single-page application that meets the PWA criteria and features a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser.

Started with an existing application and implemented methods for getting and storing data to an IndexedDB database. Used a package called idb, which is a lightweight wrapper around the IndexedDB API. It features a number of methods that are useful for storing and retrieving data, and is used by companies like Google and Mozilla.

```
User Story:
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use

Acceptance Criteria:
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
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
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application

```

### \* [Installation](#installation)

This application assumes you have a 'complete dev environment' setup - a terminal, Node, & VS Code. To get started, Fork the repository and inside your terminal, run `git clone` to clone the new repo, then `cd` into it and execute `npm i` to install all the dependancies.

### \* [Usage](#usage)

Once you have started installed all dependancies, you can execute the commands below to get the app built & running.

* All of the necessary scripts will run from the root directory `package.json`.

* `npm run start:prod` in the command line to run the build script and start our server.

* `npm run server` in the command line to start the server only, without the client.

* `npm run install` in the command line to install all of the client's dependencies.

* `npm run build` in the command line and have our client run the webpack build script.

* `npm run client` in the command line to start the client only, without the server.

* `npm run start` in the command line to start both the client and server.

![npm](https://github.com/luksvrd/Text-Editor-PWA/blob/main/npm.jpg)

### \* [Questions](#questions)

If you have any questions about the repo, open an issue at https://github.com/luksvrd/crispy-social-phone. You can also find more of my work on [Github](https://github.com/luksvrd)

### \* [Contributing](#contributing)

Contributors: Lukas Virden

- Thanks to [Manav Misra](https://github.com/manavm1990/html-css-practice) for the Starter Templates & all his teachings throughout the WUSTL Coding Bootcamp.

### \* [License](#license)

- [![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)
- ![NPM](https://img.shields.io/npm/l/inquirer?style=plastic)
- ![badmath](https://img.shields.io/github/languages/top/lernantino/badmath)
- [![npm collaborators](https://img.shields.io/npm/collaborators/inquirer)](https://www.npmjs.com/package/inquirer)
- [![Dependents (via libraries.io)](https://img.shields.io/librariesio/dependents/npm/inquirer)](https://www.npmjs.com/package/inquirer)
- [![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](code_of_conduct.md)

- [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Copyright (c) 2022 Lukas Virden, All rights reserved.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
