# Video SDK Android(Java) Code Sample

## What is it?

This code sample demonstrates a one-to-one and group video call application built with [Video SDK RTC Android SDK](https://docs.videosdk.live/docs/realtime-communication/sdk-reference/android-sdk/setup)

- Built for serverless video calling experience in Android.
- Scale it upto 5,000 participants with low code.
- 10,000 minutes free on monthly basis

![video-sdk-mobile.jpg](https://static.zujonow.com/github/video-sdk-mobile.jpg)

## Features

- [x] Video API with real-time audio, video and data streams
- [x] 5,000+ participants support
- [ ] Chat support with rich media.
- [ ] Screen sharing with HD and Full HD.
- [ ] Play realtime video in meeting
- [ ] Connect it with social media such as Facebook, Youtube etc (RTMP out support).
- [x] Intelligent speaker switch
- [x] Record your meetings on cloud
- [x] Customise UI and build other rich features with our new data streams such as whiteboard, poll, Q & A etc.

## Device support

Visit our official [documentation](https://docs.videosdk.live/docs/realtime-communication/sdk-reference/android-sdk/setup) for more information

## Prerequisites

You must have the following installed:

- Android Studio
- Android SDK
- Emulator or physical android device

## Getting started

1. Run the authentication server
   Follow [videosdk-rtc-nodejs-sdk-example](https://github.com/videosdk-live/videosdk-rtc-nodejs-sdk-example) to run authentication server.

2. Clone the repo

   ```sh
   $ git clone https://github.com/videosdk-live/videosdk-rtc-android-java-sdk-example.git
   ```

3. Create a `local.properties` file in the root directory of your android project with the api server url that points to the authentication server.

   ```
   api_server_url='http://192.168.0.101:9000'
   ```

4. Run the android app with `Shift+F10` or the `Run` button from toolbar

For more information, visit [official documentation](https://docs.videosdk.live/docs/realtime-communication/sdk-reference/android-sdk/setup)

Related

- [Video SDK RTC Prebuillt No Code App](https://github.com/videosdk-live/videosdk-rtc-js-prebuilt-embedded-example)
- [Video SDK RTC React App](https://github.com/videosdk-live/videosdk-rtc-react-sdk-example)
- [Video SDK RTC Node JS App](https://github.com/videosdk-live/videosdk-rtc-nodejs-sdk-example)