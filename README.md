# AI Tic-Tac-Toe

A desktop Tic-Tac-Toe game where you play as **O** against an unbeatable **X** AI. The AI uses the Minimax algorithm with Alpha-Beta pruning.

## Requirements

- Python 3
- Tkinter (included with most standard Python installations)

No third-party packages are required.

## Run

From the repository folder, run:

```powershell
python .\tictactoe.py
```

Or provide the full path to the file:

```powershell
python "C:\path\to\AI_Mini-project\tictactoe.py"
```

The game window opens. Choose a square to make your move. Use **Reset / Play Again** to start another game.

## Project details

- Human plays **O**; the AI plays **X**.
- Minimax evaluates future game states.
- Alpha-Beta pruning skips branches that cannot improve the decision.
- The interface tracks wins, losses, draws, and nodes explored.
