# Human Activity Recognition (HAR)

In this repository, we explore issues related to human activity recognition (HAR) using both deep learning and machine learning algorithms. 
The dataset employed for this project originates from the UCI public dataset.


## UCI HAR Dataset

The folder named `UCI HAR Dataset` comprises both the raw sensor data and feature data for all 60 participants. 
You can obtain the data from the [UCI repository](https://archive.ics.uci.edu/dataset/240/human+activity+recognition+using+smartphones). 

The dataset has been divided into training and testing subsets. The raw sensor dataset contains data collected from accelerometer and gyroscope sensors using an Android mobile device, 
stored in [UCI repository](https://archive.ics.uci.edu/dataset/240/human+activity+recognition+using+smartphones). 
The features dataset consists of 561 features derived from the raw sensor data.

The UCI dataset is an activity recognition data set built from the recordings of 30 subjects performing basic activities and postural transitions while carrying a waist-mounted smartphone with embedded inertial sensors.
- Number of participants: 30
- Age: 19-48
- Number of activities: 6
- Smartphone used: Samsung Galaxy S II (on the waist)
- Sample frequency: 50Hz - sliding windows of 2.56 sec and 50% overlap (128 readings/window)
- Sensor Signals: 3-axis accelerometer and 3 axis gyroscopes
- Labels: manually by video-recorded
- The obtained dataset has been partitioned into two sets: 70% of the volunteers was selected for generating the training data and 30% the test data. 

Six activities were performed
```
1 WALKING
2 WALKING_UPSTAIRS
3 WALKING_DOWNSTAIRS
4 SITTING
5 STANDING
6 LAYING
```

## Analysis Scripts
Notebook | Description
-------- | ------
[UCI-Visualization] | Raw sensor data visualization
[UCI-CNN-raw-data]   | Convolutional neural network(CNN)
[UCI-KNN-features-data]   | Convolutional neural network(CNN)