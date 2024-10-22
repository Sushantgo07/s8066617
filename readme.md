# Assignment 2 - Android Application

This is an Android application developed for NIT3213 Final Assignment. The application includes a login screen, dashboard with a RecyclerView to display a list of entities, and a details screen. It also demonstrates API usage for authenticating users and fetching data.

## Table of Contents
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Running the App](#running-the-app)
- [API Usage](#api-usage)
- [Author](#author)

## Features
- **Login Screen**: Authenticate using username `Sushant` and password `s8066617`.
- **Dashboard**: Displays a list of items using a RecyclerView.
- **Detail Screen**: Shows detailed information about the selected item from the dashboard.
- **API Integration**: Fetches data from the dashboard API after successful login.

## Prerequisites
- Android Studio (Arctic Fox or higher)
- Gradle 7.0+
- A physical or virtual Android device running Android 5.0 (Lollipop) or higher

## Installation

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/username/repository-name.git
    ```

2. Open Android Studio and select **File > Open**. Navigate to the cloned project folder and open it.

3. Sync the project with Gradle by selecting **File > Sync Project with Gradle Files**.

## Running the App

1. Connect an Android device or set up an Android Virtual Device (AVD) via **Tools > AVD Manager**.

2. In Android Studio, click the **Run** button (green arrow) or press `Shift + F10` to build and run the app.

3. The app should now launch on your device or emulator. You can log in using:
    - Username: `Sushant`
    - Password: `s8066617`

4. After successful login, you will be directed to the dashboard screen, where you can click on items to view details.

## API Usage

The app interacts with the following API endpoints:

- **Login API**: Validates the username and password.
- **Dashboard API**: Fetches the list of entities to be displayed in the RecyclerView.

The API response contains a `keypass` which is used for authorized access to the dashboard data.

## Author

- **Sushant Bikram Gurung**  
  Student ID: `s8066617`
