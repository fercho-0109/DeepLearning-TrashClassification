# Trash-Classification-using-ML-tools

Code developed for "A. Marino, - Trash Clasification using Convolutional Neural networks".  
Master's student "Calabria University".  
For any questions or suggestions write to alexismarino0109@gmail.com

# Sumary.
This repository contains a machine learning project showcasing the application of convolutional neural networks for the accurate classification of six distinct trash categories: "paper, cardboard, glass, metal, plastic, and common trash." The model achieves impressive performance metrics, with precision at 97%, recall at 95%, and an overall accuracy of 81%. The project was meticulously developed in Jupyter using Python, with Tensorflow and Keras serving as the primary libraries.  
The Dataset was obtained from the following dataset repositories  
https://www.kaggle.com/datasets/sumn2u/garbage-classification-v2  
https://github.com/garythung/trashnet

# Get started from scratch to use this ML model
### 1. Install Python and Jupyter with Anaconda  
https://www.anaconda.com/download  
Please, make sure that you check Add Anaconda3 to the system PATH when you install the program.
To check, open the command prompt and run: jupyter notebook.  
### 2. Environment creation workflow and Git install
https://git-scm.com/download/win  
- Install the 64-bit Git for Windows
- Once installed clone this repository using the  command prompt and : git clone ........


# Prerequisites
- The code was created and tested on the Matlab/Simulink 2023a environment
- Install Quanser interactive labs "Qlabs" (https://es.mathworks.com/matlabcentral/fileexchange/123860-quanser-interactive-labs-for-matlab). This requires a license to get access to the digital twins 
# File description
The repository contains two main folders  
1. **Matlab-simulation**: This folder contains a replication of the paper [[1](https://ieeexplore.ieee.org/document/9956741)] using Quanser enviroment. This is implemented using different linearization techniques according to the paper which is "Dynamic feedback linearization". Moreover, it contains the Matlab files to run the control. 
2. **Quanser-simulation**: This folder contains a replication of the paper [[1](https://ieeexplore.ieee.org/document/9956741)] as well, but this time using the Qbot 2e Digital Twin provided by Quanser.
### Bibliography  
[1] Cristian Tiriolo, Giuseppe Franzè, and Walter Lucia. An obstacle-avoidance receding horizon control scheme for constrained differential-drive robot via dynamic feedback linearization. In 2023 American Control Conference (ACC), pages 1116–1121, 2023.

# Simulations 
### For Matlab Simulation  
Download the respective folder called Matlab_simulation, Then for:
- Tracking problem: run "**Tracking_using_dynmaic_lin.m**" for Dynamic linearization
### For Quanser Simulation using the Qbot2e Digital Twin.
Download the respective folder called Quanser_simulation. Then, open the Quanser interactive labs and select Qbot 2e.

- Setup the position of the robot, go to Options - Change reset location - choose x=-0.25, y=-1.75, rotation=180 deg
- First, run "**Main_tracking_using_dyn_lin_Quanser.m**". To configure the parameters.
- Second, open and run the Simulink file "**Tracking_with_dynamic_lin.slx**" Then, the robot in the simulator should start to move and follow the trajectory that is the red line in the environment. If the connection with the simulator fails, close the simulator and open it again.

# Example to run an experiment  
**"Tracking Problem using Dynamic linearization"**
### Matlab simulation 
1. Download the folder. 
2. Run the Matlab file  "**Tracking_using_dynmaic_lin.m**"
3. The simulation should start showing the following result  
![image](https://github.com/fercho-0109/RHC-Tracking-Trajectory-with-Obstacle-Avoidance/assets/40362695/9da97de6-8f37-4604-bd6f-a36ef1451159)
### Quanser simulation
1. Download the folder
2. Open the Quanser interactive labs and select Qbot 2e.
3. Setup the position of the robot in the virtual environment Qlab, go to Options - Change reset location - choose x=-0.25, y=-1.75, rotation=180 deg
4. Run the Matlab file "**Main_tracking_using_dyn_lin_Quanser.m**"
5. Open and Run the Simulink file "**Tracking_with_dynamic_lin.slx**"
6. The Qbot 2e should start to move following the reference trajectory "red line"  
![image](https://github.com/PreCyseGroup/RHC-Tracking-Trajectory-with-Obstacle-Avoidance/assets/40362695/855b62e5-6ebd-4bf2-a85c-3464a9948a70)







  


