## Craft CMS Pages Structure and Webpack Basic Site Bootstrap

This package will give the barebones folders and files that are necessary to start a webpack project using minified JS, SCSS to CSS, and loaded image files.

### Folder Structure

`web` is the destination folder. `web/js`, `web/css`, and `web/img` are where minified js, css and images will be placed.

JS compiles ES6 syntax with Babel.

CSS compiles SASS and has autoprifixer enabled.

`src` is the working folder

`src/js/index.js` will be minified into `web/js/app.min.js` so import all working JS into it. SCSS stylesheets will also be required to be imported in order for them to be minified. `index.js` is already set up to compile `src/scss/styles.scss`.
