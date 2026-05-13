# 🧩 Lexical Twist Puzzle

## 📌 Project Overview

The **Lexical Twist Puzzle** is a console-based Java application that processes two words and performs transformations based on logical conditions.

The system validates inputs, checks reverse relationships, applies string transformations, and analyzes vowel–consonant distribution while progressively evolving into a fully modular OOPS-compliant architecture.

This project demonstrates:

- Incremental feature development
- Clean GitFlow branching strategy
- Modular OOPS design
- Defensive programming
- Maintainable and extensible architecture

---

## 🚀 Features Implemented (Use Case Evolution)

### ✅ UC1 – Display Puzzle Title
Displays the application name.

### ✅ UC2 – Accept Word Inputs
Accepts two user inputs via console.

### ✅ UC3 – Single Word Validation
Ensures only single words are accepted using defensive programming.

### ✅ UC4 – Reverse Relationship Check
Checks whether the second word is the reverse of the first word (case-insensitive).

### ✅ UC5 – Word Transformation
If reverse match:
- Reverse word
- Convert to lowercase
- Replace all vowels with '@'

### ✅ UC6 – Combine & Count
If not reverse:
- Combine both words
- Convert to uppercase
- Count vowels and consonants

### ✅ UC7 – Rule-Based Output
Based on vowel–consonant distribution:
- Print first 2 unique vowels
- OR first 2 unique consonants
- OR equality message

### ✅ UC8 – OOPS Refactor
Refactored into modular architecture:

| Class | Responsibility |
|--------|---------------|
| `LexicalTwistPuzzle` | Input & Output handling |
| `WordValidator` | Input validation |
| `LexicalAnalyzer` | Business logic |

---

## 🏗 OOPS Principles Demonstrated

- ✔ Encapsulation
- ✔ Abstraction
- ✔ Single Responsibility Principle
- ✔ Modularity
- ✔ Extensibility

---

## 🔀 GitFlow Implementation

This project follows a structured GitFlow approach:

- `main` → Production-ready version
- `develop` → Integration branch
- `feature/*` → Each use case implemented separately

All feature branches are preserved to demonstrate incremental development.

---


