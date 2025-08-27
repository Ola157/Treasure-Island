# Treasure Island

## Overview

**Treasure Island** is a simple text-based adventure game built in Python. The player makes choices that determine their fate while navigating through obstacles to find the hidden treasure. It’s a quick, interactive game that demonstrates the use of conditional logic, user input handling, and storytelling.

## Demo

![alt text](<Treasure Island 2.gif>)

## How It Works

The game presents the player with a sequence of choices:

1. The first decision is whether to go **left** or **right**.

   * Choosing "right" leads to an immediate game over.
   * Choosing "left" continues the journey.
2. At the lake, the player can **wait** for a boat or **swim** across.

   * Waiting safely leads to an island.
   * Swimming ends in defeat.
3. On the island, the player must pick one of three doors:

   * **Yellow** reveals the treasure (victory).
   * **Red** or **blue** ends in defeat.

The game ends as soon as the player either finds the treasure or meets a game over condition.

## How to Run

1. Make sure you have **Python 3.x** installed on your machine.
2. Save the script into a file, for example: `treasure_island.py`.
3. Open a terminal or command prompt, then run:

```bash
python treasure_island.py
```

4. Follow the on-screen instructions by typing your choices (`left`, `right`, `wait`, `swim`, `yellow`, `red`, or `blue`).

## Resources

* [Python Official Documentation](https://docs.python.org/3/) – for understanding Python basics like `print()`, `input()`, and conditional statements.

---

Would you like me to also **add replay functionality** (so the player can restart instead of closing the program after losing), or keep it exactly as a one-shot playthrough?
