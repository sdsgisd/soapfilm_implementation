# A Model for Soap Film Dynamics with Evolving Thickness

This is an implementation of the paper “A Model for Soap Film Dynamics with Evolving Thickness” Anonymous Author et al., Transactions on Graphics (SIGGRAPH 2020).

Author: Anonymous Programmers  
Lisence: MPL-2.0

## Basic Usage
Running the executables without command line arguments will display the usage. Data files are located in the hgf_assets folder.

[KEY SETTING]  
Space: Run/Stop. 
s: Proceed one time step.  
i: Change simulation mode 0. surface flow only 1. surface deformation only 2. full model  
P: Add a random thickness field using Perlin noise  
C: Add a random velocity field using curl noise  
m: Change rendering mode.    


## Example Senarios

### Cyclone 
Configuration file: cyclone.txt  
Initialization: press 'XYZ' key

### Giant Bubble
Configuration file: giantbubble.txt  
Initialization: press 'XYZ' key

## Dependencies
This program is built by standard procedures using CMAKE (http://www.cmake.org).  
The following external libraries are required:     
Eigen (http://eigen.tuxfamily.org)  
LAPACK (http://www.netlib.org/lapack/)  
libigl (http://libigl.github.io/libigl/)  
OpenGL (https://www.opengl.org/)  
GLEW (http://glew.sourceforge.net/) for non-mac OS

### Acknowledgement
This program is built on HGF, which is a simulation program accompanying the paper “A Hyperbolic Geometric Flow for Evolving Films and Foams”, Ishida et al., Transactions on Graphics (SIGGRAPH Asia 2017).


