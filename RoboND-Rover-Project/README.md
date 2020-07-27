# Search and Sample Return Project

This project is modeled after the [NASA sample return challenge](https://www.nasa.gov/directorates/spacetech/centennial_challenges/sample_return_robot/index.html) and it covers the three essential elements of robotics, which are perception, decision making and actuation. This project was carried out in a simulator environment built with the Unity game engine. 

## The Simulator
The first step is to download the simulator build that's appropriate for your operating system.  Here are the links for [Linux](https://s3-us-west-1.amazonaws.com/udacity-robotics/Rover+Unity+Sims/Linux_Roversim.zip), [Mac](	https://s3-us-west-1.amazonaws.com/udacity-robotics/Rover+Unity+Sims/Mac_Roversim.zip), or [Windows](https://s3-us-west-1.amazonaws.com/udacity-robotics/Rover+Unity+Sims/Windows_Roversim.zip).   
You can test out the simulator by opening it up and choosing "Training Mode".  Use the mouse or keyboard to navigate around the environment and see how it looks.

## Dependencies
Python 3 and Jupyter Notebooks will be needed to do this project.

## Recording Data
In `test_dataset` folder you'll find a csv file with the output data for steering, throttle position etc. and the pathnames to the images recorded in each run.  A few images in the folder called `calibration_images` would be used to do some of the initial calibration steps with. 
I've create a new folder 'calibration_images' to store the image data in. 

The overall report was in the pdf file 