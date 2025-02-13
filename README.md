# MySplash

MySplash is an Android application that features a splash screen with a network connectivity check. If the device is connected to the internet, it transitions to the main activity after a short delay. Otherwise, it displays a Snackbar message prompting the user to retry.

## Features

- Displays a splash screen for 3 seconds
- Checks internet connectivity using `ConnectivityManager`
- If connected, transitions to `HomeActivity`
- If no internet, shows a Snackbar with a retry option

## Installation

1. Clone this repository:
   ```sh
   git clone https://github.com/your-username/mySplash.git
   ```
2. Open the project in **Android Studio**.
3. Build and run the app on an emulator or a physical device.

## Usage

- Launch the app.
- If there is an active internet connection, it will move to `HomeActivity` after 3 seconds.
- If there is no internet, a Snackbar appears with a "Retry" button to recheck connectivity.

## Project Structure

```
mySplash/
│-- app/
│   │-- src/
│   │   │-- main/
│   │   │   │-- AndroidManifest.xml
│   │   │   │-- java/com/example/mysplash/
│   │   │   │   │-- SplashActivity.java
│   │   │   │   │-- HomeActivity.java
│   │-- build.gradle
│-- settings.gradle
│-- gradle.properties
```

## Dependencies

This project uses:

- `androidx.appcompat:appcompat`
- `com.google.android.material:material`

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author

Developed by **Abdilahi1**.

