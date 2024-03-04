# Connect Four

## Overview
Connect Four is a classic board game where players aim to align four game pieces in a row horizontally, vertically, or diagonally before their opponent does. This project implements the Connect Four game using .NET Blazor, a modern web framework for building interactive web applications with C#.

## Features
- **Interactive Gameplay:** Experience the thrill of Connect Four with interactive gameplay, allowing players to place game pieces and compete against each other in real-time.
- **Winning Conditions:** Implement logic to detect winning combinations of game pieces and declare a winner when four pieces align.
- **User Interface:** Build a user-friendly interface using Blazor components to visualize the game board, player turns, and game status.
- **State Management:** Manage game state separately from the UI to facilitate easy modification and code readability, following best practices in game development.

## How to Play
1. **Start Game:** Begin with a clean game board with no game pieces.
2. **Player Turn:** Each player takes turns placing their game pieces on the board.
3. **Check for Winner:** After each turn, check for winning combinations horizontally, vertically, and diagonally.
   - If a player aligns four pieces, declare them the winner and end the game.
   - If no winner is found, continue gameplay until a winner is declared or the game board is full.
4. **Restart Game:** Optionally, provide a way for players to reset the game and start over.

## Implementation Details
- **State Management:** Utilize a separate C# class to manage game state, including the positions of game pieces and logic for checking winning conditions.
- **Blazor Components:** Create custom Blazor components to represent the game board, game pieces, and player turns, ensuring a responsive and interactive user interface.
- **Game Loop:** Implement a game loop to handle player turns, check for winners, and update the UI accordingly.

## Contributing
Contributions to the Connect Four project are welcome! If you have ideas for new features, improvements, or bug fixes, feel free to fork the repository, make your changes, and submit a pull request. Your contributions will help enhance the project and benefit the Blazor community.
