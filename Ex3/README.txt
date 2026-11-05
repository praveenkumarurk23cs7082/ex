EXPERIMENT 3: Add Interactivity to App – Input and Forms
Register Number: URK23CS7082
Course: 24CS2016 - Building Applications using Flutter

AIM
To develop a Flutter application that shows a predefined list of products and
lets the user search and filter them with input widgets, giving an interactive
experience.

FILES IN THIS FOLDER
  lib/main.dart          - complete source code of the application
  pubspec_snippet.yaml   - the relevant part of pubspec.yaml (dependencies)
  README.txt             - this file

PREREQUISITES
  - Flutter SDK installed (check with: flutter doctor)
  - An emulator, a physical device, or Chrome for web

HOW TO RUN
1. flutter create ex3_product_search
   cd ex3_product_search
2. Replace the generated lib/main.dart with the lib/main.dart from this folder.
3. flutter pub get
4. flutter run -d chrome   (or pick an emulator / device when asked)

STATUS
  The code was reviewed and checked for Dart syntax, but it was NOT executed
  in the environment where this record was prepared (Flutter SDK / Firebase
  were not available there). Please run it on your machine and capture your
  own screenshots.

SCREENSHOTS YOU NEED TO CAPTURE
Save them in Output_Screenshots/Ex3/ with these names:
  output_1.png  ->  Initial screen with all 8 products
  output_2.png  ->  Search text typed (e.g. "smart") with filtered results
  output_3.png  ->  A category chip selected (e.g. Accessories)
  output_4.png  ->  Search text with no match (e.g. "xyz") showing No products found

After saving the screenshots, open Final_Lab_Record.docx, delete the grey
placeholder box of each figure in Experiment 3 and insert the matching
picture (Insert > Pictures), keeping the caption below it.
