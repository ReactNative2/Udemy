# 

## Tech Stack
* [React Native Getting Started](http://facebook.github.io/react-native/docs/getting-started.html)

<b>Dependency</b> | Purpose
------------ | -------------
XCode | Package our code + the React Native library into an installable app and run in on the iOS simulator
Homebrew | Used to install node
Node/NPM | Node runs Javascript ouside of the browser.  NPM is used for installing and managing dependencies.  Node and NPM come together.
watchman | Watches files on the hard drive and waits for them to change.
RN CLI | React Native Command Line Interface.  Used to generate new React Native projects.

* To run your app on iOS:
   cd /Users/vukdukic/ARC-ReactNative/albums
   react-native run-ios
   - or -
   Open ios/albums.xcodeproj in Xcode
   Hit the Run button
* To run your app on Android:
   cd /Users/vukdukic/ARC-ReactNative/albums
   Have an Android emulator running (quickest way to get started), or a device connected
   react-native run-android
* [Troubleshooting React Native Startup](https://rallycoding.com/blog/troubleshooting-react-native-startup/)
* [API music_albums](http://rallycoding.herokuapp.com/api/music_albums)

## CLI
* react-native init auth
* react-native run-ios
