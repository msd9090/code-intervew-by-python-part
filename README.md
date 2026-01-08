## 🚀 Python Interview Mastery: Part 2
Welcome to the Python Interview Mastery repository! This project is a curated collection of Python programming concepts, algorithmic challenges, and core data structures specifically designed to help you ace technical interviews.

Whether you are brushing up on your syntax or diving into custom sorting algorithms, this interactive notebook covers it all.

## 📚 What's Inside?
This repository contains an extensive Jupyter Notebook covering:

## 🔄 Control Flow: Mastering while loops (including break and continue) and for loops with else clauses.

## 🧩 Functions & Scope:

Defining functions with multiple input arguments.

Understanding *args for variable-length arguments and **kwargs for keyword arguments.

Global vs. Local variable scope.

## 🏗️ Data Structures: Deep dives into Lists, Tuples, Sets, and Dictionaries.

## 🔡 String Manipulation: Advanced slicing, formatting, and built-in methods like .strip(), .replace(), and .split().

## ⚙️ Algorithms: Implementation of a custom Selection Sort algorithm using nested loops and value swapping.

##  🛠️ How to Run
Follow these steps to get the environment ready and run the code on your local machine.

1. Prerequisites
Ensure you have Python 3.x installed. You can check your version by running:

Bash

python --version
2. Install Jupyter Notebook
If you don't have Jupyter installed, you can install it via pip:

Bash

pip install notebook
3. Clone the Project
Download this repository to your local machine:

Bash

git clone <your-repo-url>
cd <your-repo-name>
4. Launch the Notebook
Run the following command in your terminal to open the Jupyter interface:

Bash

jupyter notebook
A browser window will open. Click on code-intervew-by-python-part-2 (1).ipynb to start exploring!

## 💡 Key Code Snippet: Custom Sorting
One of the highlights of this project is the manual implementation of a sort function without using Python's built-in .sort():

Python

# Custom Selection Sort Example from the Notebook
def sortList(L):
    for j in range(len(L)):
        min_val = L[j]
        min_idx = j
        for i in range(j + 1, len(L)):
            if L[i] < min_val:
                min_val = L[i]
                min_idx = i
        # Swap values
        L[j], L[min_idx] = L[min_idx], L[j]
    return L
(Based on logic found in cells)

## 🤝 Contributing
Found a bug or want to add more interview questions? Feel free to fork the repo and submit a Pull Request!

Happy Coding! 🐍
