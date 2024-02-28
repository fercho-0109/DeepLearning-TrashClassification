# Trash-Classification-using-ML-tools

Code developed for "A. Marino, - Trash Clasification using Convolutional Neural networks".  
Master's student "Calabria University".  
For any questions or suggestions write to alexismarino0109@gmail.com

# Sumary.
This repository contains a machine learning project showcasing the application of convolutional neural networks for the accurate classification of six distinct trash categories: "Paper, Cardboard, Glass, Metal, Plastic, and Common trash." The model achieves impressive performance metrics, with precision at 97%, recall at 95%, and an overall accuracy of 81%. The project was meticulously developed in Jupyter using Python, with Tensorflow and Keras serving as the primary libraries.  
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
- Once installed clone this repository using the  command prompt and the code: git clone https://github.com/fercho-0109/TrashClassification/tree/main   
**Environment creation** 
- Open the command prompt and go to the directory TrashClassification: cd TrashClassification
- Create the environment using: python -m venv TrashCassification
- Activate the environment using: .\TrashCassification\Scripts\activate
- Install ipykernel using: pip install ipykernel
- then use: python -m ipykernel --name=TrashCassification
- Now associate the environment with a jupyter notebook. So open jupyter using: jupyter notebook, and select TrashCassification directory. Then associate the environment as show in the image
![image](https://github.com/fercho-0109/TrashClassification/assets/40362695/2b853119-4011-4c9b-8141-3a8a88e539e5)
### 3. How to install Tensorflow for Deep Learning 
!pip install tensorflow opencv-python matplotlib scikit-learn. **this line is already included in the code** 

## Classes 
![image](https://github.com/fercho-0109/TrashClassification/assets/40362695/2e38a2a8-7e9a-4ae7-bd94-83a14d592f07)
0. cardboard 
1. glass
2. metal,
3. paper,
4. plastic
5. trash 


# Simulations 
### For Matlab Simulation  
Download the respective folder called Matlab_simulation, Then for:
- Tracking problem: run "**Tracking_using_dynmaic_lin.m**" for Dynamic linearization
### For Quanser Simulation using the Qbot2e Digital Twin.
Download the respective folder called Quanser_simulation. Then, open the Quanser interactive labs and select Qbot 2e.

- Setup the position of the robot, go to Options - Change reset location - choose x=-0.25, y=-1.75, rotation=180 deg
- First, run "**Main_tracking_using_dyn_lin_Quanser.m**". To configure the parameters.
- Second, open and run the Simulink file "**Tracking_with_dynamic_lin.slx**" Then, the robot in the simulator should start to move and follow the trajectory that is the red line in the environment. If the connection with the simulator fails, close the simulator and open it again.

# Example 









  


