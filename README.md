# Maze_Solver

## Table of Contents
- [Overview](overview)
- [Features](features)
- [Classes](classes)
- [Installation](installation)
- [Usage](usage)
- [Example](example)
- [Complex Maze Challenge](complex-Maze-Challenge)

## Overview
Maze Image Decomposer is a Java application designed to analyze and process images, decomposing them into connected components. It uses the Union-Find data structure to identify and connect components, allowing it to determine the connectivity between specified start and end points in a maze-like image.

## Features
- Decompose an image into its connected components.
- Identify and mark start and end points in the image.
- Determine if there is a solution path between the start and end points.
- Visualize the connected components with different colors.

## Classes
1. **Maze**: Decomposes an image into connected components and determines if there is a path between specified start and end points.
2. **UnionFind**: Implements the Union-Find data structure to manage the connected components.
3. **DisplayImage**: Handles the display and manipulation of images.

## Installation
To run the Maze Image Decomposer, you need to have Java installed on your system. Ensure you have a Java Development Kit (JDK) and an Integrated Development Environment (IDE) like IntelliJ IDEA or Eclipse.

## Usage
1. Clone the repository to your local machine.
2. Open the project in your IDE.
3. Ensure the image file you want to process is accessible and provide its path as an argument when running the program.

The program will output either true or false, indicating whether the maze is solvable and a picture of all connected components in the image.

## Example
```sh
java Maze maze_images/choose_your_maze
```

## Exploring a Complex Maze Challenge

Take a look at the maze image below:

![image8](https://github.com/OmerDahan1/Maze_Image_Decomposer/blob/main/maze_images/maze8.PNG)

### Do you think there's a solution to this maze? 

Try to find a path from the start to the end before checking the program's result.

### Program Output
After running the Maze Solver program on this maze, here is the resulting image::

![image8_solution](https://github.com/OmerDahan1/Maze_Image_Decomposer/blob/main/image8_solution.png)

In this solution image, different connected components of the maze are highlighted with distinct colors. As you can see, there is no continuous path from the start to the finish. The Union-Find algorithm accurately identified that the maze is unsolvable.

Explore other maze images to observe how the program identifies connected components and determines solvability for various mazes.
