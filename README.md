# Description #
This is currently my setup for a bootstrapping a static web project using the Compass Framework and SASS on top of the HTML5 Boilerplate 2.0.

## How to Use ##
All Compass and SASS related files are in the /compass folder.
The config file is set up to be ready to go. For your edits in /compass/sass/ css to be compiled automatically, run the watcher command `compass watch` within the /compass folder. Then all your changes in the SASS (.scss) files will be compiled into the css folder.

### CSS Files (/css) ###
The base CSS file (/css/style.css) is pre-compiled using the HTML5 Boilerplate approved normalize.css. If compass is watching the /compass/sass folder then all your edits will truncate over styles.css so you should not be touching it at all, only editing from the scss files.

### JavaScript Files (/js) ###
Libraries are stored in the /js/libs folder, including jQuery and Modernizr.
The script.js is a starter file supplied so you can start writing base JavaScript but feel free to replace or use other frameworks and libraries to your choosing.

### Image Files (/img) ###
Create a folder named /img at trunk level and place your images there. You can also create additional folders to use with the Compass spriting engine (make sure to include @import "sprites/*.png" in base stylesheet).

## Documentation for Libraries ##
* <a href="http://html5boilerplate.com/">HTML5 Boilerplate</a>
* <a href="http://compass-style.org/">Compass Framework</a>
* <a href="http://sass-lang.com/">SASS</a>
* <a href="http://necolas.github.com/normalize.css/">normalize.css</a>
