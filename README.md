# Lightning Browser — fork

This repository is a fork of [Anthony Restaino's Lightning Browser](https://github.com/anthonycr/Lightning-Browser). The upstream author and contributors created the original application. This repository's history and changes belong to the fork; the fork name does not imply authorship of upstream code.

The default branch is `browser2`. Review its commit history and source before relying on behavior described by upstream documentation. The original overview, feature list, contribution guidance, releases, and licensing information are available in the [upstream README](https://github.com/anthonycr/Lightning-Browser#readme).

## Repository contents

This is an Android browser codebase with Android application source, Gradle build files, a Gradle wrapper, changelog, license material, and test source sets. Refer to the checked-out branch for the exact state of each component; this README does not claim fork-specific features beyond what is visible in that branch.

## Build

1. Install Android Studio and a JDK supported by the branch's Gradle/Android Gradle Plugin versions.
2. Open the repository in Android Studio and allow Gradle sync to complete.
3. Select the Android app run configuration and launch on an emulator or device.
4. To build from a shell, use `./gradlew assembleDebug` (Windows: `gradlew.bat assembleDebug`).

The required Android SDK and toolchain depend on this older branch's Gradle configuration. A successful build is not asserted here; verify dependency resolution and build output before distributing an APK.

## License and attribution

This is a fork. Preserve upstream copyright and license notices when modifying or redistributing code. Read the repository's `LICENSE` and upstream licensing terms before reuse. Refer to the upstream project for its canonical history and releases.
