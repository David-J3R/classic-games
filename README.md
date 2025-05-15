# Classic Games Collection

A collection of classic games implemented primarily using HTML, CSS, and JavaScript, with significant contributions from AI.

## Project Objective

This project serves as an exploration and test of the capabilities of the AI model **Gemini 1.5 Pro Preview** & **Claude 3.7 Sonnet**. The primary goal was to have the AI develop these classic games with minimal manual intervention, to assess its coding proficiency and problem-solving skills in a practical web development context.

The Minesweeper game, in particular, offers a point of comparison against a version I previously developed in a programming class.

## Games Implemented

*   **Minesweeper**: The classic logic puzzle game. Click to reveal cells, avoid the mines, and clear the board!
*   **Snake**: Control a growing snake to eat food. Don't hit the walls or yourself!
*   **Solitaire**: The timeless single-player card game. Arrange cards in descending order and alternating colors.

## Project Structure

*   `README.md`: This file contains information about the project.
*   `index.html`: The main home page for the game collection, allowing navigation to each game.
*   `minesweeper/`:
    *   `index.html`: Contains the HTML, CSS, and JavaScript for the Minesweeper game.
*   `snake/`:
    *   `index.html`: Contains the HTML, CSS, and JavaScript for the Snake game.
*   `solitaire/`:
    *   `index.html`: Contains the HTML, CSS, and JavaScript for the Solitaire game.

*(Note: The initial plan included a `shared/` directory for common assets, but each game was developed as a self-contained `index.html` file for simplicity in this AI-driven development process.)*

## How to Play

1.  Open the main `index.html` file in your web browser.
2.  Click on the "Play" button for the game you wish to play from the home page.
3.  Each game page (`minesweeper/index.html`, `snake/index.html`, `solitaire/index.html`) includes its own rules and controls. Generally:
    *   **Minesweeper**: Left-click to reveal a cell, right-click to flag a mine.
    *   **Snake**: Use arrow keys to direct the snake.
    *   **Solitaire**: Click to interact with cards and piles (e.g., draw from stock, move cards between tableau, foundations, and waste).

## Development Notes

*   The code for each game is largely AI-generated (by Gemini 1.5 Pro Preview & Claude 3.7 Sonnet).
*   The development process was iterative, with prompts given to the AI to build features, add styling, and debug issues.
*   Each game is self-contained within its respective `index.html` file, including HTML structure, CSS styles, and JavaScript logic. This was a deliberate choice to simplify the AI's task of managing and modifying individual games.
*   The project was completed on May 14, 2025.
