## Autopilot
This project helps in getting the angle of steering rotation in a self-driving car. This project is inspired from [NVIDIA End to End Learning for Self-Driving Cars](https://devblogs.nvidia.com/deep-learning-self-driving-cars/) and data is gathered from [Udacity's Behavioral Cloning repository](https://github.com/udacity/CarND-Behavioral-Cloning-P3).

The End to End Learning for Self-Driving Cars research paper can be found at (https://arxiv.org/abs/1604.07316)
This repository uses convnets to predict steering angle according to the road. 

## Dataset
You can download the dataset from this repository: https://github.com/SullyChen/driving-datasets

## Main Credits
This repo is whole and sole referenced from [Akshay Bahadur](https://github.com/akshaybahadur21/Autopilot/tree/master/Autopilot_V2)
Data format is as follows: filename.jpg angle,year-mm-dd hr:min:sec:millisec

##### Installation of Packages 
Use `pip install -r requirements.txt` command to install packages in one go.
You can also use conda to get rid of any version provblems.

### Generic Description
An autonomous car (also known as a driverless car, self-driving car, and robotic car) is a vehicle that is capable of sensing its environment and navigating without human input. Autonomous cars combine a variety of techniques to perceive their surroundings, including radar, laser light, GPS, odometry, and computer vision. Advanced control systems interpret sensory information to identify appropriate navigation paths, as well as obstacles and relevant signage

### Dataset
Download the dataset at [here](https://github.com/SullyChen/driving-datasets) and extract into the repository folder

### Python  Implementation

1) <h4>Network Used</h4>- <i>Convolutional Network</i>
2) <h4>Inspiration</h4> - <i>End to End Learning for Self-Driving Cars by Nvidia</i>

If you face any problem, kindly raise an issue

### Procedure

Step-1: First, run `LoadData_V2.py` which will get dataset from folder and store it in a pickle file after preprocessing.
Step-2: Now you need to have the data, run `Train_pilot.py` which will load data from pickle. After this, the training process begins.
Step-3: For testing it on the video, run `AutopilotApp_V2.py`

### Output
<img src="https://github.com/akshaybahadur21/Autopilot/blob/master/v2.gif">

### References:
 
 - Mariusz Bojarski, Davide Del Testa, Daniel Dworakowski, Bernhard Firner, Beat Flepp, Prasoon Goyal, Lawrence D. Jackel, Mathew Monfort, Urs Muller, Jiakai Zhang, Xin Zhang, Jake Zhao, Karol Zieba. [End to End Learning for Self-Driving Cars](https://arxiv.org/abs/1604.07316)
 - [Behavioral Cloning Project](https://github.com/udacity/CarND-Behavioral-Cloning-P3) 
 - This implementation also took a lot of inspiration from the Sully Chen github repository: https://github.com/SullyChen/Autopilot-TensorFlow  





