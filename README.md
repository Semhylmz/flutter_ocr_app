# Flutter OCR Application
This repository contains a Flutter application that utilizes Google ML Kit for optical character recognition (OCR). The app allows users to select an image from their gallery or capture one using their camera, and then processes the image to extract and display text using OCR technology.

## Features
- Select an image from the gallery or capture a new one with the camera.
- Process the selected image to recognize and extract text.
- Display the recognized text on the screen.
- Option to process text as a list, line by line.

## How It Works
- HomePage: Users can choose to capture an image with the camera or select one from the gallery. Upon selection, the image is sent to the RecognitionPage.

- RecognitionPage: The selected image is processed using Google ML Kit's text recognition capabilities. If the image contains text, it is displayed on the screen. Users can choose to recognize text line by line if the image contains a list.

## Medium Article
For a detailed walkthrough, check out the Medium article:
👉 [Text Recognition (OCR) in Flutter](https://medium.com/@semihyilmazz/text-recognition-ocr-in-flutter-c9dbc2731ab6)

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

