# Gallery App

## Description
This project aims to create a page that has a ListView where the images will be displayed. 

## Features
- Display images in a ListView
- Supports multiple image formats
- Support gallery and camera options

## Packages Used:
  - `rename`: ^3.0.2
  - `image_picker`: ^1.1.2
  - `firebase_core`: ^3.12.1
  - `permission_handler`: ^11.3.1
  - `flutter_launcher_icons`: ^0.14.3
    
## Firebase Integration
This app is connected to Firebase for backend services and uses Firebase Distribution for testing purposes.

### Steps to connect to Firebase:
1. Go to the Firebase Console.
2. Create da new project.
3. Added the app to the Firebase project.
4. Downloaeded the `google-services.json` file for Android and place it in the `app/` directory.
5. Added the Firebase SDK to the app.
6. Initialized Firebase in the app.

### Firebase Distribution
Firebase Distribution is used to distribute the app to testers.

##### To distribute the app:
1. After downloading app apk using `flutter build --release` command then uploading the apk to Firebase Distribution.
3. Invite testers to the Firebase project to get access to the app.

