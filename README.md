# FamilyBoard
Online Family Board  
Family Board is an multi-platform app primarily for phones.  
~~App is being synced with a server so your data is accesible virtually anywhere.~~  
Everything in this app is synced locally. No data is sent to the cloud.

### Why this?
This is my semi-annual work. It's a school project.  
Assignment: Create a JavaScript app with minimum of 800 lines

My goal was to learn a new JS framework. In the end I went with React Native.

# How to run this app
This is a _React Native_ app.  
This app was tested on Android only. No guarantee, that it'll work on iOS

### Dependencies  
- Node.js installed  
- React Native installed  
    ````
    npm i react-native -g
    ````
- Android Studio with at least one Virtual device configured  
OR
- An android device with USB debugging allowed  
- ANDROID_SDK_ROOT defined in PATH  
    It is usually loccated in  `C:\Users\yourname\AppData\Local\Android\sdk`

### Follow these  
1. Download this repo
2. Start an emulator or Connect a device to your computer via USB cable
3. In the root folder of this project open Terminal/Command prompt (where App.js is located)  
4. Run the React Native project  
    ````
    npm i
    react-native run-android
    ````

# Known Issues
#### When building app, React sometimes throws EPERM error  
**To fix this:**  
    1. Open Command Prompt in root folder of this project  
    2. Type in these  
        ````
        a. cd android  
        b. gradlew clean  
        ````  
    3. Run the app  

>For what I know, this only happens on Windows  

#### Added notes do not show up if the list is empty  
**To fix this**  
    1. Restart the app  

>This only happens after fresh install or wiping data  
>The notes you added should be there, React possibly didn't updated the DOM
