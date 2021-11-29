# 👋 React Native Boilerplate
This starter React Native app is a very basic starting point to accelerate starting new mobile projects. The project is setup with native module support ("[ejected](https://github.com/react-community/create-react-native-app/blob/master/EJECTING.md)").

## 🚀 Getting Started
### Requirements
Node 10 or greater is required. Development for iOS requires a Mac and Xcode 9.4 or up, and will target iOS 9 and up.

### 📦 Installing Dependencies
JavaScript
```bash
npm install
```

iOS
```bash
cd ios && pod install
```

Android
```bash
```

### 🏃‍♀️ Running the App
iOS
```bash
npx react-native run-ios -simulator="iPhone 13"
```

## 📖 Helpful Docs
- [React Native](https://reactnative.dev/docs/getting-started)
- [React Navigation](https://reactnavigation.org/)
- [Redux](https://redux.js.org/)
- [Redux Persist](https://github.com/rt2zz/redux-persist)
- [Axios](https://axios-http.com/docs/intro)
 - [initial boilerplate docs](https://thecodingmachine.github.io/react-native-boilerplate/)
- [initial boilerplate repo](https://github.com/thecodingmachine/react-native-boilerplate)

## Helpful Info
### Directory layout 🗂️
- src/Assets: assets (image, audio files, ...) used by the application
- src/Components: presentational components
- src/Config: configuration of the application
- src/Containers: container components, i.e. the application's screens
- src/Navigators: react navigation navigators
- src/Services: application services, e.g. API clients
- src/Stores: redux actions, reducers and stores
- src/Translations: application strings, you can add languages files and be able to translate your app strings
- src/Theme: base styles for the application
