## Self Driving Car
Project Autopilot helps in getting the angle of steering rotation in a self-driving car. This project is inspired by <b>NVIDIA End to End Learning for Self-Driving Cars</b> and data is gathered from <b>Udacity's Behavioral Cloning repository</b>. It is written in Python and leveraged Keras for Deep Learning functions. 

The End to End Learning for Self-Driving Cars research paper can be found in the below table.
This repository uses Convolutional Neural Networks to predict steering angle according to the road. 

| 🗃 Dataset | 📑 Original Paper | 💡 Inspiration | 📌 Data Reference |
|:-:|:-:|:-:|:-:|
|[Dataset](https://github.com/SullyChen/driving-datasets)|[Paper](https://arxiv.org/abs/1604.07316)|[NVIDIA Self-driving](https://devblogs.nvidia.com/deep-learning-self-driving-cars/)|[Udacity](https://github.com/udacity/CarND-Behavioral-Cloning-P3)|

#### Note: 
💡 **I have made implementation code `AutopilotApp_V2.py` private to avoid misuse, feel free to contact me @v.snehith999@gmail.com to buy complete directory ✌**<br>
🔑 **If you're looking any Btech/Mtech/Academic projects? Ping me, I have a bunch**

### 🧠 Main Credits
**This repo is whole and sole referenced from [Akshay Bahadur](https://github.com/akshaybahadur21)**

### 🛠 Output
<img src="https://github.com/snehitvaddi/SelfDriving-Car_Deep-Learning/blob/master/Selfdriving-output.gif" width="300" height="300">

### 🗃 Dataset
Download the dataset from (https://github.com/SullyChen/driving-datasets) and extract it into the repository folder.<br>

Data format is as follows: `filename.jpg angle,year-mm-dd hr:min:sec:millisec`

### 🏃‍♂️ How to Run the code
Step-1: Run `LoadData_V2.py`. This will flow through the dataset and generates `labels` and `features` pickle files.<br>
Step-2: After generating two files, run `Train_pilot.py` which will load pickle files. After this, the training process begins.<br>
Step-3: For testing it on the video, run `AutopilotApp_V2.py`<br>
**I have made `AutopilotApp_V2.py` private to avoid misuse, feel free to contact me @v.snehith999@gmail.com for complete directory ✌**

### 💡 Support
Support my work my marking this repo with a <b>"⭐ star"</b>

### 📰 Generic Description
An autonomous car (also known as a driverless car, self-driving car, and robotic car) is a vehicle that is capable of sensing its environment and navigating without human input. Autonomous cars combine a variety of techniques to perceive their surroundings, including radar, laser light, GPS, odometry, and computer vision. Advanced control systems interpret sensory information to identify appropriate navigation paths, as well as obstacles and relevant signage.


### 📩 Packages Installation 
Use the `pip install -r requirements.txt` command to install packages in one go.
You can also use conda to get rid of any version problems.

 ### 📢 Note:
 If you have a specific request or have an idea of better implementation, ping me:<br>
<b>@LinkedIn:</b> [Snehit Vaddi](https://www.linkedin.com/in/snehitvaddi/)<br>
<b>@Email:</b> (v.snehith999@gmail.com) 

<br>
If you face any problem, kindly raise an issue

### 🔗 References:
 - Mariusz Bojarski, Davide Del Testa, Daniel Dworakowski, Bernhard Firner, Beat Flepp, Prasoon Goyal, Lawrence D. Jackel, Mathew Monfort, Urs Muller, Jiakai Zhang, Xin Zhang, Jake Zhao, Karol Zieba. [End to End Learning for Self-Driving Cars](https://arxiv.org/abs/1604.07316)
 - [Behavioral Cloning Project](https://github.com/udacity/CarND-Behavioral-Cloning-P3) 
 - This implementation also took a lot of inspiration from the Sully Chen github repository: https://github.com/SullyChen/Autopilot-TensorFlow  






