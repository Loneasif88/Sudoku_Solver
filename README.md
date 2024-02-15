# Sudoku_Solver
This is a Minor Project Assignment from AccioJob. The project contains 9x9 buttons as numbers from 1- 9 . in which few cells are filled with values and rest are empty and you have to fill the remainig cells with correct number so that puzzle gets solved correctly.

Find Java File "src/sudou_solver/MainFrame.java"

Brief Introduction About the Project
  -The project is a game that allows the user to solve Sudoku puzzles.
  -The aim of the project is to recreate the experience of solving Sudoku puzzles that people used to do in newspapers.
  -The session will discuss the features of the game and have a live demo.
  -In upcoming sessions, the project will be built together.
  -The game consists of a 9x9 grid of boxes that can be filled with digits from 1 to 9.
  -The game has a reset button, an exit button, a solution button, and a check moves button.
  -The reset button empties the whole grid, the exit button closes the execution, the solution button fills the grid with expected solutions, and the check moves button checks whether the move is correct or not.
  -The game grid consists of 9 rows and 9 columns, which are buttons that can be clicked to fill the digit in the box.
  -The game will be built from scratch, and it will be a combination of a 9x9 matrix of buttons.

Sudoku Technologies
  -The project will primarily use Java language for coding.
  -Java Swing will also be used to build the GUI application.
  -Java Swing is a part of JFC (Java Foundation Classes) which is used to create window-based applications.
  -AWT (Abstract Windowing Toolkit) is the base for Java Swing.
  -Java Swing is used to build lightweight GUI applications.
  -Java Swing provides a lot of styling components such as buttons, labels, text fields, etc. for building the GUI.
  -JFrames are top-level containers provided by Java Swing which provide a playground for designing components.
  -JFrames are also known as base windows on which other components such as menu bars, panels, labels, text fields, buttons, etc. rely.
  -Almost every Java Swing application starts with the JFrame window.

Sudoku Building UI
  -The project will be created using Java with Ant and named "Sudoku solver".
  -The main Jframe form will be used for designing.
  -The size of the Jframe is set to 500x630.
  -Nine grids will be added to the Jframe using a panel for each grid.
  -Each panel will be resized to 146x149.
  -Panels will be copied and pasted to adjacent places.
  -Line borders will be added to each grid.
  -Buttons will be added to each grid and resized according to the grid size.
  -Duplicate buttons will be used.
  -All buttons will be added before further adjustments are made.

Sudoku Writing down the Logic.
  -9 buttons are present in every grid, with each button named according to row and column.
  -The buttons for selection, reset, exit, OK solution, and check moves are present, with their names changed, and size set to 40.
  -A 2D array string is created to store the solver values of Sudoku.
  -The turn variable will store the value of the selection button that is pressed.
  -The value of the turn variable will be set in the clicked grid.
  -Functionalities of 81 buttons inside the grid will be written in this video.
  -The functionality of selection buttons will be written in the next video, and the functionality of four buttons will be written in the last video.
  -The code for button functionalities is demonstrated for a few buttons, where an empty button will take the value of the turn variable and the background will be set to white.
  -For already filled buttons, a warning message box will appear.
  -The message inside the box can be customized according to need.

  -Upon clicking the exit button, a warning method will be displayed with two options: Yes or No. If Yes is clicked, the program will stop the execution and the JFrame window will be closed.
  -Upon clicking the reset button, a warning box will be displayed using JOptionPane. If Yes is clicked, the program will reset by replacing the prefilled grids with a blank text.
  -The function 'reset game' is called upon clicking the reset button. The 'buttons' array stores the names of the 81 buttons, while the 'predefined buttons' array stores the names of the buttons that are predefined.
  -Nested for loops are used to iterate over the 9 grids and their 9 buttons. A boolean flag variable is used to identify whether the value of a specific grid is predefined or not.
  -If a grid is not predefined, its value will be set to blank upon clicking the reset button.

  -Code for last two functionalities: solution button and check moves button
  -Create function for solution button after reset button
  -Avoid unnecessary extra spaces while writing code
  -Need two arrays: solved board and current board
  -In C solution function, check if grid is prefilled or not
  -If not prefilled, put value from solved board array
  -On click of solution button, want to show all solutions and then hide them
  -Use global flag to toggle between functionalities
  -If global flag is true, show solutions and change button text to "hide solution"
  -If false, hide solutions and change button text to "see solution"
  -Use boolean flag to check if button is predefined or not
  -Replace value of button with value from solved board array for the same index
  -Set foreground and background color for the button
  -the Continue Solving button will allow you to continue fix the wrong cells to make them correct.
  -The Check Puzzle button will check if your puzzle has completely solved or not and through you the Respective Message.


