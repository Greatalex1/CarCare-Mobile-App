CarCare 🚗

CarCare is a Flutter mobile application designed to help vehicle owners manage and maintain their cars more efficiently. The app provides reminders for vehicle services, maintenance tips, towing services, and document management to ensure drivers keep their vehicles in optimal condition.

The goal of CarCare is to simplify car ownership by providing users with tools to track maintenance schedules, receive important reminders, and access vehicle-related services all in one place.

Features

🔐 User Authentication (Firebase Authentication)

🚗 Vehicle Management

⏰ Service Reminders

🛠 Maintenance Tips

🚛 Towing Service Requests

📄 Document Management

📱 Modern and Responsive UI

📂 Side Navigation Menu

☁ Firebase Integration

Tech Stack

Framework: Flutter

Language: Dart

Backend: Firebase

Authentication: Firebase Auth

Database: Cloud Firestore

Project Structure
lib/
│
├── common_widgets/       # Reusable UI components
├── pages/                # App screens
├── services/             # Firebase and app services
├── models/               # Data models
├── utils/                # Helper functions
└── main.dart             # App entry point
Prerequisites

Before running this project, ensure you have the following installed:

Flutter SDK

Dart

Android Studio or VS Code

Android Emulator or Physical Device

Firebase Project (for authentication and database)

You can install Flutter from:

https://flutter.dev/docs/get-started/install

Getting Started
1 Clone the Repository
git clone https://github.com/yourusername/carcare.git
2 Navigate into the project folder
cd carcare
3 Install dependencies
flutter pub get

This command downloads all required packages used in the project.

Running the Project

To run the project in development mode:

flutter run

This will launch the app on your connected device or emulator. Flutter builds a debug version by default when running the project.

Building the Project
Build APK

To generate a release APK:

flutter build apk --release

The APK file will be located at:

build/app/outputs/flutter-apk/app-release.apk

This file can be installed directly on Android devices.

Build Android App Bundle (Recommended for Play Store)
flutter build appbundle

The generated bundle will be located at:

build/app/outputs/bundle/release/app.aab

Google Play recommends using App Bundles for publishing apps.

Firebase Setup

Create a Firebase Project

Add an Android app in Firebase

Download google-services.json

Place it inside:

android/app/

Enable:

Firebase Authentication

Cloud Firestore

Assets

All project images and icons are located in:

assets/

Make sure they are declared in pubspec.yaml.

Contributing

Contributions are welcome. To contribute:

Fork the repository

Create a new branch

Commit your changes

Push the branch

Open a Pull Request

License

This project is licensed under the MIT License.
