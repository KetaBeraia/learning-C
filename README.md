# Small C Projects

A collection of small, terminal-based programs written in C to practice core programming fundamentals.

These projects are intentionally simple. The focus is on correctness, clarity, and understanding low-level concepts rather than visual polish or advanced abstractions.

---

## Purpose

This repository exists to practice and solidify:
- Core C syntax and control flow
- Working with arrays and strings
- Loops (`for`, `while`)
- Input validation and error handling
- Program structure and basic logic
- Problem-solving through small, complete programs

Each project is self-contained and targets a specific concept.

---

## Projects

### 1. Number Guessing Game
A terminal game where the computer selects a random number and the player attempts to guess it.

**Features:**
- Random number generation (1–100)
- Feedback on guesses (too high / too low)
- Input validation
- Tracks number of attempts

**Concepts practiced:**
- `rand()` and `srand()`
- Loops and conditionals
- User input handling
- Basic game logic

---

### 2. Hangman Game
A terminal-based implementation of the classic Hangman game.

The program randomly selects a word, and the player guesses it letter by letter before running out of allowed mistakes.

**Features:**
- Random word selection
- Letter-by-letter guessing
- Tracks incorrect guesses
- Prevents repeated letter inputs
- Displays current progress of the word

**Concepts practiced:**
- Character arrays and strings
- Functions and modular design
- Loops and conditional logic
- Input validation
- Game state tracking

---

### 3. Number Comparison Logic
A program where the user repeatedly guesses a randomly generated number until the correct value is entered.

**Concepts practiced:**
- Comparison operators
- Loop control (`break`, `continue`)
- Input validation with `scanf`
- Clearing input buffers

---

### 4. Factorial Calculation
A program that calculates the factorial of 10 using an array and a loop.

**Concepts practiced:**
- Arrays
- `for` loops
- Accumulator variables
- Basic mathematical logic

---

### 5. Average Marks Program
A program that calculates the average marks for multiple subjects using a 2D array.

**Concepts practiced:**
- Two-dimensional arrays
- Nested loops
- Floating-point arithmetic
- Structured data processing

---

### 6. While Loop Control Example
A small program demonstrating `while` loop behavior with `break` and `continue`.

**Concepts practiced:**
- `while` loops
- Conditional branching
- Loop interruption logic
- Understanding control flow behavior

---

## How to Run

Compile and run any program using `gcc`:

