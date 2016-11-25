# Application Starter Boilerplate
Electron starting point with all-platform compilation. Over time I will also create one with a starter Aurelia/Bootstrap framework integrated. Then another with both Cordova (or Phonegap Build) and Electron in a single build step.

## To Use:
After cloning the repo, change the icons in the 'build' folder. Then add your HTML5 application to the 'src' folder. Finally, change the app ID in the package.json file as well as the app name and description in the app/package.json file. Then ```npm start``` to run test version or ```npm run release``` to build distributable installers.

Note: On a Mac, you'll have to have an installed developer ID certificate in your keychain for the code signing step.


## Install and Build

```
git clone git@github.com:chadananda/app-start.git
cd app-start
npm install
npm start
```

### Credits
This customized boilerplate was based on [https://github.com/szwacz/electron-boilerplate/tree/master](https://github.com/szwacz/electron-boilerplate/tree/master) and [https://github.com/jimschubert/electron-aurelia-example](https://github.com/jimschubert/electron-aurelia-example)


















