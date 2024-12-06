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