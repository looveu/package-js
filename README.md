# Package.js

A javascript package manager and build tools designed for web app framework development in web browser environment.

## Installation:

You need install node.js and npm;See [http://nodejs.org/] and [http://npmjs.org/] ;

   $ cd package-js
   $ sudo npm install -g

## Getting started:

* Put package-js/src/Package directory to your statics js directory. For example as your-project/statics/jslibs/Package;
* Create your library,named "XLib";
* Create XLib/_nsconf_.js;
* Create XLib/init.js;
* Link XLib/_xproxy_.html to Package/_xproxy_.html if you want to cross domain load tpl.html or other assets;
* Create other packages;

For complete references,see docs/Package.html;