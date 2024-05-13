The "Code" file contains the code for the program in C. 
By design the program reads the structure for the labyrinth from an input file, called "file.txt". It then solves the maze it has read using the A Star Pathfinding algorithm. 
After it has solved the maze, it visualizes the solution step by step on the screen along with the original maze it has read and the final solution. 

INPUT FILE:
The input file should be in the same folder as the C project and has to be called "file.txt".
Structure of the input file: 

The two numbers on the FIRST row represent the SIZE of the maze. In the provided example case this is a 25 by 25 maze. 

The two numbers on the SECOND row represent the X and Y coordinates of the START POINT in the maze. In the provided example case the Start Point is located at (5,5)

The two numbers on the THIRD row represent the X and Y coordinates of the END POINT in the maze. In the provided example case the End Point is located at (8,21)

The three numbers on the FOURTH row and every row after it represent each point in the maze. The first number represents the X coordinate of the point. The second number represents the Y coordinate of the point. 
The third number represents whether the point is a wall or a path. 1 = path, 0 = wall. In the provided example case the point located at (1,1) is a walkable path and the point located at (6,1) is a wall. 

The program detects incorrect structures in the maze and tells the user that the input file is not structured properly. 

CONVENIENCE 
Creating these input files is very tedious when it comes to creating bigger mazes, so I have provided a PYTHON program that asks the user to draw their custom maze and it then automatically compiles the input file based on the User's drawing

Instructions for using the Python program: 
1) It generally takes a bit of time to start. Don't panic if nothing happens immediately after you click it.
2) DRAW A WALL - left click
3) ERASE A WALL - right click
4) PLACE STARTING POINT - S
5) PLACE END POINT - E
6) SAVE DRAWN MAZE TO FILE - ENTER

The file would then get saved to a file called "maze.txt". Copy its contents and paste them in "file.txt" to have the program work with your custom maze. 
You should close the Python window manually after pressing Enter.
