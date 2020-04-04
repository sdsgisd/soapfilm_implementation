# Implementation of a paper

Author: Anonymous Programmers  
Lisence: MPL-2.0

## Basic Usage
Running the executables without command line arguments will display the usage. Data files are located in the fes_assets folder.

[KEY SETTING]  
Space: Run/Stop.  
s: Proceed one time step.   
i: Change simulation mode 0. surface flow only 1. surface deformation only 2. full model  
P: Add a random thickness field using Perlin noise  
C: Add a random velocity field using curl noise  
m: Change rendering mode.    
G: Add a thickness field propotional to z-coordinate of vertex positions 

## Example Senarios

#### Giant Bubble
Configuration file: giantbubble.txt  
Initialization: press 'G', then press 'i' twice to get the simulation mode 2

#### Cyclone 
Configuration file: cyclone.txt  
Initialization: press 'G'

## Dependencies
This program is built by standard procedures using CMAKE (http://www.cmake.org).  
The following external libraries are required:     
Eigen (http://eigen.tuxfamily.org)  
LAPACK (http://www.netlib.org/lapack/)  
libigl (http://libigl.github.io/libigl/)  
OpenGL (https://www.opengl.org/)  
GLEW (http://glew.sourceforge.net/) for non-mac OS
