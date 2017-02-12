# Project

Grunt/Angular/Cordova Kickstarter.

## Build & development

Initial run: `npm install` and `bower install`

Cordova:
* Platforms
`cordova platform add browser`
`cordova platform add android`
`cordova platform add ios`
* Plugins:
`cordova plugin add cordova-plugin-whitelist`
`cordova plugin add cordova-plugin-device`
`cordova plugin add cordova-plugin-crosswalk-webview`
`cordova plugin add cordova-plugin-inappbrowser`
`cordova plugin add ionic-plugin-keyboard`
* Run:
`cordova run <platform name>`
* Help
`cordova help`

Development run: `grunt` for building, `grunt serve` for development preview with livereload and `grunt serve:www` for production preview




