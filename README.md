# Sudoku Solver

## Introduction
Sudoku Solver is a Java-based application developed as a Minor Project Assignment from AccioJob. It provides an interactive platform for users to solve Sudoku puzzles, replicating the experience of solving Sudoku puzzles commonly found in newspapers and puzzle books.

## Project Overview
- The game presents users with a 9x9 grid of cells, with some cells pre-filled with digits from 1 to 9.
- Users aim to fill in the remaining cells with correct digits such that each row, column, and 3x3 subgrid contains all the digits from 1 to 9 without repetition.
- The project aims to enhance problem-solving skills and logical thinking by engaging users in the process of solving Sudoku puzzles.

## Technologies Used
- Java: The core programming language used for implementing the logic and functionality of the Sudoku Solver.
- Java Swing: A graphical user interface (GUI) toolkit used to build the interactive user interface of the Sudoku Solver application.
- Ant: A build automation tool used for building and managing the project.

## Building UI
- The user interface is built using Java Swing, which provides a set of lightweight components for creating graphical interfaces.
- The main JFrame form serves as the canvas for designing the Sudoku grid and control buttons.
- The grid layout is achieved by arranging panels, each representing a 3x3 subgrid, within the JFrame.
- Buttons within each panel represent individual cells of the Sudoku grid, allowing users to input digits.

## Writing Down the Logic
- The logic of the Sudoku Solver is implemented using Java, with an emphasis on maintaining the rules and constraints of Sudoku puzzles.
- A 2D array is utilized to store the Sudoku grid, with empty cells represented by blank values.
- Functionality for handling user interactions, such as filling in cells, resetting the grid, and checking solutions, is implemented through event listeners and handlers.

## Features
- **Reset Button**: Clears the Sudoku grid, allowing users to start afresh.
- **Exit Button**: Closes the application, terminating the execution.
- **Solution Button**: Provides the solution to the Sudoku puzzle, allowing users to compare their progress or obtain hints.
- **Check Moves Button**: Validates user inputs, highlighting incorrect entries and providing feedback on the correctness of the puzzle.
- **Continue Solving Button**: Allows you to continue solve the wrong cell/entries to make them correct. it doesn't resets you all moves or cells.
- **Check Puzzle Button** :  Check if you have correctly solved the puzzle or not and through you the message accordingly. if not solved correctly the it will highlight the buttons with red color.

## Usage
1. Compile and run the Java application.
2. Interact with the Sudoku grid and control buttons to solve the puzzle.
3. Utilize features such as solution checking and resetting as needed to aid in solving the puzzle.

## Future Enhancements
- **Difficulty Levels**: Implement varying difficulty levels for Sudoku puzzles to cater to users with different skill levels.
- **Multiplayer Mode**: Introduce a multiplayer mode where users can compete in solving puzzles against each other.
- **Customization Options**: Provide options for customizing the appearance of the Sudoku grid and user interface.
- **Performance Optimization**: Optimize the solving algorithm to improve the application's performance for larger puzzles.

## Contributions
Contributions to the project are welcome! Feel free to fork the repository, make improvements, and submit pull requests.

## License
This project is licensed under the [free licence), which means it is free to use, modify, and distribute, subject to certain conditions.

