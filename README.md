Sunny Day Single-Page Scroller
==============================

A one-pager scrolling website with multiple layers, paper-like textures, elements lifted, and a sticky-nav.

This site uses [Foundation](http://foundation.zurb.com/) Reveal (for Modals), and Magellan (for StickyNav).

Getting Started
---------------

1. [Install NodeJs](http://nodejs.org/).
2. `$ npm install -g grunt bower` to install [Grunt](http://gruntjs.com/and [Bower](http://bower.io/).
3. `$ npm install` to [install](https://npmjs.org/doc/install.html) development dependencies.
4. `$ bower install` to fetch front-end components using [Bower](http://bower.io/).
5. `$ grunt serve` to start up the development server and watch source files for changes.

Once you're satisfied with your changes, you can run 'grunt build' to compile the project into a production-ready form - which will be placed in the /dist folder.



Grunt tasks
-----------

 * `$ grunt serve`
   Starts a local web server (default: port 9000), opens the site in your default web browser, watches for changes in source files and rebuilds when changes are detected[^1].

 * `$ grunt build`
   Build a production ready copy of the site. Concatenates, minifies, and version stamps assets.

 * 'git fetch origin' and then 'git checkout gh-pages' to send the current build to GitHub-Pages


[^1][LiveReload](http://livereload.com/) has extensions for Chrome, Firefox and Safari.
