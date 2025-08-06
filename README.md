# even-numbers
A simple Python script that finds and prints all even numbers within a user-specified range.
# 🔢 Even Number Finder

This is a command-line program written in Python that iterates through a range of numbers defined by the user and prints only the ones that are even.

The script prompts the user for a starting and an ending number. It then uses a `for` loop to check each number in that range (inclusive). If a number is even, it is printed to the console. 

## How to Use

1.  Make sure you have Python installed on your system.
2.  Save the code as a `.py` file (e.g., `EvenNumbers.py`).
3.  Open your terminal or command prompt.
4.  Navigate to the directory where the file is located and run the script:
    ```sh
    python EvenNumbers.py
    ```
5.  Enter the initial number for the range and press Enter.
6.  Enter the final number for the range and press Enter. The script will then print each even number found.

## How It Works

* **User-Defined Range:** The program takes two integer inputs from the user, a `first_number` and a `second_number`, to establish the boundaries of the search.
* **Iteration:** It uses a `for` loop with `range(first_number, second_number + 1)` to ensure every number from the start to the end (inclusive) is checked.
* **Even Number Check:** Inside the loop, an `if` statement with the modulo operator (`if number % 2 == 0`) checks if the current number has a remainder of 0 when divided by 2. Only numbers that meet this condition are printed.

## Technologies Used

* Python 3
