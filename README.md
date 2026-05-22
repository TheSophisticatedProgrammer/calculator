# Functional CLI Calculator

A robust command-line calculator app built with Python using functional programming styles and strict error catching.

## Features

- **Standard Math Suite**: Supports addition, subtraction, multiplication, division, and exponent powers.
- **Smart Data Outputs**: Strips trailing decimals automatically from whole-number results for cleaner terminal viewing.
- **Crash Protection**: Contains full exception blocks to gracefully trap invalid numeric strings and zero-division math bugs.

## Prerequisites

- Python 3.x

## How to Run

1. Save the code to a file named `main.py`.
2. Open your terminal.
3. Run the script:

## Usage Guide

1. Type your desired operation choice from the menu prompt (`add`, `subtract`, `multiply`, `divide`, `power`).
2. Provide two numbers sequentially as prompted.
3. Review the cleanly formatted output.
4. Type `quit` to exit the loop anytime.

## Technical Details

- **Lambda Routing**: Uses anonymous math functions passed as arguments straight into a master evaluation wrapper.
- **Dynamic Type Stripping**: Inspects floats using `.is_integer()` to seamlessly switch between integer and float layouts.
