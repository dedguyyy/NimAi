# Nim — Game and Q-Learning Agent

Implements the game of Nim, an AI trained via Q-learning, and utilities
for training and interactive play.

**Overview**
- `nim.py` contains the `Nim` game, a `NimAI` Q-learning agent, and helper
  functions `train()` and `play()` for training and human play.

**Quick Start**
```bash
cd nim
python -c "from nim import play, train; play(train(100))"
```

**Requirements**
- Python 3.6+
