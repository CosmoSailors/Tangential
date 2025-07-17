# Tangential (Experimental)

A Location-based event triggering Android application, that enables users to schedule tasks and triggers based on their real-time location. 
The app will utilize **Android Foreground Services** to periodically check the user's location and execute predefined actions accordingly.  

## How It Works

Tangential notifies you, rings an alarm, or automatically toggles **Do Not Disturb (DND) mode** when you reach a predefined location. Never worry about missing an important place or forgetting to turn DND on/off when entering or exiting locations like libraries, offices, or quiet zones!  

### Features

Add, toggle, and remove locations for triggering following events

- 📍 **Location-Based Alarms** - Get notified when you arrive at your destination.
- 🎛️ **Do Not Disturb (DND) Mode** - Enable/disable DND for specific locations.

## Developer setup

- Clone the repository:
   ```sh
   git clone https://github.com/CosmoSailors/Tangential.git
- Open the project in Android Studio.
- Build and run on an emulator or device.


## Made with

- Kotlin & Jetpack Compose
- [Google Maps SDK for Android](https://developers.google.com/maps/documentation/android-sdk)

## Usage

- Open the app and grant location permissions.
- Add a location manually or use "Add Current Location."
- The app will notify you when you reach the selected place.
- Dismiss alarms using the "Dismiss" button.

### Screenshots

<img src="./screenshots/permReqdScreen.png" alt="Description" width="250" height="530"> <img src="./screenshots/permissionScreen.png" alt="Description" width="250" height="530">
<img src="./screenshots/radiusLocationSelection.png" alt="Description" width="250" height="530"> <img src="./screenshots/multipleLocationList.png" alt="Description" width="250" height="530">
<img src="./screenshots/locationWithDropDownInfo.png" alt="Description" width="250" height="530"> <img src="./screenshots/showAllLocations.png" alt="Description" width="250" height="530">

## License

This project is licensed under the MIT License.
