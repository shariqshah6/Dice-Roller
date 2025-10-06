# 🎲 Python Dice Roller

A simple **Dice Roller** made in Python that simulates rolling a dice.  
Each time you run it, the program randomly generates a number between **1 and 6**, just like a real dice!

---

## 🚀 Features
- 🎯 Generates a random number from **1 to 6**
- 🔁 Option to roll again or exit
- 🧠 Simple and beginner-friendly code
- 📦 Uses Python’s built-in `random` module

---

## 🧰 Technologies Used
- **Python 3**

---

## 🧑‍💻 How It Works
1. The program uses the `random.randint(1, 6)` function to simulate a dice roll.  
2. It displays the random number between **1 and 6**.  
3. The user can choose to **roll again** or **exit** the program.

---

## 🧩 Code Example
```python
import random

while True:
    print("🎲 Dice rolled:", random.randint(1, 6))
    again = input("Roll again? (y/n): ")
    if again.lower() != 'y':
        break
