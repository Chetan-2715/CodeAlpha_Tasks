# 🌟 CodeAlpha Internship Tasks
Welcome to my project repository from the CodeAlpha internship! This repo contains practical mini-projects written in Python that helped me strengthen my logic-building and automation skills. Below is a summary of each project along with the core logic used.

---

## 📁 Projects Overview

### 🔹 1. Hangman Game (`hangman_game.py`)
**Description:** A terminal-based word guessing game where the player must guess the hidden word letter by letter.

**Key Features:**
- Randomly selects a word from a list.
- Displays blank placeholders for unguessed letters.
- Tracks previously guessed letters and remaining attempts.
- Ends game with success or failure message.

**Concepts Used:** random, loops, conditionals, sets, string manipulation.

---

### 🔹 2. File Organizer (`file_organizing.py`)
**Description:** A script to automatically organize files in a directory by sorting them into subfolders like Documents, Images, Music, etc.

**Key Features:**
- Identifies file extensions and categorizes files.
- Creates folders if they don't exist.
- Moves files using `shutil` into appropriate folders.

**Concepts Used:** `os`, `shutil`, file system traversal, extensions mapping.

---

### 🔹 3. Smart Chatbot (`chatbot.py`)
**Description:** An interactive chatbot named **Stark** that can:
- Greet users.
- Solve arithmetic expressions (e.g., `solve 25 + 36 / 6`).
- Provide weather updates using OpenWeatherMap API.
- Answer basic general knowledge questions.

**Key Features:**
- Tokenization and lemmatization using NLTK.
- Math expression parsing using `eval()`.
- External API integration for weather.
- Friendly greetings and fallback responses.

**Concepts Used:** `nltk`, `requests`, `re`, string processing, API handling, logic flow control.
