# React-Native

## init project

### website

1. OS X - This guide assumes OS X which is needed for iOS development.
2. Homebrew is the recommended way to install Watchman and Flow.
3. Install Node.js 4.0 or newer.
4. brew install watchman. We recommend installing watchman, otherwise you might hit a node file watching bug.
5. brew install flow, if you want to use flow.

**We recommend periodically running brew update && brew upgrade to keep your programs up-to-date.**

### [github](https://github.com/facebook/react-native#examples)

1. git clone https://github.com/facebook/react-native.git
2. cd react-native && npm install
3. running
 - iOS:open any example (the .xcodeproj file in each of the Examples subdirectories) and hit Run in Xcode.
 - android:Note that you'll need the Android NDK installed, see [prerequisites](https://github.com/facebook/react-native/blob/master/ReactAndroid/README.md#prerequisites).
   + ./gradlew :Examples:Movies:android:app:installDebug
    + ./packager/packager.sh (Start the packager in a separate shell (make sure you ran npm install))

### [coderwall](https://coderwall.com/p/suvorq/beginning-react-native)

1. Clone main react native repository from github: 
 - git clone https://github.com/facebook/react-native
2. Copy Examples/SampleApp to Examples/AwesomeProject 
 - mkdir Examples/AwesomeProject cp -R Examples/SampleApp Examples/AwesomeProject
3. Run packager.sh to point to AwesomeProject just created: 
 - packager/packager.sh --root=./Examples/AwesomeProject
4. Now reopen again AwesomeProject in Xcode and start building.
