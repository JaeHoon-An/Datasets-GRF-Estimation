# Datasets-GRF-Estimation
Datasets for training a two-staged MLP network to estimate ground reaction force in a two-DoF point-foot robot.

[ A. Datasets for GRF estimation (First stage MLP).csv ]

 In the above CSV file, each collum denotes the following states of the robot.
 
 1: Current Position of Hip Pitch Joint
 
 2: First histroy of Position of Hip Pitch Joint
 
 3: Second histroy of Position of Hip Pitch Joint
 
 4: Current Position of Knee Pitch Joint
 
 5: First histroy of Position of Knee Pitch Joint
 
 6: Second histroy of Position of Knee Pitch Joint

 7: Current Velocity of Hip Pitch Joint
 
 8: First histroy of Velocity of Hip Pitch Joint
 
 9: Second histroy of Velocity of Hip Pitch Joint
 
 10: Current Velocity of Knee Pitch Joint
 
 11: First histroy of Velocity of Knee Pitch Joint
 
 12: Second histroy of Velocity of Knee Pitch Joint

 13: Current Torque of Hip Pitch Joint
 
 14: Current Torque of Knee Pitch Joint

 15: Current Ground Reaction Force (Ground-truth)


[ B. Datasets for Sim2Real transfer (Second stage MLP).csv ]
 
 In the above CSV file, each collum denotes the following states of the robot.

 1: Estimated Ground Reaction Force from the First Stage MLP Network
 
 2: Measured Ground Reaction Force (Ground-truth)
