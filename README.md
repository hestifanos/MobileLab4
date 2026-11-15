# Mobile Task App

A small native Android task-list project built with Kotlin and AndroidX. Tasks can be created with an optional deadline and description, searched, and retained across configuration changes. Tasks are held in memory and do not persist across app restarts.

## Build and run

Open the repository in Android Studio, sync the Gradle project, and run the `app` configuration on an emulator or Android device.

- Minimum Android version: API 24
- Compile/target SDK: API 36
- Gradle runtime: JDK 17 or newer (the app bytecode targets Java 11)

Run tests with the Gradle wrapper:

```bash
./gradlew test
./gradlew connectedAndroidTest
```

## Project structure

```text
app/src/main/java/com/example/todo/MainActivity.kt   Main task screen
app/src/main/java/com/example/todo/NewTask.kt        Task-entry screen
app/src/main/res/layout/                             Screen layouts
app/src/test/                                        JVM unit tests
app/src/androidTest/                                 Android instrumentation tests
```

This repository currently has the same tracked application tree as `TodoApp`; compare the two before choosing which portfolio entry to retain.
