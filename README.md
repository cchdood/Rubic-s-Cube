# Rubic-s-Cube
# made by 陳郁安 (Student ID. B10703014) from National Taiwan University

# A. Abstract.
    This is a python code written with pygame and Opengl to simulate the operation and solving algorithm of Rubic's Cube.

# B. Requirement & Guide to run the code.
      B-1 Requirement
      1. The code is written with python 3.9.7, so Python (version later than 3.9.7) should be installed. Python download link:https://www.python.org/downloads/
      2. The code uses OpenGL Library. So OpenGL should be installed.
          2-1. Installation of OpenGL for python
               Step One. 
                   Download PyOpenGL_accelerate‑3.1.6‑....whl and PyOpenGL‑3.1.6‑....whl from https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyopengl
                   ps. download the right files according to your pc system and python version. For instance, I use 64-bit windows and python 3.9.7,
                   so I download PyOpenGL_accelerate‑3.1.6‑cp39‑cp39‑win_amd64.whl (cp39 means PY 3.9) and PyOpenGL‑3.1.6‑cp39‑cp39‑win_amd64.whl.
                 
               Step Two. 
                   Open cmd, use "cd" command to direct to the path where the two .whl files are, and run the following code:
                   $ pip install PyOpenGL-3.1.6-....whl
                   $ pip install PyOpenGL_accelerate-3.1.6-....whl
                 
                   Just remember to direct to the right path first and run "pip install (file name.whl)" for the two files.
                   That's it!
                 
      3. The code uses Pygame library. So Pygame should be installed. Just open cmd and run the following code: $ pip install pygame
      
      B-2 Run the code
      You can copy and paste all the code from "main code" to your IDE. link: https://github.com/cchdood/Rubic-s-Cube/blob/main/main%20code. 

# C. Control
      You can manually change the view of the cube or do certain operation with the hotkeys:
      C-1 Change the view of cube (rotating the whole cube)
      "W" key - Rotate up
      "S" key - Rotate down
      "A" key - Rotate left
      "D" key - Rotate right
      "Q" key - Rotate anticlockwise
      "E" key - Rotate clockwise
      
      C-2 Manual Operation (rotating single layer)
      note. When rotating a single layer of the cube, we have to specify which layer to rotate. So we let the layer to rotate be "n-th layer". 
            (n is 1 by default, but can be changed with hotkeys)
      "I" key - Rotate the n-th layer (n-th column) up
      "K" key - Rotate the n=th layer (n-th column) down
      "J" key - Rotate the n-th layer (n-th row) left
      "L" key - Rotate the n-th layer (n-th row) right
      "U" key - Rotate the n-th layer (the 1st layer is the one closest to you) anticlockwise
      "O" key - Rotate the n-th layer clockwise
      "1" key - change the value of n to 1
      "2" key - change the value of n to 2
      "3" key - change the value of n to 3
      
      C-3 Special Operation
      "R" key - Shuffle the cube
      "Home" key - Solve the cube (the solving algorithm I use is not the most efficient one, so it takes some time to solve)
      
# D. Control Guide and solving showcase:
      https://www.youtube.com/watch?v=LVUK65qG2_Q
