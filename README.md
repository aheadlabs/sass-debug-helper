# sass-debug-helper
Generates a CSS from SCSS files that let you color your html boxes for layout debuging purposes.

*web* file names could be changed at will, but make sure you change the @import value too.
The description of the files follow:
* source/
    * _webDebug.scss: is the file where all the debug colouring is generated and so, the file you should work on for customizing the "debug helpers". This is the file that must be imported in your project.
* docs/
    * project_implementation_demo.scss: is the main SCSS file where you generate your SASS code. This is an example of how you should import the import in your code.
    * classes_implementation_demo.css: is a web.scss compilation example, but don't pay attention to it since it depends on the values of the variables you set. For compiling .scss files to .css files see the [official SASS documentation](http://sass-lang.com/).

This is just an idea in SASS using the SCSS format, but you could be interested on doing the same with LESS or SASS format. Go ahead and fork this repository!
