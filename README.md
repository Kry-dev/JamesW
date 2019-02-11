# Bootstrap 4 with sass and gulp 4
A Bootstrap 4.1.3 with font-awesome, sass, gulp 4 tasks, browserSync (with hot-reloading). You can override bootstrap sass variables by placing those 
variables in `yourdirectory/assets/scss/_custom_variables.scss`

## Pre-requisite
- [Node.js](https://nodejs.org/en/download/ "Node Js")
- NPM (Comes with Node.js)
- [Gulp](https://gulpjs.com/ "Gulp")

Install Gulp Globally

    $ npm -g install gulp

## Getting started

1. Clone repository:
`git clone https://github.com/Kry-dev/JamesW.git`

2. Change directory:
`cd directory-name`
    
3. Install all dependencies and libraries:
`npm install`

4. Run Gulp Task:
  - `gulp`      - To compile scss to css, minify css and js and build ready for production files in **dist** folder.

  - `gulp dev`  - Starts a local server with browserSync and hot reloading on changes to files (HTML, SCSS, JS).
   
