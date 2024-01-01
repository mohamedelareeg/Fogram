# Fogram - Social Media App

Fogram is an Android application that serves as a social media platform, similar to Facebook and Instagram. It offers features such as posting, stories, chatting, groups, Firebase Realtime Database integration, and push notifications.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Configuration](#configuration)
- [Version Information](#version-information)
- [Running the Application](#running-the-application)
  - [Debugging](#debugging)
  - [Release Build](#release-build)
- [Publishing](#publishing)
- [Built With](#built-with)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Posts and Stories:** Share moments with friends through posts and stories.
- **Chatting:** Real-time chat functionality for private conversations.
- **Groups:** Create and join groups based on interests or communities.
- **Firebase Realtime Database:** Utilizes Firebase for real-time data synchronization.
- **Push Notifications:** Stay updated with push notifications for new activities.
- **Image Handling:** Supports image uploading, cropping, and applying filters.
- **Multi-Language Support:** Implements RTL (Right-to-Left) layout for multilingual support.

## Getting Started

### Prerequisites

- Android Studio
- Android device or emulator

### Installation

1. Clone the repository: `git clone https://github.com/mohamedelareeg/Fogram.git`
2. Open the project in Android Studio.
3. Build the project to resolve dependencies and compile the application.
4. Connect an Android device or use an emulator.
5. Run the application from Android Studio.

### Configuration

Ensure you have the required API keys and configurations for Firebase services. Update the necessary files with your configurations.

## Version Information

- **Compile SDK Version:** 34
- **Target SDK Version:** 34
- **Minimum SDK Version:** 23
- **Build Tools Version:** 34.0.0-rc2
- **App Version Code:** 1
- **App Version Name:** 1.0


## Running the Application

### Debugging

To run the application in debug mode:

1. Connect an Android device or use an emulator.
2. In Android Studio, select "Run" from the toolbar.
3. Choose the connected device/emulator and click "OK" to build and run the app.

### Release Build

To build a release version of the application:

1. Open the terminal in Android Studio.
2. Navigate to the project root directory.
3. Run the following command:

   ```bash
   ./gradlew assembleRelease
   
This command generates the release APK in the app/build/outputs/apk/release/ directory.

### Publishing
To publish the application to the Google Play Store:

1. gnerate a signing configuration for the release build in the app/build.gradle file.
2. Build the release version using the steps mentioned above.
3. In Android Studio, select "Build" > "Build Bundle(s) / APK(s)" > "Build APK(s)".
4. The generated APK will be available in the app/build/outputs/apk/release/ directory.

Follow the Play Console guidelines to create a new release, upload the APK, and publish the app.

## Built With

- [Java](https://www.java.com/) - The primary programming language.
- [Firebase](https://firebase.google.com/) - Comprehensive mobile and web app development platform.
- [Android Image Cropper](https://github.com/ArthurHub/Android-Image-Cropper) - Library for cropping images.
- [CircleImageView](https://github.com/hdodenhof/CircleImageView) - Circular ImageView library.
- [Compressor](https://github.com/zetbaitsu/Compressor) - Image compression library.
- [Universal Image Loader](https://github.com/nostra13/Android-Universal-Image-Loader) - Library for image loading and caching.
- [Glide](https://github.com/bumptech/glide) - Fast and efficient image loading library.
- [Android Image Filters](https://github.com/androidhive/ImageFilters) - Library for applying image filters.
- [Firebase UI Database](https://github.com/firebase/FirebaseUI-Android) - UI components for Firebase Realtime Database.
- [Android PhotoEditor](https://github.com/burhanrashid52/PhotoEditor) - Library for photo editing.
- [Multidex](https://developer.android.com/studio/build/multidex) - Library for enabling multidex support.

## Dependencies

Detailed information about the libraries and dependencies used in the project can be found in the [build.gradle](build.gradle) file.

## Contributing

Feel free to contribute to the development of Fogram by creating issues, submitting pull requests, or suggesting new features.

## License

This project is licensed under the MIT License.
