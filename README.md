Lunte The Adventure
===================

A bird perspective adventure basing on a bomberman clone.


Node.js and NPM
===============

You need node.js and npm. Install it so that npm is in your PATH.

http://nodejs.org/

Afterwards, you need to install the package manager bower http://bower.io/.

    npm install -g bower (this might require root privileges)

You also need to install Grunt (http://gruntjs.com/getting-started), a
JavaScript task runner (similar to ant):

    npm install -g grunt-cli (this might require root privileges)


Getting dependencies
====================

This step needs to be done only once and after updating package.json:

    npm install

To download the actual project dependencies like jQuery, you have to invoke
bower:

    bower install


Running in browser
==================

Grunt can watch any files for updates and rebuild everything automatically.
Simply execute:

    grunt serve

This will start a server and open your browser to load the page. When you edit
any file, the browser will be informed to reload the page.


Building an official release
============================

To build an official release, use:

    grunt

The release will be stored in the dist/ folder.
