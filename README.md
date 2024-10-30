
# Favorite Random Words

This is a Flutter application that generates random word pairs and allows users to save their favorites. The app uses the `english_words` package for random word pair generation and the `provider` package for state management.

## Features

- **Random Word Pair Generation:** Generate random word pairs using the `english_words` package.
- **Favorites Management:** Users can mark word pairs as favorites and view their list of saved pairs.
- **NavigationRail Layout:** A responsive design using `NavigationRail` for seamless navigation between the Home and Favorites screens.
- **Material 3 Theme:** Customized theme with Material 3 and a dynamic color scheme based on a seed color.

## Getting Started

1. **Clone the repository**:
   ```bash
   git clone <repository_url>
   cd <repository_folder>
   ```

2. **Install dependencies**:
   ```bash
   flutter pub get
   ```

3. **Run the app**:
   ```bash
   flutter run
   ```

## Code Structure

- **main.dart**: The main entry point of the app, setting up the app’s theme and initial `ChangeNotifierProvider`.
- **MyAppState**: A `ChangeNotifier` class that manages the app state, including the current word pair and the list of favorite pairs.
- **MyHomePage**: Manages navigation between two pages: `GeneratorPage` and `FavoritesPage`.
- **GeneratorPage**: Displays the current random word pair and allows the user to generate new pairs or add the current one to favorites.
- **FavoritesPage**: Displays the list of saved favorite word pairs.

## Dependencies

- [Flutter](https://flutter.dev/)
- [Provider](https://pub.dev/packages/provider)
- [english_words](https://pub.dev/packages/english_words)

## License

This project is open-source under the [MIT License](LICENSE).