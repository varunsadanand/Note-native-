# Note-native- 

## Introduction

Note-native- is a mobile application developed using React Native. The project enables users to create, view, and manage personal notes. The application leverages React Navigation for seamless navigation across different screens and utilizes AsyncStorage for persistent storage of notes on the device.

## Features

- Create new notes with a title and content.
- View a list of all saved notes.
- Edit and update existing notes.
- Delete notes from the storage.
- Responsive and intuitive user interface.
- Persistent on-device storage using AsyncStorage.
- Navigation between screens using React Navigation.

## Requirements

- Node.js (version 12 or higher)
- npm or yarn package manager
- React Native environment setup (React Native CLI)
- Android Studio or Xcode for running on emulator or device

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/varunsadanand/Note-native-.git
   cd Note-native-
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Install required pods for iOS (if building for iOS):
   ```bash
   cd ios && pod install && cd ..
   ```

4. Start the Metro bundler:
   ```bash
   npm start
   # or
   yarn start
   ```

5. Run the application:

   - For Android:
     ```bash
     npm run android
     # or
     yarn android
     ```

   - For iOS:
     ```bash
     npm run ios
     # or
     yarn ios
     ```

## Usage

- Launch the application on your device or emulator.
- On the home screen, view a list of all your notes.
- Tap the "+" button to add a new note.
- Enter the note title and content, then save.
- Tap on any note to view its full content.
- Edit or delete notes as required.

## Configuration

- The application uses AsyncStorage for storing notes. No server or backend setup is required.
- Navigation is configured using React Navigation with a stack navigator.
- All configuration related to navigation and storage is handled in the respective files under the project structure.
- To adjust the UI or theme, modify the styles in the corresponding React Native components.

## License

This project is licensed under the MIT License.

## Contributing

- Fork the repository.
- Create a new branch for your feature or fix.
- Commit your changes and push the branch to your forked repo.
- Open a pull request with a clear description of your changes.

Contributions, issues, and feature requests are welcome!
