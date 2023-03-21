# sendbird-flutter-dashchat
![Platform](https://img.shields.io/badge/platform-flutter-blue.svg)
![Languages](https://img.shields.io/badge/language-dart-blue.svg)

## Introduction
This is a sample application showing how to integrate [Sendbird](https://sendbird.com)'s Flutter SDK with [DashChat](https://pub.dev/packages/dash_chat), a chat UI library, and [Firebase Cloud Messaging](https://firebase.google.com/docs/cloud-messaging) for push notifications.

## Requirements
- Dart 2.10.4
- Flutter 1.22.x or higher

To run the demo you will need an active Sendbird application id and at least two users. See [this introductory video](https://www.youtube.com/watch?v=QCS0eyO2Q3U) for instructions on how to create a new application and users.

You will also need to create a new Firebase project, enable the legacy messaging API, and copy the server key from Firebase into your Sendbird application. As part of settig up Firebase, you will need to add the `google-services.json` file from your Firebase project details in the `android/app` folder in this repo.

## Setup
See [Flutter install instructions](https://flutter.dev/docs/get-started/install) for your platform and preferred IDE.

Run the `flutter pub get` CLI command to update packages before running.

## Running
Once Flutter has been setup, check if there are any simulators/emulators/devices available to run on with:
`flutter devices`

Which will output something similar to:
```
iPhone 12 mini (mobile)                      • 487C50F3-5F34-4D7E-85BB-911977A813D3 • ios
Chrome (web)                                 • chrome                               • web-javascript
```

Execute `flutter run -d <device_id>` to run the app on a given device (ie `flutter run -d FB`)

The first screen should then appear:
![login_screen](https://imgur.com/wucQftU.png)