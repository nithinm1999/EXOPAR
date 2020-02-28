# EXOPAR
In a human–robot interface, the prediction of motion, which is based on context information of a task, has the potential to improve the robustness and reliability of motion classification to control human-assisting manipulators. The electromyography (EMG) signals can be used as a control source of artificial arm after it has been processed. The objective of this work is to achieve better classification with multiple parameters using Artificial Neural Networks for  different movements of a prosthetic arm. A ANN is one of the simplest and the most important methods in pattern recognition. The proposed structure is simulated using Scikit-Learn, and satisfied results are obtained, that explains the ability of the proposed structure to recognize the movements of human arm based EMG signals and try to get specified amount of electric impulse of that predicted action.

Solution: In response, we have created the ExoPAR Glove. This glove will meet the identified needs by  
•	facilitating the creation of quantitative reports of therapeutic progress to allow for complete reimbursements,
•	Data (muscle activity and axes readings) obtained by the device is sampled, quantified and analysed , and is used as input for the Machine learning Model which is built for this specific purpose. 
•	allowing physical therapists the ability to identify and address specific deficiencies based on the predicted results of the ML model in the patient’s therapy, and  
•	thus providing solutions to enhance robotic rehabilitation for patients struggling to regain use of their hands.

--> Gesture Prediction using ANN on Myo-data.
--> Requirement
Library	    Version
Python	    ^3.5
Tensorflow	^1.1.0
Numpy	      ^1.12.0
sklearn	    ^0.18.1

--> In repo are collected dataset from Myo armband. Dataset contains only 5 gestures:

👍 - (1)
✊️ - (2)
✌️ - (3)
🤘 - (4)
🖖 - (5)

--> Training network
python3 train.py
75k iteration take about 2h on i3-6100.

--> Prediction on data from MYO armband
python3 predict.py
