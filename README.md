# NewOne Android Application

This is an Android application that integrates with DJI drones using the DJI SDK. The app is designed to manage media files from the drone's camera and provides a user-friendly interface for drone operations.

## Features

- **DJI SDK Integration**: Connects to DJI drones and manages media files.
- **Media Management**: Refreshes and displays media files stored on the drone's SD card.
- **User Interface**: Simple and intuitive UI for easy navigation and operation.

## Requirements

- **Android Studio**: Latest version recommended.
- **Android Device**: Samsung A20 or similar, supporting `armeabi-v7a` and `arm64-v8a`.
- **DJI Drone**: Compatible with DJI SDK version 4.16.

## Setup Instructions

1. **Clone the Repository**:
bash git clone https://github.com/yourusername/newone.git

2. **Open in Android Studio**:
   - Open Android Studio and select "Open an existing Android Studio project."
   - Navigate to the cloned repository and open it.

3. **Configure SDK and Dependencies**:
   - Ensure you have the DJI SDK and other dependencies configured in your `build.gradle.kts` file.

4. **Build and Run**:
   - Connect your Android device.
   - Click on the "Run" button in Android Studio to build and deploy the app to your device.

## Build Configuration

- **Compile SDK Version**: 34
- **Minimum SDK Version**: 28
- **Target SDK Version**: 34
- **NDK ABI Filters**: `armeabi-v7a`, `arm64-v8a`

## Dependencies

- **DJI SDK**: Version 4.16
- **Kotlin Standard Library**: Version 1.9.10
- **AndroidX Libraries**: Core, AppCompat, ConstraintLayout, etc.
- **Glide**: For image handling
- **Lifecycle Runtime KTX**: For lifecycle management

## Permissions

Ensure the following permissions are declared in your `AndroidManifest.xml`:

- `INTERNET`
- `ACCESS_NETWORK_STATE`
- `ACCESS_WIFI_STATE`
- `WRITE_EXTERNAL_STORAGE`
- `READ_EXTERNAL_STORAGE`
- `ACCESS_FINE_LOCATION`
- `ACCESS_COARSE_LOCATION`

## Troubleshooting

- **Crashes on Startup**: Ensure all native libraries are correctly included and that the DJI SDK is initialized properly.
- **Connection Issues**: Verify that all necessary permissions are granted and that the device is connected to the internet.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
