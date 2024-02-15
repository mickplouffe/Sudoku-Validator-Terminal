# Sudoku Validator

Welcome to the Sudoku Validator project! This repository hosts a Java application designed to run in the terminal, aimed at validating Sudoku puzzles from a .txt format. Whether you're a Sudoku enthusiast or a Java developer looking to understand more about algorithmic problem-solving, this project is intended for educational and personal learning purposes.

[File will be uploaded in the future. This README is writen before hand.]

## Overview

The Sudoku Validator is a simple Java console application that checks whether a given Sudoku puzzle is valid according to the standard Sudoku rules. The application reads a Sudoku grid from a text file or user input and validates each row, column, and 3x3 subgrid to ensure all numbers comply with the game's rules.

## Features

- **Grid Input**: Supports input via text files or manual entry through the terminal, offering flexibility in how Sudoku grids are provided.
- **Validation Logic**: Incorporates robust algorithms to validate rows, columns, and 3x3 subgrids for the presence of unique numbers from 1 to 9.
- **Error Reporting**: Clearly identifies and reports any discrepancies found in the puzzle, including duplicates or invalid numbers.
- **User-Friendly Interface**: Simple and intuitive terminal interface for easy interaction and results interpretation.
- **Test Cases**: Includes a set of pre-defined Sudoku puzzles with varying levels of complexity for testing and validation purposes.

## Getting Started

To run the Sudoku Validator, ensure you have Java installed on your machine. Clone this repository, navigate to the project directory in your terminal, and compile the Java files:

```bash
javac SudokuValidator.java
```

Then, run the application:

```bash
java SudokuValidator
```

## How to Use

When running the application, you'll be prompted to either enter the Sudoku grid manually or choose a found text file containing the grid. Each row of the Sudoku should be entered or formatted in the file as nine numbers separated by spaces, with `0` or another placeholder representing empty cells.

## Contributing

As a personal learning project, contributions are not actively sought, but suggestions for improvements or bug reports are welcome. Feel free to open an issue if you have feedback or ideas to enhance the application.

## License

This project is open-sourced under the MIT License. See the [LICENSE](LICENSE.md) file for more details. It is meant for educational purposes, and while it can be used as a reference or starting point for your own projects, it comes with no warranty or support.
