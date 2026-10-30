Reply App - Adaptive Content for Large Screens
=================================
Completed Android Basics with Compose codelab: [Build an adaptive app with an adaptive layout](https://developer.android.com/codelabs/basic-android-kotlin-compose-adaptive-content-for-large-screens?hl=es-419).

Based on the official Google training repository, starting from `nav-update`.
Includes compact, medium, and expanded previews, adaptive list-detail content,
and the five instrumented tests requested by the codelab.

Introduction
------------
The Reply app is a basic email client that displays various categories of your
inbox. This app is used to illustrate the concept of adaptive layouts.

Pre-requisites
--------------

* Experience with Kotlin syntax
* How to create and run a project in Android Studio
* How to create composable functions
* How to create compose navigation

Getting Started
---------------

1. Install Android Studio, if you don't already have it.
2. Download the sample.
3. Import the sample into Android Studio.
4. Build and run the sample.

Instrumented tests
------------------

Use the shared Android Studio configurations `Pruebas compactas`,
`Pruebas medianas`, and `Pruebas expandidas` with a matching emulator size.
The same groups can be run from the command line:

```shell
./gradlew connectedDebugAndroidTest -Pandroid.testInstrumentationRunnerArguments.annotation=com.example.reply.test.TestCompactWidth
./gradlew connectedDebugAndroidTest -Pandroid.testInstrumentationRunnerArguments.annotation=com.example.reply.test.TestMediumWidth
./gradlew connectedDebugAndroidTest -Pandroid.testInstrumentationRunnerArguments.annotation=com.example.reply.test.TestExpandedWidth
```
