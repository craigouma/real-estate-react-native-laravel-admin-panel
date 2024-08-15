# React Native Real Estate App

This is a React Native app for real estate, integrated with a Laravel admin panel and .NET backend.

## Installation

Follow these steps to install and set up the app:

1. Clone the repository to your local machine.
2. Open a terminal and navigate to the project directory.
3. Install the required dependencies by running the following command:

```bash
npm install
```

4. Install the React Native CLI by running the following command:

```bash
npm install -g react-native-cli
```

5. Install the Laravel dependencies by navigating to the `admin-panel` directory and running the following command:

```bash
composer install
```

6. Set up the Laravel environment by creating a `.env` file and configuring the necessary database settings.

7. Migrate the database by running the following command:

```bash
php artisan migrate
```

8. Start the Laravel development server by running the following command:

```bash
php artisan serve
```

9. Open another terminal and navigate to the project directory.
10. Start the React Native development server by running the following command:

```bash
react-native start
```

11. In a separate terminal, build and run the app on a connected device or emulator by running the following command:

```bash
react-native run-android
```

or

```bash
react-native run-ios
```

12. The app should now be running on your device or emulator.
