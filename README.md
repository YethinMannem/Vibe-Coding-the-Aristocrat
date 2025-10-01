# Vibe-Coding the Aristocrat: A Cipher Solver Notebook

This project is a solution for Assignment 0 in CSCI 717: Software Construction. It features a Python program, delivered as a Jupyter Notebook (`.ipynb`), capable of solving monoalphabetic substitution (Aristocrat) ciphers. The program was developed through an exploratory, conversation-driven process using Large Language Models (LLMs) as pair-programming partners.

## 📜 Description

The `solver.ipynb` notebook contains a self-contained script that uses statistical analysis to crack ciphers. It builds a language model based on n-gram frequencies from an embedded text corpus and then uses a stochastic hill-climbing algorithm to search for the most likely decryption key.

## ✨ Features

- **No Dependencies:** The notebook runs using only standard Python 3 libraries.
- **Robust Solving Engine:** Uses bigram and trigram analysis for high accuracy.
- **Automated Search:** Employs a hill-climbing algorithm to find the optimal solution without manual guessing.
- **Interactive:** The notebook prompts the user to paste any ciphertext for instant analysis.
- **Self-Contained:** The English language corpus is embedded in the script, so no extra files are needed.

## 🚀 How to Run

To run this project, you need an environment capable of opening and executing Jupyter Notebooks. Here are two common methods:

### Option 1: Using Google Colab (Recommended)

This is the easiest method as it requires no local installation.

1.  Navigate to [Google Colab](https://colab.research.google.com/).
2.  In the welcome pop-up, click on the **`Upload`** tab.
3.  Select the `final_solver.ipynb` file from your computer to upload it.
4.  Once the notebook is open, run the single code cell by clicking the **Play button** (▶️) to its left.

### Option 2: Using a Local Jupyter Environment

Use this method if you have Anaconda or Jupyter installed on your computer.

1.  **Prerequisites:** Ensure you have a working installation of Jupyter Notebook or JupyterLab.
2.  **Launch Jupyter:** Open your terminal or command prompt, navigate to the directory containing the `solver.ipynb` file, and launch the application:
    ```bash
    # For Jupyter Notebook
    jupyter notebook
    
    # Or for JupyterLab
    jupyter lab
    ```
3.  **Open the Notebook:** Your web browser will open with the Jupyter interface. Click on the `solver.ipynb` file to open it.
4.  **Run the Code Cell:** With the notebook open, select the code cell and run it by clicking the **`Run`** button in the toolbar or by pressing **`Shift + Enter`**.

### After Running the Code Cell

Regardless of the method you choose, after you execute the code cell:
1.  The program will train its language model and display a prompt.
2.  **Paste your ciphertext** into the input box that appears.
3.  Go to a new, empty line and press **`Enter`** to submit the text.
4.  The script will begin the automated search and print the final solution.
