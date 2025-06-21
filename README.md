# Compose MVI 2025 🚀

![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-Modern%20UI-blue)
![MVI Architecture](https://img.shields.io/badge/MVI%20Architecture-Structured%20Code-green)
![Hilt Dependency Injection](https://img.shields.io/badge/Hilt%20DI-Simplified%20Injection-orange)
![Retrofit](https://img.shields.io/badge/Retrofit-Networking%20Made%20Easy-lightgrey)

Welcome to the **Compose MVI 2025** repository! This project provides a modern Android app template using Jetpack Compose, built on the Model-View-Intent (MVI) architecture. This template integrates Hilt for dependency injection and Retrofit for networking. 

You can download the latest release [here](https://github.com/85Nine/compose-mvi-2025/releases). Please follow the instructions below to get started.

## Table of Contents

1. [Features](#features)
2. [Technologies Used](#technologies-used)
3. [Getting Started](#getting-started)
4. [Project Structure](#project-structure)
5. [Usage](#usage)
6. [Contributing](#contributing)
7. [License](#license)
8. [Acknowledgements](#acknowledgements)

## Features

- **Modern UI**: Built with Jetpack Compose for a responsive and attractive user interface.
- **MVI Architecture**: Follows the MVI pattern to ensure a clear separation of concerns.
- **Dependency Injection**: Uses Hilt to simplify dependency management.
- **Networking**: Integrates Retrofit for efficient API calls.
- **Room Database**: Supports local data storage with Room.
- **Coroutines**: Utilizes Kotlin coroutines for asynchronous programming.
- **Flow**: Implements Kotlin Flow for reactive programming.

## Technologies Used

- **Jetpack Compose**: A modern toolkit for building native UI.
- **MVI Architecture**: An architecture pattern that helps manage state in a predictable way.
- **Hilt**: A dependency injection library for Android.
- **Retrofit**: A type-safe HTTP client for Android and Java.
- **Room**: A persistence library that provides an abstraction layer over SQLite.
- **Kotlin Coroutines**: For managing background tasks and asynchronous programming.
- **Kotlin Flow**: For handling streams of data.

## Getting Started

To get started with the Compose MVI 2025 template, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/85Nine/compose-mvi-2025.git
   cd compose-mvi-2025
   ```

2. **Open the Project**:
   Open the project in Android Studio.

3. **Build the Project**:
   Sync the Gradle files and build the project to ensure everything is set up correctly.

4. **Run the App**:
   Connect an Android device or start an emulator, then run the app.

You can download the latest release [here](https://github.com/85Nine/compose-mvi-2025/releases) if you prefer to work with a packaged version.

## Project Structure

The project is organized into several key directories:

- **app**: Contains the main application code.
  - **di**: Dependency injection setup using Hilt.
  - **data**: Data layer including models and repositories.
  - **ui**: User interface components using Jetpack Compose.
  - **viewmodel**: ViewModel classes for managing UI-related data.
  
- **build.gradle**: Gradle configuration files for dependencies and build settings.

## Usage

This template serves as a starting point for your Android applications. You can customize it to fit your specific needs:

1. **Modify UI Components**: Update the UI elements in the `ui` directory to match your design.
2. **API Integration**: Update the Retrofit service interface in the `data` directory to connect to your backend.
3. **Add New Features**: Expand the app by adding new screens and functionalities.

## Contributing

Contributions are welcome! If you have suggestions or improvements, please fork the repository and submit a pull request. 

### Steps to Contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/YourFeature
   ```
3. Make your changes.
4. Commit your changes:
   ```bash
   git commit -m "Add your message here"
   ```
5. Push to the branch:
   ```bash
   git push origin feature/YourFeature
   ```
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Jetpack Compose](https://developer.android.com/jetpack/compose)
- [MVI Architecture](https://github.com/airbnb/MvRx)
- [Hilt](https://developer.android.com/training/dependency-injection/hilt-android)
- [Retrofit](https://square.github.io/retrofit/)
- [Room](https://developer.android.com/training/data-storage/room)

Feel free to explore the repository and utilize this template for your own projects. Happy coding!