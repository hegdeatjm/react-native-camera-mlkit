---
id: expo_usage
title: Expo Usage
sidebar_label: Expo Usage
---

RNCamera of react-native-camera-mlkit is heavily based on Expo camera module. Thanks @aalices and Expo for the great work.

So you don't need to use **react-native-camera-mlkit** if you have the following config:

- If you are using [Expo](https://expo.io)
- If you are using [create-react-native-app](https://github.com/react-community/create-react-native-app)
- If you eject a [create-react-native-app](https://github.com/react-community/create-react-native-app) app and are using [ExpoKit](https://docs.expo.io/versions/latest/expokit/expokit)

## How to migrate from Expo to react-native-camera-mlkit

If you decide to eject without using ExpoKit, you can follow react-native-camera-mlkit installation instructions and just change the usage of your Camera component to RNCamera:

```diff
- import { Camera } from 'expo';
+ import { RNCamera } from 'react-native-camera-mlkit';

- <Camera
+ <RNCamera
```

## How to migrate from react-native-camera-mlkit to Expo Camera Module

```diff
- import { RNCamera } from 'react-native-camera-mlkit';
+ import { Camera } from 'expo';

- <RNCamera
+ <Camera
```
