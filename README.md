# Front end build scripts

Allows for easy builds of javascript, css, html, and imgs.

This project uses the streaming build proccess tool "gulp"

## How to use seed project

Clone the seed repository, run `npm install` to grab the dependencies, and start building!

### Running the app

To use the build proccesses add your files to the src folder:

For js-hint:

    gulp jshint

To optimize images:

    gulp imagemin

To minify html:

    gulp htmlpage

To concat, stripdebugs, uglify, and combine js:

    gulp scripts

To autoprefix, minifyCSS, and combine css:

    gulp styles

To removed unused css classes (results are some what unpredictable):

    gulp uncss


## Contact

For more information on GULP please check out http://gulpjs.com/

