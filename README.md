## Autopilot
Project Autopilot helps in getting the angle of steering rotation in a self-driving car. This project is inspired from <b>NVIDIA End to End Learning for Self-Driving Cars</b> and data is gathered from <b>Udacity's Behavioral Cloning repository</b>. It is written in Python and leveraged Keras for Deep Learning functions. 

The End to End Learning for Self-Driving Cars research paper can be found at the below table.
This repository uses convolutional Neural Networks to predict steering angle according to the road. 

| 🗃 Dataset | 📑 Original Paper | 💡 Inspiration | 📌 Data Reference |
|:-:|:-:|:-:|:-:|
|[Dataset](https://github.com/SullyChen/driving-datasets)|[Paper](https://arxiv.org/abs/1604.07316)|[NVIDIA Self-driving](https://devblogs.nvidia.com/deep-learning-self-driving-cars/)|[Udacity](https://github.com/udacity/CarND-Behavioral-Cloning-P3)|

### 🛠 Output
<img src="https://github.com/akshaybahadur21/Autopilot/blob/master/v2.gif" width=700 height=400>

### 🗃 Dataset
Download the dataset from (https://github.com/SullyChen/driving-datasets) and extract into the repository folder.<br>

Data format is as follows: `filename.jpg angle,year-mm-dd hr:min:sec:millisec`

### 👉 Procedure
Step-1: First, run `LoadData_V2.py` which will get dataset from folder and store it in a pickle file after preprocessing.
Step-2: Now you need to have the data, run `Train_pilot.py` which will load data from pickle. After this, the training process begins.
Step-3: For testing it on the video, run `AutopilotApp_V2.py`

### 💡 Support
Support my work my marking this repo with a <b>"⭐ star"</b>

### 🧠 Main Credits
This repo is whole and sole referenced from [Akshay Bahadur](https://github.com/akshaybahadur21/Autopilot/tree/master/Autopilot_V2)
Data format is as follows: filename.jpg angle,year-mm-dd hr:min:sec:millisec

### 📩 Packages Installation 
Use `pip install -r requirements.txt` command to install packages in one go.
You can also use conda to get rid of any version provblems.

### 📰 Generic Description
An autonomous car (also known as a driverless car, self-driving car, and robotic car) is a vehicle that is capable of sensing its environment and navigating without human input. Autonomous cars combine a variety of techniques to perceive their surroundings, including radar, laser light, GPS, odometry, and computer vision. Advanced control systems interpret sensory information to identify appropriate navigation paths, as well as obstacles and relevant signage.

 ### 📢 Note:
 If you have a specific request or have an idea of better implementation, ping me:<br>
 @LinkedIn: [Message Snehit Vaddi](https://www.linkedin.com/in/snehitvaddi/)<br>
 @Email: (v.snehith999@gmail.com) 

### Python Implementation

1) <h4>Network Used</h4>- <i>Convolutional Network</i>
2) <h4>Inspiration</h4> - <i>End to End Learning for Self-Driving Cars by Nvidia</i>

If you face any problem, kindly raise an issue

### 🔗 References:
 - Mariusz Bojarski, Davide Del Testa, Daniel Dworakowski, Bernhard Firner, Beat Flepp, Prasoon Goyal, Lawrence D. Jackel, Mathew Monfort, Urs Muller, Jiakai Zhang, Xin Zhang, Jake Zhao, Karol Zieba. [End to End Learning for Self-Driving Cars](https://arxiv.org/abs/1604.07316)
 - [Behavioral Cloning Project](https://github.com/udacity/CarND-Behavioral-Cloning-P3) 
 - This implementation also took a lot of inspiration from the Sully Chen github repository: https://github.com/SullyChen/Autopilot-TensorFlow  






