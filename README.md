# Evolutionary Robotics

 You can start by running the file:
 ### `Main`
 
The Main purpose of the code is to Create a neural networks & evolutional algorithm for a robot simulator robot. </br>

* Mobile robot simulator</br>
* ANN as controller </br>
* EA for evolve weights of ANN </br>
* Differnet room designs </br>


## Neural Network
* Used ANN as controller </br>
* Used two layers with recurrent nodes</br>
* Used feedback to create memory</br>
* Play with Dt (depend on time step)</br>
* Input: 12 infrared distance sensors (30°distance)</br>
* Output: two outputs – each controls speed of one wheel</br>

## Fitness criteria
* Collision-free </br>
* Fix time for each experiment </br>
* Simulate dust, used removed dust as fitness</br>


## Installation
The program is in Python <br />
In order to use the code you need to install the following packages
   ```sh
    import numpy as np
    import math
    import pygame
    import time
    import random
    import matplotlib.pyplot as plt
   ```

## Contributors
Elena Kane </br>
Nikolaos Ntantis </br>
Ioannis Montesantos 






