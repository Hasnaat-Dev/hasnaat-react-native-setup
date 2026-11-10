# hasnaat-react-native-setup

## Project Information

| Field       | Details                                    |
|-------------|--------------------------------------------|
| **Project** | hasnaat-react-native-setup                 |
| **Name**    | Hasnaat                                    |
| **Course**  | Mobile Application Development (UMT)       |
| **Version** | 0.0.1 (React Native 0.88.1)               |

## Description

A React Native mobile application set up as part of the Mobile Application Development course at UMT. This project demonstrates the initial setup and configuration of a React Native development environment on Windows with Android Emulator, using the official React Native Community CLI.

## Prerequisites

- Node.js >= 18
- JDK 17
- Android Studio with Android SDK
- `ANDROID_HOME` environment variable set
- An Android Virtual Device (AVD) created in Android Studio

## Commands Used

### Create the Project
```bash
npx @react-native-community/cli@latest init HasnaatReactNativeSetup --directory hasnaat-react-native-setup
```

### Navigate into the Project
```bash
cd hasnaat-react-native-setup
```

### Start Metro Bundler (in a separate terminal)
```bash
npx react-native start
```

### Run on Android Emulator
```bash
npx react-native run-android
```

## Project Structure

```
hasnaat-react-native-setup/
├── android/              # Android native project
├── ios/                  # iOS native project
├── __tests__/            # Test files
├── App.tsx               # Main application component
├── index.js              # Entry point
├── package.json          # Dependencies and scripts
├── tsconfig.json         # TypeScript configuration
├── metro.config.js       # Metro bundler config
├── babel.config.js       # Babel configuration
├── README.md             # This file
├── emulator-proof.png    # (Add screenshot here)
└── structure-proof.png   # (Add screenshot here)
```

## Screenshots

> Place the following screenshots in the project root after running the app:
> - `emulator-proof.png` — Screenshot of the app running on Android Emulator
> - `structure-proof.png` — Screenshot of the project folder structure
