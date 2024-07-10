# N-Queens Visualizer

**Table of Contents**
1. [Introduction](#introduction)
2. [System Architecture](#system-architecture)
3. [Front-end](#front-end)
4. [Algorithm Explanation](#algorithm-explanation)
5. [Installation](#installation)
6. [Usage](#usage)

## Introduction

The N-Queens Visualizer is a web-based application that visually demonstrates the process of solving the N-Queens puzzle. The N-Queens puzzle involves placing N queens on an N×N chessboard such that no two queens can attack each other, meaning no two queens share the same row, column, or diagonal. This project is implemented using JavaScript, CSS, and HTML, with development done in the VS Code IDE.

## System Architecture

The N-Queens Visualizer is a single-page application (SPA) built using the following technologies:
- **JavaScript**: For implementing the backtracking algorithm and logic.
- **HTML**: For structuring the web page.
- **CSS**: For styling the application.

## Front-end

The front-end of the N-Queens Visualizer is developed using vanilla JavaScript, HTML, and CSS. The user interface consists of a chessboard where queens are placed, control buttons to start/stop the visualization, and input fields to set the size of the chessboard (N).

### Front-end Pages

- **Main Page**: Displays the N×N chessboard and controls for the visualization.
- **Settings Panel**: Allows users to input the value of N and control the speed of the visualization.

### Front-end Tools and Libraries

- **JavaScript**: For dynamic interaction and visualization logic.
- **CSS**: For styling the components.
- **HTML**: For structuring the UI.

## Algorithm Explanation

The N-Queens puzzle is solved using a recursive backtracking algorithm. Here's a step-by-step explanation:

1. **Place a queen on the board**: Start with the first row and attempt to place a queen in each column.
2. **Recursively place the next queen**: Move to the next row and attempt to place a queen in a column where it does not conflict with previously placed queens.
3. **Check for conflicts**: Ensure that the new queen does not share the same row, column, or diagonal with any of the previously placed queens.
4. **Backtrack if conflicts arise**: If a conflict is detected, remove the queen and try the next column in the current row.
5. **Repeat until all queens are placed without conflicts**: Continue the process until all N queens are successfully placed on the board without any conflicts.
6. **Return the board configuration**: Once all queens are placed, the algorithm returns the board configuration as the solution.

## Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/NAYAN-KUMAR-SINGH/N-Queens/](https://github.com/NAYAN-KUMAR-SINGH/N-Queens/)
   ```
2. Navigate to the project directory:
   ```bash
   cd N-Queens
   ```

## Usage

1. Open the `index.html` file in your web browser:
   ```bash
   open index.html
   ```
2. Input the desired value of N in the settings panel.
3. Click the "Start" button to begin the visualization.
4. Observe the step-by-step placement of queens on the chessboard until a solution is found.

The N-Queens Visualizer provides an intuitive and educational way to understand the recursive backtracking algorithm used to solve the N-Queens puzzle. Enjoy exploring different board sizes and visualizing the solution process!
