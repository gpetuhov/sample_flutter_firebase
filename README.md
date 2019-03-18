# sample_flutter_firebase
Learn how to use Firebase in Flutter with Flutter Firebase Codelab

## Notes
* Flutter Plugin doesn't work on Android Studio Canary versions
* If Android Studio can't find Dart SDK then provide path to it in Settings: path_to_flutter_folder/bin/cache/dart-sdk
* To format text (if needed): Right-click the dart code and select Reformat Code with dartfmt
* To add external packages: edit pubspec.yaml file and click Packages get and import package in main.dart
* To wrap widget with another widget: place cursor on the widget and press Alt-Enter -> Choose "Wrap with new widget"
* Firebase requires Multidex support, so set minSdkVersion 21 in android/app/build.gradle to support Multidex 

## References
https://codelabs.developers.google.com/codelabs/flutter-firebase/#0