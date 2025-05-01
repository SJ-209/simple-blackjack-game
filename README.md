# Blackjack Game (Scrimba Course Project - Web App)

**A simple web-based Blackjack game built as part of the Scrimba JavaScript course, demonstrating fundamental JavaScript concepts within a browser environment.**

## Table of Contents

* [About the Project](#about-the-project)
* [Getting Started](#getting-started)
* [Usage](#usage)
* [Learned Concepts](#learned-concepts)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)

## About the Project

This project is a basic implementation of the classic card game Blackjack, designed to be played directly in a web browser. It was created as a learning exercise during a JavaScript course on Scrimba to solidify understanding of core programming concepts within a web development context. The game allows a single player to play against a virtual dealer, with a simple graphical interface.

## Getting Started

To play this game, you only need a modern web browser.

1.  Clone the repository (if you've hosted it on GitHub):
    ```bash
    git clone [https://github.com/](https://github.com/)[Your Username]/blackjack-web-scrimba.git
    ```
2.  Navigate to the project directory:
    ```bash
    cd blackjack-web-scrimba
    ```
3.  Open the `index.html` file in your web browser.

    **Note:** If you followed the Scrimba course directly in their environment, you might not have a separate file. In that case, this README serves as documentation of the concepts learned. If you've exported your Scrimba project, locate the main `index.html` file.

### Optional Setup (If you have a local development server):

If you have a local development server set up (e.g., using `npm live-server`), you can also run the project from your server's root directory and access it via `localhost:[port]`.

## Usage

Once you open `index.html` in your browser, you should see the Blackjack game interface. The game will have buttons for actions like "Start Game," and "New Cards." Use these buttons to interact with the game and play against the dealer. The goal is to get a hand value as close to 21 as possible without exceeding it.

## Learned Concepts

This project heavily utilized the following fundamental JavaScript language components to create the interactive web application:

* **Arrays:** Used to represent the players' hands.
* **Objects:** Used to represent individual player details.
* **Booleans:** Used to track game states (e.g., `isAlive`, `hasBlackjack`, `gameOver`).
* **If/Else Statements:** Implemented game logic for determining actions based on card values, game states, and user input (button clicks).
* **Comparison Operators:** Used to compare card values and determine winners.
* **Logical Operators:** Combined conditions for more complex game rules (e.g., checking for Blackjack and bust conditions).
* **For Loops:** Used to iterate through the players' hands for calculations and rendering.
* **Math Object:** Utilized for generating random numbers to simulate card dealing.
* **Return Statements:** Used within functions to provide results and control program flow in response to game events.

## Contributing

As this was primarily a learning project following a specific course, major contributions might not be the focus. However, if you find any bugs or have minor improvements, feel free to fork the repository and submit a pull request.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/ImproveUI`)
3.  Commit your Changes (`git commit -m 'Improve user interface or game flow'`)
4.  Push to the Branch (`git push origin feature/ImproveUI`)
5.  Open a Pull Request

## License

Distributed under the [MIT](LICENSE) License. See `LICENSE` for more information. (Consider creating a `LICENSE` file in your repository with the MIT license text).