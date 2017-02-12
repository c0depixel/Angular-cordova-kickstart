# Project

Grunt/Angular/Cordova Kickstarter.

## Build & development

Initial run: `npm install` and `bower install`

Cordova:
- Platforms<br>
`cordova platform add browser`<br>
`cordova platform add android`<br>
`cordova platform add ios`
- Plugins:<br>
`cordova plugin add cordova-plugin-whitelist`<br>
`cordova plugin add cordova-plugin-device`<br>
`cordova plugin add cordova-plugin-crosswalk-webview`<br>
`cordova plugin add cordova-plugin-inappbrowser`<br>
`cordova plugin add ionic-plugin-keyboard`
- Run:<br>
`cordova run <platform name>`
* Help<br>
`cordova help`

Development run: `grunt` for building, `grunt serve` for development preview with livereload and `grunt serve:www` for production preview




