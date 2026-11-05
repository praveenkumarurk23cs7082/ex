EXPERIMENT 4: Form Validation using Stateful Widgets
Register Number: URK23CS7082
Course: 24CS2016 - Building Applications using Flutter

AIM
To design and implement a Car Mileage Calculator with Flutter Form,
TextFormField and stateful widgets that validates the user's input and shows
the calculated mileage dynamically.

FILES IN THIS FOLDER
  lib/main.dart          - complete source code of the application
  pubspec_snippet.yaml   - the relevant part of pubspec.yaml (dependencies)
  README.txt             - this file

PREREQUISITES
  - Flutter SDK installed (check with: flutter doctor)
  - An emulator, a physical device, or Chrome for web

HOW TO RUN
1. flutter create ex4_mileage_calculator
   cd ex4_mileage_calculator
2. Replace the generated lib/main.dart with the lib/main.dart from this folder.
3. flutter pub get
4. flutter run -d chrome   (or pick an emulator / device when asked)

STATUS
  The code was reviewed and checked for Dart syntax, but it was NOT executed
  in the environment where this record was prepared (Flutter SDK / Firebase
  were not available there). Please run it on your machine and capture your
  own screenshots.

SCREENSHOTS YOU NEED TO CAPTURE
Save them in Output_Screenshots/Ex4/ with these names:
  output_1.png  ->  Calculate pressed with empty fields (validation errors)
  output_2.png  ->  Valid values entered (e.g. 450 km and 30 litres)
  output_3.png  ->  Result card showing 15.00 km/l and Good rating
  output_4.png  ->  Form after pressing Reset

After saving the screenshots, open Final_Lab_Record.docx, delete the grey
placeholder box of each figure in Experiment 4 and insert the matching
picture (Insert > Pictures), keeping the caption below it.
