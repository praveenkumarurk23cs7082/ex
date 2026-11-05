EXPERIMENT 6: Data Persistence using SQLite
Register Number: URK23CS7082
Course: 24CS2016 - Building Applications using Flutter

AIM
To design and develop a Flutter application that stores and retrieves student
records in an SQLite database by implementing the Create and Read operations.

FILES IN THIS FOLDER
  lib/main.dart          - complete source code of the application
  pubspec_snippet.yaml   - the relevant part of pubspec.yaml (dependencies)
  README.txt             - this file

PREREQUISITES
  - Flutter SDK installed (check with: flutter doctor)
  - An emulator, a physical device, or Chrome for web

IMPORTANT
Run on an Android emulator or a physical device (flutter run). sqflite does
not work on Flutter Web.

HOW TO RUN
1. flutter create ex6_sqlite_students
   cd ex6_sqlite_students
2. Replace the generated lib/main.dart with the lib/main.dart from this folder.
3. Add the required packages:
   flutter pub add sqflite path
4. flutter pub get
5. flutter run   (or pick an emulator / device when asked)

STATUS
  The code was reviewed and checked for Dart syntax, but it was NOT executed
  in the environment where this record was prepared (Flutter SDK / Firebase
  were not available there). Please run it on your machine and capture your
  own screenshots.

SCREENSHOTS YOU NEED TO CAPTURE
Save them in Output_Screenshots/Ex6/ with these names:
  output_1.png  ->  Empty student form
  output_2.png  ->  Save pressed with empty fields (validation errors)
  output_3.png  ->  A student saved and shown in the list
  output_4.png  ->  Records still listed after closing and reopening the app

After saving the screenshots, open Final_Lab_Record.docx, delete the grey
placeholder box of each figure in Experiment 6 and insert the matching
picture (Insert > Pictures), keeping the caption below it.
