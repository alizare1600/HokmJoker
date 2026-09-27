# HokmJoker 🎴

Hokm Joker - An Android Card Game

## Description

HokmJoker is an Android card game application built with Java and Gradle. It features an engaging UI for playing the Hokm card game.

## Features

- Android-based card game interface
- Material Design UI with custom styling
- Support for various screen sizes

## Prerequisites

- Java 17 or higher
- Gradle 8.9
- Android SDK
- Minimum API Level: Check AndroidManifest.xml

## Build Instructions

### Local Build

```bash
# Clone the repository
git clone https://github.com/alizare1600/HokmJoker.git
cd HokmJoker

# Build the debug APK
gradle :app:assembleDebug

# The APK will be generated at:
# app/build/outputs/apk/debug/app-debug.apk
```

### Using GitHub Actions

The project includes an automated build workflow that:
1. Checks out the code
2. Sets up Java 17
3. Configures Gradle 8.9
4. Builds the Android project
5. Generates and uploads the APK as an artifact

The workflow runs on every push to the `main` branch and can be triggered manually.

## Project Structure

```
HokmJoker/
├── app/
│   ├── src/
│   │   └── main/
│   │       ├── java/com/example/hokmjoker/   # Java source code
│   │       ├── res/                           # Resources (layouts, strings, colors, etc.)
│   │       └── AndroidManifest.xml
│   ├── build.gradle                           # App-level build configuration
│   └── ...
├── build.gradle                               # Project-level build configuration
├── settings.gradle                            # Gradle settings
└── .github/workflows/                         # CI/CD workflows
```

## Technologies Used

- **Language:** Java
- **Build System:** Gradle
- **Platform:** Android
- **UI Framework:** Android Framework

## License

No license specified yet. Please add a LICENSE file if needed.

## Author

- alizare1600

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Getting Started

1. Clone or download the repository
2. Open in Android Studio or your preferred IDE
3. Build the project: `gradle build`
4. Deploy to an emulator or physical device

---

For more information, visit the [GitHub repository](https://github.com/alizare1600/HokmJoker).
