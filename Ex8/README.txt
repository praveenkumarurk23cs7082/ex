EXPERIMENT 8: Searching Information in Google Firestore Database
Register Number: URK23CS7082
Course: 24CS2016 - Building Applications using Flutter

AIM
To develop a Flutter application that retrieves book information from Google
Firestore based on the title entered by the user and displays the details on
the screen.

FILES IN THIS FOLDER
  lib/main.dart          - complete source code of the application
  pubspec_snippet.yaml   - the relevant part of pubspec.yaml (dependencies)
  README.txt             - this file

PREREQUISITES
  - Flutter SDK installed (check with: flutter doctor)
  - An emulator, a physical device, or Chrome for web

IMPORTANT
Requires your own Firebase project, the generated lib/firebase_options.dart,
and the books collection with the sample data.

FIREBASE SETUP
1. Create a project in the Firebase Console (console.firebase.google.com) and register an Android or Web app in it.
2. Open Build → Firestore Database → Create database and start it in test mode for this lab.
3. In the Flutter project folder run "flutter pub add firebase_core cloud_firestore", then run "flutterfire configure" to generate lib/firebase_options.dart.
4. Manually create a collection named books and add the documents given in the sample data below.

Sample data (type these documents in by hand in the Firebase Console):
  id | title | author | copies
  B101 | Flutter in Action | Eric Windmill | 5
  B102 | Clean Code | Robert C. Martin | 3
  B103 | Dart Apprentice | Jonathan Sande | 0

HOW TO RUN
1. flutter create ex8_firestore_book_search
   cd ex8_firestore_book_search
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
Save them in Output_Screenshots/Ex8/ with these names:
  output_1.png  ->  Firebase Console - books collection
  output_2.png  ->  Search for "Flutter in Action" (details shown)
  output_3.png  ->  Search for "Dart Apprentice" (0 copies, red warning)
  output_4.png  ->  Search for a title that does not exist (Book not found)

After saving the screenshots, open Final_Lab_Record.docx, delete the grey
placeholder box of each figure in Experiment 8 and insert the matching
picture (Insert > Pictures), keeping the caption below it.
