# Sedona
____

Frontend educational project based on the PSD file. Made with the perfect pixel approach.

The project was build with the following technologies and methodologies:
- Semantic HTML5
- CSS
- Sass
- BEM
- JavaScript
- Gulp
- NPM

## Table of contents
1. [How to compile the project](#install)
  1. [Install NPM](#npm)
  2. [Commands to compile the project](#compile)


### How to compile the project <a name="install"></a>
To compile the project you will need NPM and Gulp task runner

#### Install NPM<a name="npm"></a>
The project has a package.json file which stores all needed dependencies.

`$ npm install`

### Commands to compile the project <a name="compile"></a>

$ npm start
Builds a temporary development folder (tmp) and launches bowser-sync script to watch the changes mad in the html, sass and js files.
___

`$ npm build`

Builds distribution folder (dist) into which copy and minifies files which are ready to be send on the server.
____

`$ npm deploy`

Runs '$npm build ' comannd and deploys builded website to the github pages.