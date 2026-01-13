# Small C Projects

A collection of small, terminal-based projects written in C while learning core programming fundamentals.

These projects are intentionally simple. The focus is on correctness, clarity, and understanding low-level concepts rather than visual polish or advanced abstractions.

---

## Purpose

This repository exists to practice and solidify:
- Core C syntax and control flow
- Working with strings and arrays
- Input validation and error handling
- Program structure and modular design
- Problem-solving through small, complete programs

Each project is self-contained and designed to reinforce specific concepts.

---

## Projects

### 1. Number Guessing Game
A simple terminal game where the computer selects a random number and the player attempts to guess it.

**Features:**
- Random number generation (1–100)
- Feedback on guesses (too high / too low)
- Tracks number of attempts

**Concepts practiced:**
- Random number generation
- Loops and conditionals
- Input handling
- Basic game logic
### 2. Hangman Game
A terminal-based implementation of the classic Hangman game written in C.

The program randomly selects a word, and the player attempts to guess it one letter at a time before running out of allowed mistakes.

**Features:**
- Random word selection
- Letter-by-letter guessing
- Tracks incorrect guesses
- Prevents repeated letter inputs
- Displays current progress of the word

**Concepts practiced:**
- Character arrays and strings
- Loops and conditional logic
- Functions and modular program design
- Input validation
- Game state tracking

**How to run:**
```bash 
gcc guessing_game.c -o guessing_game
./guessing_game

gcc hangman.c -o hangman
./hangman




