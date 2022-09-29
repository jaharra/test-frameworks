# test-mobile-appium


This mobile test framework uses the following tools:
 - Node
 - Java
 - Appium
 - Android Studio
 - VSCode (code editing)
 
 Tests are coded in `typescript` and uses `mocha` test framework with `junit` reporting style.
 
 
## Local setup:
  - Install node from [here](https://nodejs.org/en/download/)
  - Install Java from [here](https://www.oracle.com/java/technologies/downloads/)
  - Install appium using npm
    ```
    npm install -g appium
    ```
  - Download appium desktop app server from [here](https://github.com/appium/appium-desktop)
    ```
    npm install -g appium-doctor
    ```
  - *Optional*: Install appium doctor to detect cofiguration problems for ios and android prior to starting appium server
  - *Optional*: Download appium inspector [here](https://github.com/appium/appium-inspector) to inspect elements
  - Install android studio from [here](https://developer.android.com/studio/)
  
## Running locally:
  - Start appium on localhost `127.0.0.1` and port `4723`
  - Start your android emulator (by default Pixel 5 Android 13 configured in the test)
  - Open the project in `VSCode` and on the terminal run `npm install` to install all dependencies
  - To run the tests: `npm run test`
