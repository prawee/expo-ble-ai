# Testing BLE with Expo

## Required
- NodeJS

## Create Project
```bash
npm install -g expo-cli
npx expo init expo-ble-simple || npx create-expo-app --template
```

## First running
```bash
cd expo-ble-simple
yarn start || yarn ios || yarn android
```

## Install `BLE` Library
```bash
npx expo install react-native-ble-plx
yarn ios #ok
yarn android #ok
npx expo install react-native-permissions
```

## Build
### iOS
```bash
yarn clean
yarn ios # is ok
yarn ios -d # is ok
```

### Android
```bash
yarn clean
yarn android # is broken
yarn android -d # is broken
```