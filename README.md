# Terrain Generator for Godot 3D (3.4.x)

## Project Description
A simple terrain generator for Godot 3D.

![image](https://user-images.githubusercontent.com/90869314/216716389-03054f5b-7ee5-4507-b56c-71b49fe1996d.png)

Provides a class called "TerrainGenerator" (and "TerrainGeneratorAsync" for better performance at the cost of an additional thread) which can be created with the .new() function. Once created, add the object to the scene tree, and it will generate customizable terrain around the position of a 3D "target."

The terrain generated is very simple, so feel free to use this as a starting point. Layering additional noisemaps on top of this terrain for biomes, rivers, and other features would be a good place to start.

## How to Build
1. Download the project as a zip & unzip somewhere on your device
2. Use the Godot launcher (last tested with Godot 3.4.x) to open the project
3. Run from the Godot application
