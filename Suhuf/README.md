# SUHUF

**SUHUF** is a React Native application designed to connect people for communal prayers. Whether you're at home, traveling, or in a new city, SUHUF helps you find and join prayer groups nearby or virtually. The app fosters a sense of community by making it easy to organize and participate in group prayers.

## Features

- **Find Prayer Groups**: Locate nearby prayer groups or create your own.
- **Join Virtual Prayers**: Connect with others for virtual prayer sessions.
- **Prayer Reminders**: Get notified about prayer times and upcoming group prayers.
- **Community Building**: Chat and connect with other users to build a stronger community.
- **Easy Navigation**: Intuitive UI for seamless navigation and user experience.

## Installation

To get started with SUHUF, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/SUHUF.git
   cd SUHUF
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Set Up Environment Variables**:
   Create a `.env` file in the root directory and add your environment variables:
   ```env
   API_KEY=your_api_key_here
   ```

4. **Run the App**:
   - For iOS:
     ```bash
     npx react-native run-ios
     ```
   - For Android:
     ```bash
     npx react-native run-android
     ```

## Usage

1. **Sign Up/Log In**: Create an account or log in to access the features.
2. **Find Prayer Groups**: Use the map or list view to find nearby prayer groups.
3. **Join a Group**: Tap on a group to view details and join.
4. **Create a Group**: Organize a new prayer group and invite others to join.
5. **Set Reminders**: Enable prayer time reminders in the settings.

## Technologies Used

- **React Native**: For building the cross-platform mobile application.
- **Expo**: For development and deployment tools.
- **Firebase**: For authentication, real-time database, and notifications.
- **React Navigation**: For navigation between screens.
- **Redux**: For state management.

## Contributing

We welcome contributions from the community! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes.
4. Push your branch and submit a pull request.

Please ensure your code follows our coding standards and includes appropriate tests.

## License

SUHUF is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or suggestions, please reach out to us at [support@suhuf.com](mailto:support@suhuf.com).

---

Thank you for using SUHUF! We hope this app helps you stay connected with your community and enhances your prayer experience.

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
    npx expo start
   ```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.
