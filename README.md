# Grunt Starter Kit

Grunt starter kit to get up and running quickly with a static site.  `Grunt.js` comes configured with [Sass](https://github.com/gruntjs/grunt-contrib-sass), [PostCSS](https://github.com/nDmitry/grunt-postcss), [Concat](https://github.com/gruntjs/grunt-contrib-concat), and [Babel](https://babeljs.io/).

This uses PHP files to make templating easier, but you can convert the index.php to .html if you just need something simple.

## Instructions

Clone this repo to your local dev environment.

Change directories to the `grunt-starter` folder, then run `npm install`.

Then just run `grunt watch` and start coding.

### JS

Prefix your JS files with an underscore and save them in the `js/` folder (`_header.js` and `_footer.js` are already there as examples).  Concat will first combine all js files starting with an underscore to `js/app.js` and then Babel will compile down into `js/build/app.min.js`.  So make sure you don't direclty edit `js/app.js`.

### CSS/Sass

Save all your .scss files in `css/scss/`.