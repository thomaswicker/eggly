Potion - SASS/Angular Framework
==========

Potion Framework - SASS/Angular/GulpJS

Potion's core includes a core set of modules: base, global and modules.

###BASE:
**grids.scss:** Core code for creating the responsive grid system behind Potion  
**helpers.scss:** A set of OOCSS (Object oriented CSS) helper classes to use throughout your HTML templates for quick margins, font styles, and more  
**main.scss:** A catch all style sheet for global styles  
**normalize.scss:** A set of styles used for any project to normalize your baseline CSS and HTML  
**reset.scss:** Global resets to remove standard browser padding, margins, etc  
**type.scss:** Typography styles  

###GLOBAL:
**mixins.scss:** Custom mixins for Potion used by all other .scss files  
**vars.scss:** Potion's variables used by all other .scss files. These can be overridden to change global colors, fonts, sizes, etc.    

###MODULES:
**alerts.scss:** Classes for styling basic alerts  
**buttons.scss:** Classes for Potion's custom button classes  
**code.scss:** Classes for styling code blocks within your HTML  
**forms.scss:** Classes for styling forms and form elements  
**headings.scss:** Classes for styling h1,h2,h3,h4,h5,h6 tags  
**icons.scss:** Classes for Potion's built in custom icon set  
**images.scss:** Classes for images and image positioning  
**lists.scss:** Classes for styling ordered and unordered lists  
**magictabs.scss:** Classes for Potion's responsive tab system  
**modals.scss:** Classes for styling Potion's custom modals and pop-ups  
**nav.scss:** Classes for styling desktop and mobile navigation  
**rules.scss:** Classes for styling hr tags and dividers  
**superheros.scss:** Classes for styling hero elements and banners  
**tables.scss:** Classes for styling Potion's responsive table system    

####INSTALLING NODE    
Potion does not use Node for its inner workings, but Node makes it easier to download and manage all of the dependencies for your project. To install Node, visit nodejs.org/download/ and download the installer package.

####INSTALLING GULP    
Gulp is the task runner that Potion leverages for build process and efficiency. It helps streamline the build process, compresses and minifies your code and processes SASS, etc. To install Gulp, you need to have first downloaded and installed node.js (which includes npm).

_Then, from the command line you can install the gulp-cli globally with:_
```
npm install -g gulp
```
_Change directory (cd/) to the root directory of your project and then run:_

_Now you can use the npm install command. This will use the package.json file within Potion to automagically install the necessary local dependencies for the project. When completed, you'll be able to run the various Gulp commands provided from the command line._
```
npm install
```
_Run gulp on the command line. This is the default command which runs all gulp tasks and then creates a watch process which will recompile on every change to your code._

```
gulp
```

####INSTALLING BOWER  
Bower is a front end dependency manager to take care of all your libraries like jQuery, Angular, etc. To install Bower, visit bower.io or you can install globally via command line with:

```
npm install -g bower  
```
_After bower is installed globally, from the command line type:_

```
bower install
```

_This will use the bower.json file within Potion to generate all of the front end dependencies needed for the project._
