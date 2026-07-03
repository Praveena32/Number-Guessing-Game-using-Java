# Number Guessing Game (Java)

A feature-rich, console-based Number Guessing Game built using Java. The application challenges players to guess a randomly generated number within a specified range while tracking their score across multiple rounds.

---

## 🚀 Features

- **Dynamic Range generation:** The computer picks a random number between a specified minimum and maximum range (Default: 1 to 100).
- **Limited Attempts:** Players must guess the correct number within a set number of tries, adding an extra layer of challenge.
- **Dynamic Scoring:** Points are awarded based on how fast you guess the number—fewer attempts mean a higher score!
- **Multi-Round Support:** Play as many rounds as you want; the game tracks your total cumulative score.
- **Robust Input Handling:** Built-in validation prevents the program from crashing if a user accidentally types a non-integer character.

---

## 🛠️ Key Concepts Used

- **`java.util.Random`**: For secure and dynamic random number generation.
- **`java.util.Scanner`**: For capturing and parsing user console inputs.
- **Nested Loops**: Implemented using `while` structures to handle continuous game rounds and sequential player attempts.
- **Conditionals & Validation**: `if-else` blocks handle player feedback ("Too high", "Too low") and `hasNextInt()` filters out bad inputs.

---

## 💻 How to Run

### Prerequisites
Make sure you have the **Java Development Kit (JDK)** installed on your machine (JDK 8 or higher is recommended).

### Running via Terminal/Command Prompt

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
   cd your-repo-name

## 📸 Gameplay Preview

![Number Guessing Game Demo](assets/gameplay-screenshot.png)
