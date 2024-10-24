# Dicee Flutter Mobile App
This is a simple Dicee mobile app built using Flutter. The app lets you roll two dice at random by tapping on them, generating new random dice numbers on each tap. It’s a fun project to practice basic state management and user interaction in Flutter.

## Features
-Two dice displayed on the screen.</br>
-Tap on either dice to roll both dice, generating a random number between 1 and 6 for each.</br>
-The app uses the Random class from Dart to generate random dice rolls.</br>
-Clean and responsive UI with a red theme.

## Preview


https://github.com/user-attachments/assets/aae540e6-fd40-4e66-bfc7-94915787a41f



## Installation
To run this project locally:</br>
Clone the repository:</br>
git clone https://github.com/Atupakisyestephen/dicee-flutter-mobile-app.git

Navigate to the project directory:</br>
cd dicee-flutter-mobile-app</br>

Install dependencies:</br>
flutter pub get</br>

Run the app:</br>
flutter run

## How It Works
-The app consists of a DicePage stateful widget.</br>
-Each dice is represented by an image asset that changes dynamically based on a random number (1-6) generated using Dart's Random().nextInt(6).</br>
-When a dice is tapped, the changeDiceFace() function is called, updating the state and triggering a rebuild with new dice images.

## Code Snippet
void changeDiceFace() {</br>
  setState(() {</br>
    leftDiceNumber = Random().nextInt(6) + 1;</br>
    rightDiceNumber = Random().nextInt(6) + 1;</br>
  });</br>
}</br>

This function updates the dice numbers with a random value between 1 and 6, then calls setState to rebuild the UI with the new dice images.

## Assets
Make sure to include the dice images in your images/ directory with filenames dice1.png through dice6.png.

## Dependencies
[Flutter](https://flutter.dev/)</br>
Dart

## Contact
Atupakisye S. Elias</br>
Phone: +255 626 561 774 | +255 656 915 449</br>
LinkedIn: [Atupakisye S. Elias](https://www.linkedin.com/in/atupakisye)</br>
YouTube: [Atupakisye Elias](https://www.youtube.com/@AtupakisyeElias)</br>
Website: https://atupakisyestephen.github.io/My-Personal-Website/

## License
This project is licensed under the MIT License.





