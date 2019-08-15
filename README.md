# TV Recognizer
Brazil Tv Station Logo Recognizer

This project was originally created to be part of Beep App project. The work uses Flutter framework to process a TensorFlow Lite model (FlatBuffer format) containing a Trained Convolutional Neural Network (CNN). The model processes a live video from Smartphone Camera (Using Camera plugin 0.5.3) on FLUTTER in order to recognize Tv Station Logos.


Data:
--------
- Tflite file (TensorFlow Lite), was constructed using DARKNET / YOLO Tiny V2 and after converted to Tflite PB (Protobuf) containing the model' weights and graph definition.
- The Flutter Folders (TvLogo_Detect) consists of the Distance detection (for entire Television), and Close detection (for just logo on entire phone screen).
- The Notebook (Logo_Data_Augmentation.ipynb) consists of the program to Augment the logo images due the few images to compose the dataset and for better accuracy on detection.
- Pre-made APKs to put directly into smartphone.

Setting Up:
-----------------------------------

First you will need to install Flutter for your platform:
https://flutter.dev/docs/get-started/install

Then run `flutter doctor` and be sure that no issues are reported for the sections relevant to your platform.

In order to run this ANDROID APP on a smartphone just do `flutter run` in the TVLogo Far or TVLogo Close directory.


Install from pre-made APK:
-----------------
You can install the apk directly on Smartphone:

- APK for Far distance: 
- APK for Close distance: 





Copyright © 2019 leoitcode
