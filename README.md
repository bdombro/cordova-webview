Generated from scratch using cordova CLI.

```bash
npm install -g cordova
cordova create wrap tech.benevolent.wrap wrap
cordova plugin install cordova-plugin-inappbrowser
# update www/js/index.js
cordova requirements
cordova platform add ios
cordova run ios --target='iPhone-11'
```