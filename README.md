# Guessing Game – Python Project (Task 2)

A fun command-line game where the computer randomly selects a number between **1 and 100**, and the user must guess it.  
The program gives feedback for each guess: **Too high**, **Too low**, or **Correct!**

---

## 📌 Project Details
**Project Name:** Guessing Game  
**Task No.:** Task 2  
**Author:** Kunal  

---

## 📁 Files Included
- `app.py` — Main Python program containing the game logic. :contentReference[oaicite:1]{index=1}
- `README.md` — Documentation for Task 2.

---

## 🎮 How the Game Works
- Program randomly picks a number between **1 to 100**.
- User enters guesses.
- Program tells:
  - **Too low!**
  - **Too high!**
  - **Correct!**
- After correct guess, it shows the **number of attempts** taken.

---

## 🚀 How to Run the Project

1. Terminal / PowerShell open karo.
2. Project folder me jao:





Program run
python app.py
(OR)
python3 app.py


🧪 Sample Gameplay OutputWelcome to the Guessing Game!

I'm thinking of a number between 1 and 100. Try to guess it!

Enter your guess: 28
Too low! Try again.

Enter your guess: 50
Too low! Try again.

Enter your guess: 90
Too high! Try again.

Enter your guess: 89
Congratulations! You guessed it in 13 attempts.



🔧 Program Logic (Short Overview)
Uses:
secret_number = random.randint(1, 100)

Loop runs until correct guess.

Attempts counter increments each time.

Handles invalid input using:

except ValueError:
    print("Please enter a valid integer.")


Full code is inside app.py.


💡 Possible Improvements

Add difficulty levels (Easy / Medium / Hard)

Add score tracking

Add GUI using Tkinter

Add sound effects or animations (optional)






   ```bash
   cd Task\ 2
