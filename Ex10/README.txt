EXPERIMENT 10: User Login Authentication with Google Firestore Database
Register Number: URK23CS7082
Course: 24CS2016 - Building Applications using Flutter

AIM
To develop a Flutter application in which a user logs in with an email and
password stored in Google Firestore, using a clean and professional user
interface.

FILES IN THIS FOLDER
  lib/main.dart          - complete source code of the application
  pubspec_snippet.yaml   - the relevant part of pubspec.yaml (dependencies)
  README.txt             - this file

PREREQUISITES
  - Flutter SDK installed (check with: flutter doctor)
  - An emulator, a physical device, or Chrome for web

IMPORTANT
Requires your own Firebase project, the generated lib/firebase_options.dart,
and the users collection with the sample data.

FIREBASE SETUP
1. Create a project in the Firebase Console (console.firebase.google.com) and register an Android or Web app in it.
2. Open Build → Firestore Database → Create database and start it in test mode for this lab.
3. In the Flutter project folder run "flutter pub add firebase_core cloud_firestore", then run "flutterfire configure" to generate lib/firebase_options.dart.
4. Manually create a collection named users and add documents with the fields name, email, phone and password, as in the sample data below.

Sample data (type these documents in by hand in the Firebase Console):
  name | email | phone | password
  Aarav Kumar | aarav@example.com | 9876543210 | pass@123
  Divya S | divya@example.com | 9123456780 | divya@456

HOW TO RUN
1. flutter create ex10_firestore_login
   cd ex10_firestore_login
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
Save them in Output_Screenshots/Ex10/ with these names:
  output_1.png  ->  Login screen
  output_2.png  ->  Invalid email format entered (validation message)
  output_3.png  ->  Wrong credentials (Invalid email or password)
  output_4.png  ->  User Dashboard after successful login

After saving the screenshots, open Final_Lab_Record.docx, delete the grey
placeholder box of each figure in Experiment 10 and insert the matching
picture (Insert > Pictures), keeping the caption below it.
