# [Ionic 4 | In App Browser | Abrir navegador web dentro y fuera de aplicación](https://www.youtube.com/watch?v=YWeNCNT0qkA)

<img src="https://github.com/martha-softwaredeveloper/Ionic4-InAppBrowser/blob/master/src/assets/screenshot1.png" width="300"/>

<img src="https://github.com/martha-softwaredeveloper/Ionic4-InAppBrowser/blob/master/src/assets/screenshot2.png" width="300"/>

## Installation

1. ionic start Ionic4-InAppBrowser blank --type=angular
2. ionic cordova plugin add cordova-plugin-inappbrowser
3. npm install @ionic-native/in-app-browser
from https://ionicframework.com/docs/native/in-app-browser

## Configuration

1. At app.module.ts, add InAppBrowser in providers
2. At home.page.ts, create url function
3. At home.page.html, add button

## Test

1. Open Android Studio's emulator
2. ionic cordova run android
3. ionic cordova run ios
4. iOS doesn't seem to work with the self target but it open the link

## Author

RobotSolar