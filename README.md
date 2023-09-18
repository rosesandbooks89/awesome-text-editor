# awesome-text-editor

## Description
To build a text editor that runs in the browser. The app will be a single-page application that meets the PWA criteria. Additionally, it will feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline.


## Table of Contents
* [User Story](#user-story)
* [Acceptance Criteria](#acceptance-criteria)
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Struggles and Sources](#struggles-and-sources)
* [Link to Recordings](#link-to-recordings)
* [Questions](#questions)

## User Story

AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use

## Acceptance Criteria

* GIVEN a text editor web application
* WHEN I open my application in my editor
* THEN I should see a client server folder structure
* WHEN I run `npm run start` from the root directory
* THEN I find that my application should start up the backend and serve the client
* WHEN I run the text editor application from my terminal
* THEN I find that my JavaScript files have been bundled using webpack
* WHEN I run my webpack plugins
* THEN I find that I have a generated HTML file, service worker, and a manifest file
* WHEN I use next-gen JavaScript in my application
* THEN I find that the text editor still functions in the browser without errors
* WHEN I open the text editor
* THEN I find that IndexedDB has immediately created a database storage
* WHEN I enter content and subsequently click off of the DOM window
* THEN I find that the content in the text editor has been saved with IndexedDB
* WHEN I reopen the text editor after closing it
* THEN I find that the content in the text editor has been retrieved from our IndexedDB
* WHEN I click on the Install button
* THEN I download my web application as an icon on my desktop
* WHEN I load my web application
* THEN I should have a registered service worker using workbox
* WHEN I register a service worker
* THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
* WHEN I deploy to Heroku
* THEN I should have proper build scripts for a webpack application


## Installation
To install the application, please follow the instructions below:

1. Clone the repo
    ```sh
    git clone
    ```
2. Install NPM packages
    ```sh
    npm install
    ```
3. Run the application
    ```sh
    npm run start
    ```
4. Open the application in your browser
    ```sh
    http://localhost:3001/


## Usage

Open terminal install npm packages and run npm run start from the root directory to start cd client && build for the webpack mode production.

## License
This project does not have a license.

## Struggles and Sources
I struggled a bit with this project. I had a hard time getting the application to load with no consol errors. I had worked with a classmate that had used a plugin called polyfill. I tried to use that plug in but it caused errors with my workbox. I didn't realize that was an issue but after removing it the app works as it should


## Link to Recordings/Screenshot
Here is a link to the deployed app [here]("https://awesome-text-editor-2023-3b17a5e16de1.herokuapp.com/").

## Questions
If you have any questions, please contact me at the email below. Check out my Github portfolio for more of my projects!

Here is a link to my [GitHub Repo](https://github.com/rosesandbooks89/awesome-text-editor).

If you have any questions please email me at: rosesandbooks89@gmail.com.

©rosesandbooks89