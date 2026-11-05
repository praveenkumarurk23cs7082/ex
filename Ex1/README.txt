EXPERIMENT 1: Working with Widgets and Layouts
Register Number: URK23CS7082
Course: 24CS2016 - Building Applications using Flutter

AIM
To design and develop a Flutter application that displays a list of fruits
using the Row, Column, Container, Card and ListView widgets, and to organise
the user interface with a reusable custom widget.

FILES IN THIS FOLDER
  lib/main.dart          - complete source code of the application
  pubspec_snippet.yaml   - the relevant part of pubspec.yaml (dependencies)
  README.txt             - this file

PREREQUISITES
  - Flutter SDK installed (check with: flutter doctor)
  - An emulator, a physical device, or Chrome for web

IMPORTANT
Create the folder assets/images/ in the project and copy five images named
apple.jpg, orange.jpg, mango.jpg, pomegranate.jpg and banana.jpg into it. Add
the assets section from pubspec_snippet.yaml to your pubspec.yaml (keep the
indentation exactly as shown), then run flutter pub get. Without the images
the app still runs but shows grey placeholder icons - capture the screenshots
only after adding the real images.

HOW TO RUN
1. flutter create ex1_widgets_layouts
   cd ex1_widgets_layouts
2. Replace the generated lib/main.dart with the lib/main.dart from this folder.
3. Add the required packages:
   flutter pub add intl
4. flutter pub get
5. flutter run   (or pick an emulator / device when asked)

STATUS
  The code was reviewed and checked for Dart syntax, but it was NOT executed
  in the environment where this record was prepared (Flutter SDK / Firebase
  were not available there). Please run it on your machine and capture your
  own screenshots.

SCREENSHOTS YOU NEED TO CAPTURE
Save them in Output_Screenshots/Ex1/ with these names:
  output_1.png  ->  Home screen with the first fruits visible
  output_2.png  ->  List scrolled to show the remaining fruits
  output_3.png  ->  SnackBar message after tapping Buy Now

After saving the screenshots, open Final_Lab_Record.docx, delete the grey
placeholder box of each figure in Experiment 1 and insert the matching
picture (Insert > Pictures), keeping the caption below it.
