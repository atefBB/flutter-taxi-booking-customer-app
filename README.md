# Flutter Taxi Booking Customer App

## Getting Started

`Flutter Taxi Booking Customer App` has "main.dart" as Entry Point.

https://user-images.githubusercontent.com/48312656/115983462-a721b100-a54d-11eb-8487-d122b5e70901.mp4

## Generate Android release

```bash
flutter clean && flutter build apk --release
```

Generate split APK's:

```bash
flutter clean && flutter build apk --split-per-abi --release
```

## iOS release steps

Set iOS deployment target

Follow below steps

setup flutter sdk
get packages
open runner.xcworkspace from ids folder
update version code in yaml
Bellow commands will generate the runner.app file

flutter clean
flutter build ios --release
Now open the xcode run/build to check if project has error

Select Product -> Archive
Follow the uploading steps
