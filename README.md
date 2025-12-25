# Geobill

Geobill is a native Android application built using Kotlin and Jetpack Compose. It is designed as a billing hosting solution with a user-friendly interface.

## Main Project

Geobill Main Project: https://github.com/alexistdev/geobill

## Features

- **Modern UI**: Built entirely with Jetpack Compose for a responsive and declarative UI.
- **Splash Screen**: Animated splash screen on launch (`SplashActivity`).
- **Authentication**: Secure login interface (`LoginActivity`).
- **Theme**: Custom blue-themed Material 3 design.

## Tech Stack

- **Language**: Kotlin
- **UI Framework**: Jetpack Compose (Material 3)
- **Minimum SDK**: 26 (Android 8.0 Oreo)
- **Target SDK**: 36 (Android 14/15)
- **Build System**: Gradle (Kotlin DSL)

## Prerequisites

- Android Studio Koala or newer recommended.
- JDK 11 or newer.
- Android SDK Platform 36 installed.

## Getting Started

1.  **Clone the repository:**
    ```bash
    git clone <repository-url>
    ```
2.  **Open in Android Studio:**
    - Open Android Studio and select "Open an existing Android Studio project".
    - Navigate to the cloned directory and select it.
3.  **Sync Gradle:**
    - Allow Android Studio to sync the project with Gradle files.
4.  **Run the App:**
    - Connect an Android device or start an emulator.
    - Click the "Run" button (Shift+F10) to build and launch the application.

## Project Structure

- `app/src/main/java/com/example/geobill`: Contains the Kotlin source code (Activities, Composables).
- `app/src/main/res`: Contains resources (drawables, mipmaps, values).
- `app/build.gradle.kts`: Application module build configuration.
