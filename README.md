# oop-proj-unity
This repo is a starter kit tutorial of unity side using Ros# to connect rosbridge_server.  
This is a easy project to move a cube with keyboard or VR joystick.   
You need another repo for ROS (python) side to run this project.  
https://github.com/ARG-NCTU/oop-proj-unity-ros/tree/master  

Unity version: 2020.3.36

# Setup: Import the project
1. clone this repo
```
$ git clone git@github.com:ARG-NCTU/oop-proj-unity.git
```
2. Open with Unity Hub

3. Network environment setup
The network environment setup in this project shows below, if your setup different to this tutorial, remember do step 4 to change server ip setup.
![Network](/readme_img/network.png)

4. Choose the example scene at Assets/Scenes/SampleScene.unity
You can see a cube in scene with third person view.

5. Modify server ip in project (if your setup different from step 3)
![modify_ip](/readme_img/set_ip.png)

# Usage: how to run this project 
1. Before you run the project you can choose VR joy stick control or keyboard control by click check mark of script shows below. 
![choose_control](/readme_img/choose_vr_joy_or_keyboard.png)

2. Click play button to start project