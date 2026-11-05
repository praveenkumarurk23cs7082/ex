EXPERIMENT 5: Application State Management
Register Number: URK23CS7082
Course: 24CS2016 - Building Applications using Flutter

AIM
To develop a Personal Budget Calculator that accepts income and expenses,
calculates the remaining balance and displays the financial status using a
Flutter state management technique.

FILES IN THIS FOLDER
  lib/main.dart          - complete source code of the application
  pubspec_snippet.yaml   - the relevant part of pubspec.yaml (dependencies)
  README.txt             - this file

PREREQUISITES
  - Flutter SDK installed (check with: flutter doctor)
  - An emulator, a physical device, or Chrome for web

HOW TO RUN
1. flutter create ex5_budget_calculator
   cd ex5_budget_calculator
2. Replace the generated lib/main.dart with the lib/main.dart from this folder.
3. Add the required packages:
   flutter pub add provider
4. flutter pub get
5. flutter run -d chrome   (or pick an emulator / device when asked)

STATUS
  The code was reviewed and checked for Dart syntax, but it was NOT executed
  in the environment where this record was prepared (Flutter SDK / Firebase
  were not available there). Please run it on your machine and capture your
  own screenshots.

SCREENSHOTS YOU NEED TO CAPTURE
Save them in Output_Screenshots/Ex5/ with these names:
  output_1.png  ->  Initial screen
  output_2.png  ->  Income set (e.g. 30000) and a few expenses added - green surplus
  output_3.png  ->  Expenses larger than income - red deficit
  output_4.png  ->  After deleting an expense - balance updated

After saving the screenshots, open Final_Lab_Record.docx, delete the grey
placeholder box of each figure in Experiment 5 and insert the matching
picture (Insert > Pictures), keeping the caption below it.
