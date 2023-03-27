# Flutter Iconsax

[Iconsax](http://fluttericonsax) port to Flutter. Tis package renders the icons as SVG pictures.

## Usage

```dart
class MyExampleWidget extends StatelessWidget {
    @override
    Widget build(BuildContext context) {
        return Iconsax(
            Iconsaxs.user,
            style: IconsaxStyle.outline,
            color: Colors.blue,
            size: 30.0
        );
    }
}
```

## Install

Add `flutter_iconsax` package to your `pubspec.yaml`

```yaml
dependencies:
  flutter_iconsax: # Latest version
```

You can also run `flutter pub add flutter_iconsax` to quickly add latest version from your CLI.
