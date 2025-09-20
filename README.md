# Rock, Paper, Scissors – Python (Jupyter Notebook)

A simple implementation of the classic **Rock, Paper, Scissors** game. Play against the computer until one side reaches **3 points**.

---

## 📌 Overview

* Two players: **You vs. Computer**.
* Each round both choose: `Rock`, `Paper`, or `Scissors`.
* Scoring: Winner of the round gets **1 point**.
* Match ends when a player reaches **3 points**.

> Rules: Rock beats Scissors • Scissors beats Paper • Paper beats Rock.

---

## 🧠 Python Concepts Used

* Variables and basic types (`str`, `int`)
* Input/output (`input()`, `print()`)
* Control flow (`if/elif/else`)
* Loops (`while` loop to continue the game)
* Randomness (`random.choice` for the computer’s move)
* Validation (check if the player’s choice is valid)
* Using string methods like `.capitalize()`
* Flow control with `continue`

---

## ▶️ How to Run (Jupyter Notebook)

* Abra o **Jupyter Notebook**.
* Carregue o notebook com o código.
* Execute a célula para iniciar o jogo. O programa pedirá sua jogada via `input()`.

---

## 💻 Code Examples (Key Concepts)

### Importing and using `random`

```python
import random
player_computer = random.choice(options)
```

### Capitalizing user input

```python
player_human = input("Type Player 1 option:").capitalize()
```

### While loop for continuous play

```python
while (points_player_human != 3) and (points_player_computer != 3):
    print("Write an option: Rock, Paper or Scissors:")
```

### Using `continue` to repeat a round

```python
if player_human == player_computer:
    print("It is a draw! Play again!")
    continue
```

### Conditional logic (`if/elif/else`)

```python
if player_human == "Rock":
    if player_computer == "Scissors":
        print("Player Human Won!")
    else:
        print("Player Computer Won!")
elif player_human == "Scissors":
    if player_computer == "Paper":
        print("Player Human Won!")
    else:
        print("Player Computer Won!")
elif player_human == "Paper":
    if player_computer == "Rock":
        print("Player Human Won!")
    else:
        print("Player Computer Won!")
```

---

## 📝 Notes

This was my **first Python project**, created in the finals of **May 2025**. It focuses on practicing:

* loops (`while`),
* conditionals (`if/elif/else`),
* user input,
* randomization (`random.choice`),
* string methods (`.capitalize()`),
* and flow control (`continue`) — all inside **Jupyter Notebook**.
