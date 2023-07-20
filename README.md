# PWA - TEXT EDITOR

[![github-follow](https://img.shields.io/github/followers/israel2800?label=Follow&logoColor=blue&style=social)](https://github.com/renansm93)
[![project-languages-used](https://img.shields.io/github/languages/count/israel2800/team-profile-generator-challenge?color=important)](https://github.com/israel2800/NoSQL-Social-Network-API)
[![project-top-language](https://img.shields.io/github/languages/top/israel2800/NoSQL-Social-Network-API?color=orange)](https://github.com/israel2800/NoSQL-Social-Network-API)
[![node.js](https://img.shields.io/node/v/c?color=orange)](https://nodejs.org/en/)
[![npm](https://img.shields.io/npm/v/npm?color=orange&logo=npm)](https://www.npmjs.com/package/inquirer)
[![license](https://img.shields.io/badge/License-MIT-brightgreen.svg)](https://choosealicense.com/licenses/mit/)



## Table of Contents

* [Description](#description)
* [Access](#access)
* [Installation](#installation)
* [Usage](#usage)
* [Credits](#credits)

## Description

The app will be a single-page application that meets the PWA criteria. Additionally, it will feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline. 

### User Story

```
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

### Tools and Technologies Used

To create this application, I used:
- IndexedDB (via the idb package) as a database
- Webpack to bundle front-end code
- Workbox to create a service worker that caches static assets
- And, Heroku.

### Screenshot of Application

![screenshot-of-application](./assets/images/screenshot-of-application.png)

![Service-worker](./assets/images/Service-worker.png)

## Access

### Code Repository

The repository where the code is saved is on Github. To access it, click [here](https://github.com/renansm93/PWA_Text-Editor).

### Live Application

My application is deployed on Heroku. To access it, click [here](https://renan-text-editor-6dfeb8705062.herokuapp.com/).

## Installation

To install necessary dependencies, run the following command:

```
npm i
```

## Usage

To use the application from the command line (after installing dependencies):
1. Open the root directory of the repository in your terminal or bash.
2. Bundle the front-end code by entering ```npm run build``` in the command line.
3. Start the server by entering ```npm run start``` in the command line.
4. Go to the port on your local host.
5. Click the "Install" button.

Alternatively, to use the live application, click [here](https://renan-text-editor-6dfeb8705062.herokuapp.com/).

## Credits

- This is the [starter code](https://github.com/coding-boot-camp/cautious-meme) used.

<hr>
<p align='center'><i>
This README was generated with ❤️ by RENAN SPILKA MIRANDA
</i></p>
