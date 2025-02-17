# 2048 Game

A browser-based implementation of the classic **2048 puzzle game** built with JavaScript. Combine tiles to reach the magic number—**2048**—while honing your strategy and enjoying a smooth, interactive UI.

<p align="center">
  <img src="https://github.com/user-attachments/assets/b8e39547-8e94-4bee-9b85-1c31cd250c1e" alt="2048 game GIF" />
</p>

## 🎮 Gameplay

- **Goal**: Slide numbered tiles on a 4x4 grid to combine them into a tile with the value of **2048**.
- **How to Play**: Use arrow keys to move tiles. Tiles with the same value merge, creating a new tile with double the value. Keep combining tiles until you reach **2048**—or run out of moves!
- **Win/Loss**: Win by reaching 2048. The game is over when no valid moves remain.

## ✨ Features

- **Smooth Gameplay**: Intuitive controls and animations for a satisfying player experience.
- **Responsive Design**: Works well across devices and screen sizes.
- **Random Tile Generation**: After each move, a new tile (2 or 4) spawns randomly, adding challenge.
- **Scoring System**: Tracks your score with each move, encouraging higher scores.
- **Restart Option**: Reset the board at any time with a click of a button.

## 📂 Project Structure

- **`src/modules/Game.class.js`**: Core game logic and mechanics, including tile merging and move validation.
- **`src/index.html`**: Main layout and structure for the game interface.
- **`main.js`**: Connects UI elements with game logic and manages event handling.

## 🚀 Technologies

- **JavaScript**: Game logic and interactions
- **HTML & CSS**: Responsive layout and styling

## 🧩 Try it Out

You can play the game [here](https://mikezhylka.github.io/game-2048-js) or clone this repository to try it locally.

## 🖥️ How to Run Locally

Follow these steps to run the project on your machine:

- **Prerequisites**: Node.js v20.18.3 (Download) npm (comes with Node.js) Git (for cloning the repository)

- **Step 1**: Clone the Repository: git clone https://github.com/mikezhylka/game-2048-js.git

- **Step 2**: Check Node Version: Ensure you’re using Node.js v20.18.3.

- **Step 3**: Install Dependencies: npm install

- **Step 4**: Run the Development Server: npm run start

