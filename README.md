# SudokuSolver
A basic Sudoku game with built in auto-solver.

### About
The Sudoku Solver game uses an algorithm to develop new random Sudoku puzzles. Once the puzzle is generated it allows the user to use mouse and keyboard to enter digits to attempt to fill out the puzzle. Once the player wants to check the answers the player can click the "Check Answers" button. The program will then check all filled out answers and if it is correct it will lock in the answers and change the text color to green. If a player gives up the player can click the "Auto-Solve Puzzle" button, the program will then use a backtracking algorithm to solve the Sudoku puzzle in real time allowing the player to watch how the algorithm works. As the puzzle is being auto-solved the puzzle will be locked and the auto-solved squares will have red text. A player can get a new puzzle at any point by simply clicking the "New Puzzle" button.

### Dependancies
* Python 3.8.2
* PyQT5

### Known Bugs
* No currently known bugs.

### License
MIT License

Copyright (c) 2020 James Denbow

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
