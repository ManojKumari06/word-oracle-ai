# 🔮 Word Oracle AI

An advanced AI-powered word guessing game built entirely in Python and Jupyter Notebook.
Unlike traditional word games that only match letters, Word Oracle uses a multi-strategy
semantic similarity engine to measure how conceptually close your guess is to the target
word — so guessing "ocean" when the answer is "sea" actually gets you credit.

## ✨ What Makes It Different

Most word games are purely syntactic — they check letters, not meaning.
Word Oracle understands language at a deeper level using 5 ML techniques combined:

- 🧠 WordNet Path Similarity — measures conceptual closeness via Princeton's lexical database
- 📐 TF-IDF Cosine Similarity — character-level vector similarity using scikit-learn
- ✏️ Levenshtein Edit Distance — normalized spelling distance
- 🔤 Character N-gram Jaccard — bigram/trigram surface overlap
- 📍 Positional Letter Overlap — spatial letter matching

## 🎮 Game Modes
- Classic — unlimited guesses, adaptive difficulty
- Hardcore — only 6 guesses, hard words only
- Blitz — race against the clock

## 📊 ML Features
- Adaptive difficulty engine that adjusts based on your last 5 games
- Live semantic heat meter (❄ Freezing → 🔥 On Fire)
- Post-game Similarity Timeline chart
- Semantic Space Explorer — MDS plot of your guesses in 2D conceptual space
- XP-based rank system (Novice → Legend)

## 🛠 Tech Stack
Python · Jupyter Notebook · NLTK · scikit-learn · ipywidgets · matplotlib · NumPy

## 🚀 Run It
Open `word_oracle_game.ipynb` in Jupyter and run all cells top to bottom.
No API keys. No GPU. No cloud. Just Python.
