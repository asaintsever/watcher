# Watcher Mobile App (Android & iOS)

Mobile app for Technology Watch.

## Getting Started

This [Flutter](https://docs.flutter.dev/) application has been generated using Flutter CLI:

```sh
flutter create --platforms android,ios --org com.asaintsever watcher_mobile_app
```

## Set or update app icon

Using [flutter_launcher_icons](https://pub.dev/packages/flutter_launcher_icons) package with config in [pubspec.yaml](pubspec.yaml):

```yaml
flutter_launcher_icons:
  android: true
  ios: true
  image_path: "assets/icon/watcher-app.png"
  # Android adaptive icon configuration for better appearance
  adaptive_icon_background: "#1a1a2e"
  adaptive_icon_foreground: "assets/icon/watcher-app.png"
  # This removes white space and makes icon fill the safe zone
  min_sdk_android: 21
```

Run following command to update app icon using icon provided in `assets/icon` folder:

```sh
dart run flutter_launcher_icons
```
