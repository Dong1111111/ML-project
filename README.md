# ML-project
Dataset is more than 10G, hard to upload, please see the google drive link below:

Raw data: https://drive.google.com/file/d/1dy22HhSdTUvmptlS6xvbLQa9uy8zfYNa/view?usp=sharing

After pre-processing: https://drive.google.com/file/d/1kjB5euUHDg4UeTvspAGx9h9LtWLmctiG/view?usp=sharing  
& https://drive.google.com/file/d/11hBII9Fr7F9d9T32quZ3IXMnKmjvuGJQ/view?usp=sharing



All the code can run based on the number from a1-a5

a1: Seperate original dataset to 2012 and 2013, dToU and nonToU group, then seperate A-Q categories according to their income level. 
    Here only learn the price response function of group A, all the other group can use the same code.
    
a2: Calculate the average demand of all consumers by time (365 day * 48 time slot)

a3: Generate input and output data for learning network, the file name is 'trainA.mat'

a4: Train the machine learning network, including NN(a4_1), XGBoost(a4_2), and LSTM(a4_3, including 2 files), SVR(a4_4), 

a5: Calculate the paramters of price response function, including linear type (a5_1) and nonlinear type (a5_2).

*The code and required data to run the code is uploded seperately becasue the file limit is 25MB.
