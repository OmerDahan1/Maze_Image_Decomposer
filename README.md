# Maze_Image_Decomposer

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

## Complex Maze Challenge
Let's explore a complex maze challenge! Below is an image of a maze:

hard_unsolvable

### Do You Think It Has a Solution?
Before running the program, take a look at the maze image above and consider whether you think it has a solution. Can you find a path from the start to the end of the maze?

### Program Result
After running the Maze Solver program on the complex maze, here's the output:

hard_output

In this image, you can see the connected components of the maze. Each component is color-coded for clarity. As you can observe, the complex maze is not solvable, and the Union-Find algorithm has correctly identified the absence of a path from the start to the end.

Feel free to explore other provided maze images to see how the program handles different mazes and their connected components.



