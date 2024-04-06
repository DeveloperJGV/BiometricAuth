# BiometricAuth

This project demonstrates the use of biometric authentication in an Android application using Kotlin and Jetpack Compose.

## Features

- Biometric Authentication: The application uses the AndroidX Biometric library to authenticate users with their biometric data (fingerprint, face recognition, etc.).
- Android Version Compatibility: The application checks the Android version running on the device and sets the biometric authentication accordingly.
- Biometric Prompt: The application displays a biometric prompt for user authentication. The prompt includes a "Cancel" button for Android versions older than Android 11.0.
- Error Handling: The application handles various biometric authentication results, such as hardware unavailability, feature unavailability, authentication not set, authentication error, authentication failure, and authentication success.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Android Studio Iguana | 2023.2.1 or later
- Android SDK version 30 or later


## Built With

- [Kotlin](https://kotlinlang.org/)
- [Jetpack Compose](https://developer.android.com/jetpack/compose)
- [AndroidX Biometric](https://developer.android.com/jetpack/androidx/releases/biometric)
- [Gradle](https://gradle.org/)

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/yourusername/your-repo-name/CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
