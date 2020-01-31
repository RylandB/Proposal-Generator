# Development Manual

## Tech Aspects

For mobile development we are using React Native v0.68, and ASP.net Core MVC v2.1 for our backend.

We are using android studio as our emulator for developing and running the application.

The IDE we used for developing Puma Mobile is Jetbrains Webstorm. Download it for Windows Here: https://www.jetbrains.com/webstorm/download/#section=windows

Puma Mobile is an extension of Puma that can request authorization tokens, add assets to a local portfolio, and send that portfolio to
the Puma backend to be evaluated and receive results to display from the submission, on a mobile device



## Getting Set Up
**NOTE: YOU WILL HAVE TO HAVE PUMA BACKEND INSTALLED AND RUNNING LOCALLY TO PROPERLY DEVELOP ON PUMA MOBILE** 

**PLEASE REFER TO THE PUMA DEVELOPMENT MANUAL TO GET IT SET UP AND RUNNING**

Download the Puma Mobile repository from here: https://github.com/japperales/CS495-Puma-Mobile

To set up React Native and Android Studio, please follow the guide here under "React Native CLI Quickstart" -> "Windows" -> "Android"(Ignore the "creating a new application" section) : https://facebook.github.io/react-native/docs/getting-started

Once you have set up React Native, Android, Studio and have the project opened in Webstorm, you may need to install the dependencies. Do this by running "npm install" through the terminal in the root directory of the application.

### Important Folders:

 -android: all of the assets and code for the android native application. Usually no need to touch items in here as react-native will handle the contents.
 
-ios: same as above.

-Screens: folder containg all of the rendered screens that are navigable by the bottom bar in the application. These are the parent components of each screen, and child components of the app.

-contexts: folder containing all of the context components used in the app. Think of these as Scoped global data that can be accessed by all child components should they choose.

-Components: folder containing all child components for any of the screen components.


### Important Files

-App.js This is the root component for the entire app, any context used here will be essentially global.

-package.json: this file lists all dependencies that are required by the project.

