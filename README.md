# Vehicle Inspection

A simple GluonFX JavaFX mobile application for Vehicle Inspection.

## Hello World Version

Displays "Vehicle Inspection" on screen.

## Building

### Prerequisites
- Maven
- GraalVM with GluonFX support
- Android SDK / NDK for APK

### Desktop Run
```bash
mvn clean gluonfx:run
```

### Build Android APK
```bash
mvn clean -Pandroid gluonfx:build gluonfx:package
```

APK will be generated in the `target` directory.

**Note:** Building native Android APK requires proper setup of GraalVM, Android SDK. Check Gluon docs for details.

Repo: https://github.com/Myamba255/vehicle-inspection