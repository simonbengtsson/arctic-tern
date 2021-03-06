# Västtrafik Nära
---

Nearby stops, departures and journeys for västtrafik

App Store: https://itunes.apple.com/gb/app/arctic-tern/id1439743742?mt=8

Google Play: https://play.google.com/store/apps/details?id=com.simonbengtsson.arctictern

![Screenshot](https://is5-ssl.mzstatic.com/image/thumb/Purple128/v4/0a/75/55/0a755505-f237-7894-201d-7cf30bc9e023/pr_source.png/460x0w.png)

### Roadmap
- Search for stop
- Favorite stops
- Filter by direction
- Line map

### Running
- Clone and install Android Studio with the Flutter and Dart plugins
- Create a env.dart from env.dart.sample
- Choose a simulator or device and run the app through Android Studio

### Publish iOS
- Update pubspec.yaml version number
- flutter build ipa
- Open archive in xcode and distribute

### Publish Android
- Create or verify key.properties content
- Update pubspec.yaml version number
- flutter build apk
- Create new release with apk in Google Play Console (Production -> New Release)

### Dart cons
- Semi-colons and extra parenthesis
- Underscore instead of private