# AV Messenger

**AV Messenger** is a feature-rich Android chatting application built using Kotlin, XML, Firebase, and Android Studio. It provides a seamless and secure platform for real-time communication, ensuring a user-friendly experience for connecting with friends, family, or colleagues.

## Features

- **Real-time Messaging**: Send and receive messages instantly.
- **User Authentication**: Secure login and signup using Firebase Authentication.
- **Cloud Storage**: Messages and user data are stored in Firebase Firestore for reliability.
- **User-friendly Interface**: Intuitive design with clean navigation.
- **Notifications**: Get notified for new messages even when the app is closed.
- **Profile Management**: Update profile pictures and user details.
- **Secure Communication**: End-to-end security with Firebase.

## Tech Stack

- **Language**: Kotlin
- **UI Design**: XML
- **Backend**: Firebase Firestore and Firebase Realtime Database
- **IDE**: Android Studio
- **Other Tools**: Firebase Authentication, Firebase Cloud Messaging

## Installation

Follow these steps to run AV Messenger on your local machine:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Arihantv58/AV_Messenger.git
   ```

2. **Open the project in Android Studio:**
   - Launch Android Studio.
   - Click on "Open an Existing Project" and select the cloned repository folder.

3. **Set up Firebase:**
   - Create a Firebase project on [Firebase Console](https://console.firebase.google.com/).
   - Download the `google-services.json` file from Firebase and place it in the `app/` directory of the project.

4. **Sync the project:**
   - Open `build.gradle` (Project) and `build.gradle` (Module: app) files and sync the project with Gradle.

5. **Run the app:**
   - Connect an Android device or start an emulator.
   - Click the "Run" button in Android Studio to build and deploy the app.

## Usage

- Launch the app and sign up with your email.
- Log in using your credentials.
- Start chatting by selecting a user from the available list or search for a contact.
- Customize your profile through the settings menu.

## Screenshots

*Include screenshots of the app here, such as login screen, chat interface, and profile management.*

## Contributing

We welcome contributions to improve AV Messenger. To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push to your fork.
4. Open a pull request with a detailed description of your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

