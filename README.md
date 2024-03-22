# MusicAppUi

## Description:
MusicAppUi is a modern Android application project aimed at providing a visually appealing and user-friendly interface for a music app. It incorporates various UI components and functionalities commonly found in music applications, offering users a seamless and enjoyable experience while browsing and managing their music library.

## Features:

1. **Bottom Navigation:** The application features a bottom navigation bar for easy navigation between different sections of the app, providing quick access to key features such as home, library, and browsing.
2. **Drawer Navigation:** Users can access additional functionalities and settings through the drawer navigation menu, including account management, subscription details, and other options.
3. **Library:** The library section allows users to explore their music collection, including playlists, artists, albums, songs, and genres. Users can browse, search, and manage their music library effortlessly.
4. **Subscription Management:** Users can manage their subscription plans, view subscription details, and explore different subscription options available within the app.
5. **Account Management:** The application provides features for managing user accounts, including adding new accounts, viewing account information, and updating account settings.
6. **Home:** In the home section, users can discover new music, explore curated playlists, and find music based on different moods, genres, or activities. The section offers a personalized music discovery experience.
7. **Browse:** Users can browse through various music categories such as hits, happy, workout, running, TGIF, and yoga in a visually appealing grid layout, making it easy to discover and explore new music.

## Screenshots

<!-- Include screenshots or GIFs of your app here to give users a visual representation of what your app looks like. -->
<img src="https://github.com/nishkarsh25/MusicAppUi/blob/main/Screenshots/ss1.png" alt="Screenshot 1" width="300"> &nbsp; &nbsp; <img src="https://github.com/nishkarsh25/MusicAppUi/blob/main/Screenshots/ss2.png" alt="Screenshot 2" width="300">

<img src="https://github.com/nishkarsh25/MusicAppUi/blob/main/Screenshots/ss3.png" alt="Screenshot 1" width="300"> &nbsp; &nbsp; <img src="https://github.com/nishkarsh25/MusicAppUi/blob/main/Screenshots/ss4.png" alt="Screenshot 2" width="300">

<img src="https://github.com/nishkarsh25/MusicAppUi/blob/main/Screenshots/ss5.png" alt="Screenshot 1" width="300"> &nbsp; &nbsp; <img src="https://github.com/nishkarsh25/MusicAppUi/blob/main/Screenshots/ss6.png" alt="Screenshot 2" width="300">

<img src="https://github.com/nishkarsh25/MusicAppUi/blob/main/Screenshots/ss7.png" alt="Screenshot 1" width="300"> &nbsp; &nbsp; <img src="https://github.com/nishkarsh25/MusicAppUi/blob/main/Screenshots/ss8.png" alt="Screenshot 2" width="300">


# GIF's
<img src="https://github.com/nishkarsh25/MusicAppUi/blob/main/Screenshots/ss9.gif" alt="Screenshot 4" width="300">

## Technologies Used:

- **Kotlin:** The primary programming language used for developing the Android application, known for its concise syntax and powerful features.
- **Jetpack Compose:** Leveraged for building the modern and declarative UI components of the application, enabling faster UI development and improved performance.
- **ViewModel:** Utilized to manage UI-related data in a lifecycle-conscious way, separating the UI from the underlying data and business logic.
- **Navigation Component:** Implemented for managing navigation within the application, including deep linking and passing data between destinations, ensuring a smooth and intuitive navigation experience.

## Project Structure:

- **MainActivity.kt:** The entry point of the application containing the main setup for composing the UI and initializing necessary components.
- **MainViewModel.kt:** ViewModel responsible for managing the state and business logic of the main screen, handling data updates and user interactions.
- **Screen.kt:** Defines the various screens and navigation routes used in the application, including bottom screen and drawer screen destinations.
- **Subscription.kt, Library.kt, Homeview.kt, Browser.kt, AccountView.kt:** Composable functions representing different screens and UI components within the application, each serving a specific purpose and functionality.
- **AccountDialog.kt:** Composable function for displaying a dialog to add a new account, providing a user-friendly interface for account management operations.
- **UI Theme Files:** Contains composable functions for styling and theming various UI elements, ensuring a consistent and visually appealing user interface across the application.

## Installation

To run the MusicAppUi project locally, follow these steps:

### Prerequisites

- Android Studio installed on your machine.
- An Android emulator or a physical Android device for testing.

### Clone the Repository

1. Clone this repository to your local machine using the following command:

```bash
git clone https://github.com/nishkarsh25/MusicAppUi.git
```

## Open in Android Studio

1. Open Android Studio.
2. Click on "Open an existing Android Studio project."
3. Navigate to the directory where you cloned the repository and select the "MyWishlistApp" folder.
4. Click "OK" to open the project.

## Build and Run

1. Connect your Android device to your computer, or start an Android emulator.
2. Click on the "Run" button in Android Studio or use the shortcut Shift + F10 to build and run the project.
3. Select your device from the list of available devices and click "OK."

## Usage

1. Upon launching the app, you'll be presented with the wishlist screen.
2. To add a new item to the wishlist, click on the floating action button (FAB) at the bottom right corner.
3. Fill in the details for the new item and click the "Add" button.
4. To update an existing item, click on the item in the wishlist.
5. Make the necessary changes and click the "Save" button.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. **Fork the Repository**.
2. **Create a New Branch** (`git checkout -b feature/your-feature-name`).
3. **Make Your Changes**.
4. **Commit Your Changes** (`git commit -am 'Add some feature'`).
5. **Push to the Branch** (`git push origin feature/your-feature-name`).
6. **Create a New Pull Request**.

## License

This project is licensed under the [The 3-Clause BSD License](LICENSE).

## Author

- **Nishkarsh Gupta**
  - GitHub: [nishkarsh25](https://github.com/nishkash25)
  - Email: bm21btech11016@gmail.com
