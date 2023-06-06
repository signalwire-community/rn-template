# React Native Template for create-react-native-app

Use this template to quickly initialize React Native apps with SignalWire
dependencies:

```bash
npx create-react-native-app --template https://github.com/signalwire-community/rn-template
```

Based on the
[with-webrtc](https://github.com/expo/examples/tree/master/with-webrtc) Expo
example.

![Supports iOS](https://img.shields.io/badge/iOS-000.svg?style=flat-square&logo=APPLE&labelColor=999999&logoColor=fff)
![Supports Android](https://img.shields.io/badge/Android-000.svg?style=flat-square&logo=ANDROID&labelColor=A4C639&logoColor=fff)

## 🏃 How to build and run locally

- [Setup development Environment](https://reactnative.dev/docs/environment-setup)
- 🍎 Build/Run on iOS `yarn ios`.
  - WebRTC doesn't work in the iOS Simulator since there is no camera. Run
    `expo run:ios -d` to select a connected iOS device.
- 🤖 Build/Run on Android `yarn android`.
