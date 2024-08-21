# Pokémon Moves and Games Tracker

## Overview

**Pokémon Moves and Games Tracker** is an iOS application designed to help users track details about Pokémon, their moves, and associated games. The application leverages SwiftUI for a seamless user experience, offering detailed views and interactions related to Pokémon data.

## Features

- **Detailed Pokémon Information**: View detailed information about various Pokémon species, including stats, abilities, and evolution paths.
- **Move Details**: Explore the specifics of each Pokémon move, such as power, type, and accuracy.
- **Games Information**: Access comprehensive data about the Pokémon games, including version exclusives and key features.
- **SwiftUI Interface**: A modern, responsive user interface built entirely with SwiftUI, ensuring a smooth and intuitive user experience.
- **Modular Architecture**: The app’s structure is modular, allowing easy addition of new features and data sets.

## Project Structure

- **ContentView.swift**: The main entry point for the user interface, where the primary navigation and content display logic is managed.
- **PokemonDetails.swift**: Handles the display of detailed information for individual Pokémon, including their stats, abilities, and other related data.
- **MovesDetails.swift**: Manages the display of detailed information about Pokémon moves, such as their type, power, and additional effects.
- **MoveView.swift**: A view component focused on displaying a list of Pokémon moves and their key attributes.
- **GamesDetails.swift**: Provides detailed information on different Pokémon games, covering aspects like version-specific Pokémon and gameplay features.

## Requirements

- **Xcode 14.0+**: Ensure you have the latest version of Xcode installed.
- **iOS 16.0+**: The application is designed to run on iOS 16 and later.
- **Swift 5.0+**: Built using the latest features of Swift 5.

## Installation

To set up the project locally, follow these steps:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Goutcho/PokemonMovesAndGamesTracker.git
   cd PokemonMovesAndGamesTracker
   ```

2. **Open in Xcode:**

   Double-click the `PokemonMovesAndGamesTracker.xcodeproj` file to open the project in Xcode.

3. **Build and Run:**

   Select your target device or simulator, then build and run the project by pressing `Cmd + R`.

## Usage

1. **Explore Pokémon Details:** Start the app and browse through the Pokémon list to view detailed information on each species.
2. **View Moves:** Navigate to the moves section to see detailed descriptions of all Pokémon moves.
3. **Game Details:** Access the games section to learn more about various Pokémon games and their unique features.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new feature branch: `git checkout -b feature/your-feature-name`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/your-feature-name`.
5. Open a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- **PokéAPI**: For providing a comprehensive API with data on Pokémon, moves, and games.
- **SwiftUI**: For the robust framework that powers the user interface of the application.
- **Apple Developer Documentation**: For extensive resources and documentation on SwiftUI and iOS development.
