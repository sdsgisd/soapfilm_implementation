# Implementation of an anonymous paper

Author: Anonymous Programmers  
Lisence: All rights reserved. Will be MPL-2.0 when it is published.

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
Initialization: press 'G', then press 'i' twice to get the simulation mode 2, and run.

#### Cyclone 
Configuration file: cyclone.txt  
Initialization: press 'G' and run. The velocity field customized for this scene is automatically generated.

## Dependencies
This program is built by standard procedures using CMAKE (http://www.cmake.org).  
The following external libraries are required:     
Eigen (http://eigen.tuxfamily.org)  
LAPACK (http://www.netlib.org/lapack/)  
libigl (http://libigl.github.io/libigl/)  
OpenGL (https://www.opengl.org/)  
GLEW (http://glew.sourceforge.net/) for non-mac OS
