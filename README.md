# Favourite Places

This app makes it easy to collect your favorite places on your device in the form of: description,
photo and location.

Application built on the basis of the course "Flutter and Dart - The Complite Guide 2023 " by
Maximilian Schwarzmüller.

## Application Details:

- Architecture: [FLutter SDK](https://docs.flutter.dev/)
- API: [GoogleMaps](https://mapsplatform.google.com/)
- Platform: Android, iOS

## Features

- Take a picture of your favorite place
- Mark the location of the place on the map or set the user's current location.
- Present favorite places on the list

## How to Run

1. Create an account at [GoogleMaps](https://mapsplatform.google.com/).
3. Then get your API keys
4. Clone the repo
   ```sh
   git clone https://github.com/krisdev88/FavoritePlacesApp.git
   ```
5. Install all the packages by typing
   ```sh
   flutter pub get
   ```
6. Create an .env file in the root folder of the project

7. Navigate to **lib/.env** and paste your API keys to the relevant variables
   ```
   GOOGLE_MAPS_API_KEY=Paste Your GoogleMapsApiKey Here
   ```
8. Run the app using flutter run

## License

Distributed under the MIT License.	
