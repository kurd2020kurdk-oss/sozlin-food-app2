# Sozlin Food App

A Flutter mobile menu app for **کۆمپانیای سۆزلین** with:

- The supplied Sozlin logo at the top.
- 25 foods.
- Kurdish, English, and Arabic language switching.
- RTL support for Kurdish and Arabic.
- Search.
- List and grid views.
- Responsive Material 3 design.
- Food thumbnails loaded from the web, with emoji fallback.

## Build

Install Flutter, then from this project folder:

```bash
flutter pub get
flutter run
```

To create an Android APK:

```bash
flutter build apk --release
```

The APK will be generated at:

`build/app/outputs/flutter-apk/app-release.apk`

## Important: food images

The project now includes 25 local food illustrations under `assets/foods/`, so the menu images do not require an internet connection. The logo is also local.

The supplied logo is already included at:

`assets/logo.jpg`
