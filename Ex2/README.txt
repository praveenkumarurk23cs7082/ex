EXPERIMENT 2: Adaptive and Responsive UI Design
Register Number: URK23CS7082
Course: 24CS2016 - Building Applications using Flutter

AIM
To design and implement a responsive Flutter application for an E-Commerce
Product Catalog that uses reusable product widgets and adapts its layout to
different screen sizes.

FILES IN THIS FOLDER
  lib/main.dart          - complete source code of the application
  pubspec_snippet.yaml   - the relevant part of pubspec.yaml (dependencies)
  README.txt             - this file

PREREQUISITES
  - Flutter SDK installed (check with: flutter doctor)
  - An emulator, a physical device, or Chrome for web

IMPORTANT
Run on Chrome (flutter run -d chrome) and resize the browser window to capture
the three layouts, or use phone, tablet and desktop emulators.

HOW TO RUN
1. flutter create ex2_responsive_catalog
   cd ex2_responsive_catalog
2. Replace the generated lib/main.dart with the lib/main.dart from this folder.
3. flutter pub get
4. flutter run -d chrome   (or pick an emulator / device when asked)

STATUS
  The code was reviewed and checked for Dart syntax, but it was NOT executed
  in the environment where this record was prepared (Flutter SDK / Firebase
  were not available there). Please run it on your machine and capture your
  own screenshots.

SCREENSHOTS YOU NEED TO CAPTURE
Save them in Output_Screenshots/Ex2/ with these names:
  output_1.png  ->  Mobile layout - narrow window or phone emulator (2 columns)
  output_2.png  ->  Tablet layout - window about 700-999 px wide (3 columns)
  output_3.png  ->  Desktop layout - window 1000 px or wider (4 columns)

After saving the screenshots, open Final_Lab_Record.docx, delete the grey
placeholder box of each figure in Experiment 2 and insert the matching
picture (Insert > Pictures), keeping the caption below it.
