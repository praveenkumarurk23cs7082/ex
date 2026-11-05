EXPERIMENT 7: Data Persistence using Google Cloud Firestore
Register Number: URK23CS7082
Course: 24CS2016 - Building Applications using Flutter

AIM
To develop a Flutter application that stores and retrieves employee
information in Google Cloud Firestore so that the data remains available after
the application is closed and reopened.

FILES IN THIS FOLDER
  lib/main.dart          - complete source code of the application
  pubspec_snippet.yaml   - the relevant part of pubspec.yaml (dependencies)
  README.txt             - this file

PREREQUISITES
  - Flutter SDK installed (check with: flutter doctor)
  - An emulator, a physical device, or Chrome for web

IMPORTANT
Requires your own Firebase project and the generated lib/firebase_options.dart
file (see Firebase setup below).

FIREBASE SETUP
1. Create a project in the Firebase Console (console.firebase.google.com) and register an Android or Web app in it.
2. Open Build → Firestore Database → Create database and start it in test mode for this lab.
3. In the Flutter project folder run "flutter pub add firebase_core cloud_firestore", then run "flutterfire configure" to generate lib/firebase_options.dart.

HOW TO RUN
1. flutter create ex7_firestore_employees
   cd ex7_firestore_employees
2. Replace the generated lib/main.dart with the lib/main.dart from this folder.
3. Add the required packages:
   flutter pub add firebase_core cloud_firestore
   flutterfire configure
   (flutterfire configure creates lib/firebase_options.dart - see Firebase setup below)
4. flutter pub get
5. flutter run   (or pick an emulator / device when asked)

STATUS
  The code was reviewed and checked for Dart syntax, but it was NOT executed
  in the environment where this record was prepared (Flutter SDK / Firebase
  were not available there). Please run it on your machine and capture your
  own screenshots.

SCREENSHOTS YOU NEED TO CAPTURE
Save them in Output_Screenshots/Ex7/ with these names:
  output_1.png  ->  Firebase Console - employees collection with documents
  output_2.png  ->  Employee form filled in the app
  output_3.png  ->  Saved employees listed in the app
  output_4.png  ->  Records shown again after restarting the app

After saving the screenshots, open Final_Lab_Record.docx, delete the grey
placeholder box of each figure in Experiment 7 and insert the matching
picture (Insert > Pictures), keeping the caption below it.
