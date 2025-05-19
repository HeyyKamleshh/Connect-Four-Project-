# CONNECT FOUR AI
# How TO IMPLEMENT
  If you want to play 2-player against your friend, run the command: python3 main.py
  If you are alone and need an AI friend to play against (who you probably can’t beat), run the command:python3 versus_ai.py

# REQUIREMENT.TXT
Install them using:
pip install -r requirements.txt

## 🧠 Game Modes
 ### 1. main.py – 2 Player Game
Two human players take turns — just run it and play with your friend, sibling, or anyone who can reach your keyboard.

 ### 2. versus_ai.py – Human vs AI
Here, you play against the computer. The AI randomly selects a valid column (so, it's beatable — don't worry). No fancy algorithms here, just simple random moves.

## 🧪 crazy.py – Speed Test Mode

We simulate 1000+ games between two AIs (just like two bots tossing coins at each other until one wins).
 Why? To see how fast games can end and how often certain game durations happen.

You get results like:

Time taken to finish a game

How many games ended in X seconds

## 📊 plotter.py – Plot the Madness
We take the results from crazy.py and plot them using Matplotlib.

You’ll see a scatter plot showing:

X-axis: Time taken to finish a game

Y-axis: Number of games that ended in that time

This helps us understand how long games typically last when two AIs are playing completely randomly.

