# đ React Native Boilerplate
This starter React Native app is a  basic starting point to accelerate kicking off new mobile projects.  The project is setup with native module support ("[ejected](https://github.com/react-community/create-react-native-app/blob/master/EJECTING.md)").

## đ Requirements
Node 10 or greater is required. Development for iOS requires a Mac and Xcode 9.4 or up, and will target iOS 9 and up.

## đ Getting Started
To setup your mac for mobile development, [read more below](#mac-setup).

## đĻ Installing Dependencies
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

## đââī¸ Running the App
iOS
```bash
npx react-native run-ios --simulator="iPhone 13"
```

Android
```bash
```

## đ Useful Docs
- [React Native](https://reactnative.dev/docs/getting-started)
- [React Navigation](https://reactnavigation.org/)
- [Redux](https://redux.js.org/)
- [Redux Persist](https://github.com/rt2zz/redux-persist)
- [Axios](https://axios-http.com/docs/intro)
 - [initial boilerplate docs](https://thecodingmachine.github.io/react-native-boilerplate/)
- [initial boilerplate repo](https://github.com/thecodingmachine/react-native-boilerplate)

## âšī¸ Helpful Info
### đī¸ Directory layout 
- src/Assets: assets (image, audio files, ...) used by the application
- src/Components: presentational components
- src/Config: configuration of the application
- src/Containers: container components, i.e. the application's screens
- src/Navigators: react navigation navigators
- src/Services: application services, e.g. API clients
- src/Stores: redux actions, reducers and stores
- src/Translations: application strings, you can add languages files and be able to translate your app strings
- src/Theme: base styles for the application

### đ§ą Architecture 
- Presentational components are separated from containers. Containers usually define whole application screens. Presentational components are small components.
- With Redux, state is shared using global stores.

### đ Debugging

## Mac Setup
1) If homebrew is not installed, [view the command here](https://brew.sh/)
2) Node [LTS](https://nodejs.org/en/about/releases/) or only slightly behind should be used. Consider using [NVM](https://formulae.brew.sh/formula/nvm).
3) [Install Cocoapods](https://formulae.brew.sh/formula/cocoapods)