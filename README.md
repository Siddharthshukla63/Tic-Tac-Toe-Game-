# Tic-Tac-Toe (Python)

A simple, interactive **Tic-Tac-Toe** game built using Python. This is a command-line interface (CLI) game where two players can compete against each other on a classic 3x3 grid.

## 🎮 Features
* **Two-Player Mode:** Play locally with a friend (Player X and Player O).
* **Input Validation:** Prevents players from choosing a spot that is already taken or entering invalid coordinates.
* **Win Detection:** Automatically detects horizontal, vertical, and diagonal wins.
* **Draw Detection:** Recognizes when the board is full and no player has won.

## 🛠️ How to Run
1.  **Prerequisites:** Ensure you have [Python 3.x](https://www.python.org/downloads/) installed on your system.
2.  **Download:** Save the `tic_tac_toe.py` file to your computer.
3.  **Execute:** Open your terminal or command prompt and run:
    ```bash
    python tic_tac_toe.py
    ```

## 🕹️ How to Play
1.  The game starts with an empty 3x3 grid.
2.  The grid positions are usually mapped to numbers **1-9** (or row/column indices depending on your specific version).
3.  **Player X** goes first, followed by **Player O**.
4.  Enter the number corresponding to the cell where you want to place your mark.
5.  The first player to get 3 marks in a row (up, down, across, or diagonally) wins!

## 📂 Project Structure
```text
.
├── tic_tac_toe.py   # The main Python script containing the game logic
└── README.md        # Project documentation
