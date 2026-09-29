# GoTer

GoTer is an Android mobile application designed to connect users through communities, routes, challenges, and shared activities. The app allows people to create or join communities, organize races, track their movement on a map, communicate with other users, and monitor progress through statistics and notifications.

## Overview

The project combines:
- User authentication
- Community management
- Race creation and participation
- Map-based route visualization
- Notifications and messaging
- User profile and statistics

This application is built with Kotlin for Android and uses Firebase services for authentication and real-time data storage.

## Features

- User registration and login
- Google Sign-In support
- Biometric authentication
- Community creation and membership
- Race and event management
- Route visualization on a map
- User notifications
- Chat and social interaction
- Profile management
- Personal activity statistics

## Tech Stack

- Kotlin
- Android SDK
- Firebase Authentication
- Firebase Realtime Database
- Google Maps / Location Services
- OSMDroid
- Glide
- Gson
- OkHttp
- Coroutines

## Project Structure

```text
GoTer/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   └── com/example/gooter_proyecto
│   │   │   ├── res/
│   │   │   └── AndroidManifest.xml
│   ├── build.gradle.kts
│   └── proguard-rules.pro
├── build.gradle.kts
├── gradlew
├── gradlew.bat
├── settings.gradle.kts
├── gradle.properties
├── README.md
└── .gitignore

```
 ## Configuration
Make sure your Firebase project is configured with:

- Authentication methods enabled
- Realtime Database access rules configured
- Google Maps / location services enabled if required
  
## Main Screens
The application includes modules for:

- Login and registration
- Home dashboard
- User profile
- Communities
- Race creation
- Maps and route display
- Statistics
- Notifications
- Chat
  
