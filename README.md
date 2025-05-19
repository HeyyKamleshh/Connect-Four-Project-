# CONNECT FOUR AI
# How TO IMPLEMENT
  If you want to play 2-player against your friend, run the command: python3 main.py
  If you are alone and need an AI friend to play against (who you probably can’t beat), run the command:python3 versus_ai.py

# REQUIREMENT.TXT
Install them using:
pip install -r requirements.txt

🧠 Game Modes
1. main.py – 2 Player Game
Two human players take turns — just run it and play with your friend, sibling, or anyone who can reach your keyboard.

2. versus_ai.py – Human vs AI
Here, you play against the computer. The AI randomly selects a valid column (so, it's beatable — don't worry). No fancy algorithms here, just simple random moves.

🧪 crazy.py – Speed Test Mode

We simulate 1000+ games between two AIs (just like two bots tossing coins at each other until one wins).
 Why? To see how fast games can end and how often certain game durations happen.

You get results like:

Time taken to finish a game

How many games ended in X seconds

📊 plotter.py – Plot the Madness
We take the results from crazy.py and plot them using Matplotlib.

You’ll see a scatter plot showing:

X-axis: Time taken to finish a game

Y-axis: Number of games that ended in that time

This helps us understand how long games typically last when two AIs are playing completely randomly.
### PROBLEM FORMULATION
- WISE MOVE
Since our childhood, we've been losing to our elder siblings in the game of Connect 4. Now that we have a chance to build an AI model which takes the most optimal moves, we think we've got a chance to finally pay back!

- RANDOM WALK
In Maths, a random walk, sometimes known as a drunkard's walk, is a random process that describes a path that consists of a succession of random steps on some mathematical space. We’ll try to verify this theory with our random moves

### QUICK LITERATURE SURVEY
In recent years, artificial intelligence (AI) has significantly advanced gameplay experiences by training AI agents to make optimal and random moves in various games. Researchers have employed reinforcement learning, Monte Carlo Tree Search, deep learning, and hybrid approaches to improve AI player performance. This literature survey highlights the strategies, game-specific implementations, ethical considerations, and real-world applications of AI-enhanced gameplay. As AI continues to evolve, it has the potential to reshape the gaming industry and find applications in diverse domains beyond entertainment, making it essential to understand the current state of research in this field.

### METHOD
- UNDERSTANDING
Ensure a clear grasp of Minimax algorithm for two-player games, where the AI aims to maximize its advantage while minimizing the opponent's gain.

- GAME STATE
Define a concise and comprehensive representation of the game state that captures all essential information.

- IMPLEMENTATION
Create a recursive Minimax function that explores possible moves for both players while incorporating alpha-beta pruning for efficiency.

- EVALUATION
Develop an evaluation function to assign numerical values to game states, aiding decision-making in the Minimax algorithm based on game rules and objectives.

- TESTING 
Thoroughly test and fine-tune your Minimax-based AI, adjusting the evaluation function and parameteres to improve performance and balance optimal and random moves as needed as player experience.

### CONCLUSION
- Strategic Fusion
We combine Minimax with stochastic elements, using random moves to validate the theory of random walk in gaming, resulting in a versatile approach.

- Balanced Optimal Play
Our AI maintains equilibrium between Minimax's optimal strategies and random moves for empirical validation, enriching both the gaming experience and game theory.

- Iterative Improvement
Through iterative testing and parameter tuning, we achieve dynamic gameplay while advancing our understanding of random walk theory in gaming.