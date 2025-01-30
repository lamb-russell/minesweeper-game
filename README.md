# Minesweeper Game

A classic Minesweeper game implemented in HTML, CSS, and JavaScript. This web-based version allows players to customize the board size and mine count before starting the game.

![Minesweeper Game Screenshot](https://lamb-russell.github.io/minesweeper-game/snapshot.png)

## Table of Contents

- [How to Play](#how-to-play)
- [Features](#features)
- [Controls](#controls)
- [Customization](#customization)
- [Setup](#setup)
- [Usage](#usage)
- [Contributing](#contributing)

## How to Play

💣 **Goal:** Reveal all cells that are not mines without clicking on any mine.

💡 **How to Play:**

1. Left-click: Reveals a cell.
   - If it's a number, it shows the count of adjacent mines.
   - If it's a mine, you lose!

2. Right-click (or long-press): Marks a cell as a flag (potential mine) or a question mark.

3. Reveal all non-mine cells or correctly flag all mines to win the game.

## Features

- Customizable board height and width (5-20)
- Customizable number of mines (1-max available cells)
- Win/lose alerts
- Emoji support for flags and mines

## Controls

- Left-click: Reveal a cell or adjacent empty cells.
- Right-click (or long-press): Mark/remove flag or question mark on a cell.

## Customization

Before starting the game, you can customize the board settings:

1. **Grid Height:** Sets the number of rows in the grid (5-20).
2. **Grid Width:** Sets the number of columns in the grid (5-20).
3. **Mines:** Sets the total number of mines on the board (1-max available cells).

## Setup

To run this project locally, follow these steps:

1. Clone this repository:
   ```
   git clone https://github.com/your-username/minesweeper-game.git
   ```

2. Open the `index.html` file in your preferred web browser.

## Usage

After opening the game in your browser:

1. Customize the board settings if desired.
2. Click "Apply Settings" or press Enter to start the game.
3. Left-click on cells to reveal them and right-click (or long-press) to mark/remove flags or question marks.
4. Win by revealing all non-mine cells or correctly flagging all mines.

## Contributing

Contributions are welcome! If you encounter any bugs or have suggestions for improvement, please submit an issue or pull request.

1. Fork the repository.
2. Create a new branch: `git checkout -b my-new-feature`.
3. Make changes and commit them with meaningful commit messages.
4. Push to your fork: `git push origin my-new-feature`.
5. Submit a pull request with a clear description of your changes.

Before contributing, please review the project's [Code of Conduct](CODE_OF_CONDUCT.md) and ensure you follow our guidelines for contributing to this project.

Happy mining! 💣🎉