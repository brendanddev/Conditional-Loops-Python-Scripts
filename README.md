# Conditional Statements & Loops in Python
## Modular Functions, and User input & Validation Loops.

This repository contains solutions the project which focuses on the use of conditionals, loops, and modular programming techniques in Python.

## Project Overview

The project implements solutions for three problem statements, each designed to enhance understanding of modular programming and logical problem-solving. Solutions are organized into individual functions and the main script to ensure a clear separation of concerns and adherence to good programming practices.

## Features

### Problem Solutions

- **Question 1a**: 
  - Classifies a given pH value as **alkali**, **neutral**, or **acidic**.
  - If the value deviates by more than 3 units from neutrality (pH = 7), the classification string includes the prefix "VERY" (e.g., "VERY alkali").
  
- **Question 1b**:
  - Evaluates whether a planet’s temperature range supports the presence of liquid water and crop growth.
  - Determines if a planet is habitable based on the ability to sustain both water and crops.

- **Question 1c**:
  - Determines if three given side lengths can form a valid triangle.
  - Classifies valid triangles as **scalene**, **isosceles**, or **equilateral** based on the number of matching sides.

### Main Script (`assignment3.py.txt`)

- **Handles User Inputs**:
  - Prompts the user for inputs and calls the appropriate solution functions based on the provided values.
  
- **Displays Outputs**:
  - Outputs the results of each solution function in a user-friendly format.

### Interactive Functionality

- **Question 2**: 
  - Implements a loop that repeatedly accepts user inputs until the user decides to exit by typing "quit".
  - Checks for valid inputs before calling the function from Question 1 and displays an appropriate message for invalid inputs.

## Technical Implementation

- **Modules and Functions**:
  - Each solution is encapsulated in a separate function, ensuring modularity and reusability.
  
- **Input Validation**:
  - Validates user inputs based on the assumptions in the problem statements before processing the data.

- **Main Execution Flow**:
  - The main module orchestrates user interactions, function calls, and the display of results.

## How to Run

1. Download or clone the repository.
2. Open `assignment3.py.txt` in a Python IDE or text editor.
3. Run the script to execute the solutions for each question and interact with the user prompts.
