#Rocket Trajectory Simulator
-This is a 2D rocket trajectory simulator based off of SpaceX Falcon 9 Stage 1.
-It includes, drag, decreasing mass, and a changing angle during the rocket's trajectory. This code is meant to model a rocket's trajectory using simple physics equations and algebra, without having to rely on calculus. 

##How The Physics Works:
- Assumes constant gravity(9.8 m/s^2 downwards)
-  Uses a flight angle. However, the rocket shoots up vertically for the first 60 seconds. Once the angle starts to change, thrust and velocity are split into components as well
- The rocket gets lighter as it burns fuel, with a burn time of 162 seconds before it runs out of fuel. Once fuel runs out, the rocket depends on gravity and drag to coast.

##For the Simulation:
The simulation is in python, so Python, Jupyter Notebook, or Google Colab is needed to run this. 
matplotlib and numpy should be installed in the code

##Output:
-When the code is run, a chart with time, velocity, altitude, and horizontal distance should display all of the values in 10 second interverals from when the rocket launches to when it crashes or lands.
-Six graphs will be printed as well. These graphs compare time with the horizontal velocity, vertical velocity, horizontal acceleration, vertical acceleration, altitude, and distance.
