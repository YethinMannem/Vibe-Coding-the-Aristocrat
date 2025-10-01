# Vibe-Coding the Aristocrat: A Cipher Solver

This project is a solution for Assignment 0 in CSCI 717: Software Construction. It features a Python program capable of solving monoalphabetic substitution (Aristocrat) ciphers. The program was developed through an exploratory, conversation-driven process using Large Language Models (LLMs) as pair-programming partners.

## 📜 Description

The core of this project is `solver.py`, a self-contained script that uses statistical analysis to crack ciphers. It builds a language model based on n-gram frequencies from an embedded text corpus (Alice's Adventures in Wonderland) and then uses a stochastic hill-climbing algorithm to search for the most likely decryption key.

## ✨ Features

- **No Dependencies:** The script runs using only standard Python 3 libraries.
- **Robust Solving Engine:** Uses bigram and trigram analysis for high accuracy.
- **Automated Search:** Employs a hill-climbing algorithm to find the optimal solution without manual guessing.
- **Interactive:** Prompts the user to paste any ciphertext for instant analysis.
- **Self-Contained:** The English language corpus is embedded in the script, so no extra files are needed.

## 🚀 How to Run

1.  **Prerequisites:** Ensure you have Python 3 installed on your system.
2.  **Save the Code:** Save the program as `solver.py`.
3.  **Execute from Terminal:** Open a terminal or command prompt, navigate to the file's directory, and run the following command:
    ```bash
    python solver.py
    ```
4.  **Provide Input:**
    - The program will prompt you to paste your ciphertext.
    - After pasting your text (which can include multiple lines), go to a new, empty line and press **Enter**.
    - The script will begin the automated search and print the solution when complete.
