Markdown
# Python Number Guessing Game

A clean, interactive, command-line game built using Python. This project demonstrates fundamental programming concepts such as conditional logic, nested tracking, case-insensitive string manipulation, and loop control structures.

## 🚀 Overview
The program generates a random target integer between 1 and 10. The user is granted **3 lives** to correctly guess the number. 

* **Win Condition:** If the user guesses correctly, the current round terminates, and the user is prompted to either start a new game or exit.
* **Loss Condition:** Each incorrect guess decrements the user's remaining lives. If lives reach 0, the game displays the correct answer and offers a replay option.

## 🛠️ Key Technical Features
* **State Management:** Utilizes a structured `while True` main loop combined with localized game-state variables to ensure a seamless replay experience without variable bleeding or infinite looping.
* **Data Type Handling:** Safely converts standard string inputs from Python's `input()` function into integers for accurate evaluation.
* **Case Insensitivity:** Employs the `.lower()` string method on user text prompts to accept dynamic string responses (`Yes`, `yes`, `YES`) smoothly.
* **Clean Code Architecture:** Avoids overly complex recursion or deep loop nesting, maximizing readability and maintainability.

## 📦 How to Run the Project

1. Ensure you have **Python 3.x** installed on your machine.
2. Clone or download this repository.
3. Open your terminal/command prompt, navigate to the project directory, and execute:
```bash
   python guessing_game.py
