# Codebook

## Data Set Information:

The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data. 

The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain.

Check the README.txt file for further details about this dataset. 

A video of the experiment including an example of the 6 recorded activities with one of the participants can be seen in the following link: [Web Link]

An updated version of this dataset can be found at [Web Link]. It includes labels of postural transitions between activities and also the full raw inertial signals instead of the ones pre-processed into windows.

## Attribute Information:

For each record in the dataset it is provided: 
- Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration. 
- Triaxial Angular velocity from the gyroscope. 
- A 561-feature vector with time and frequency domain variables. 
- Its activity label. 
- An identifier of the subject who carried out the experiment.

## Variables

| Subject | subject identification                                      
 [2] "Activity"                                     
 [3] "timeBodyAcceleration-mean()-X"                
 [4] "timeBodyAcceleration-mean()-Y"                
 [5] "timeBodyAcceleration-mean()-Z"                
 [6] "timeBodyAcceleration-std()-X"                 
 [7] "timeBodyAcceleration-std()-Y"                 
 [8] "timeBodyAcceleration-std()-Z"                 
 [9] "timeGravityAcceleration-mean()-X"             
[10] "timeGravityAcceleration-mean()-Y"             
[11] "timeGravityAcceleration-mean()-Z"             
[12] "timeGravityAcceleration-std()-X"              
[13] "timeGravityAcceleration-std()-Y"              
[14] "timeGravityAcceleration-std()-Z"              
[15] "timeBodyAccelerationJerk-mean()-X"            
[16] "timeBodyAccelerationJerk-mean()-Y"            
[17] "timeBodyAccelerationJerk-mean()-Z"            
[18] "timeBodyAccelerationJerk-std()-X"             
[19] "timeBodyAccelerationJerk-std()-Y"             
[20] "timeBodyAccelerationJerk-std()-Z"             
[21] "timeBodyGyroscope-mean()-X"                   
[22] "timeBodyGyroscope-mean()-Y"                   
[23] "timeBodyGyroscope-mean()-Z"                   
[24] "timeBodyGyroscope-std()-X"                    
[25] "timeBodyGyroscope-std()-Y"                    
[26] "timeBodyGyroscope-std()-Z"                    
[27] "timeBodyGyroscopeJerk-mean()-X"               
[28] "timeBodyGyroscopeJerk-mean()-Y"               
[29] "timeBodyGyroscopeJerk-mean()-Z"               
[30] "timeBodyGyroscopeJerk-std()-X"                
[31] "timeBodyGyroscopeJerk-std()-Y"                
[32] "timeBodyGyroscopeJerk-std()-Z"                
[33] "timeBodyAccelerationMagnitude-mean()"         
[34] "timeBodyAccelerationMagnitude-std()"          
[35] "timeGravityAccelerationMagnitude-mean()"      
[36] "timeGravityAccelerationMagnitude-std()"       
[37] "timeBodyAccelerationJerkMagnitude-mean()"     
[38] "timeBodyAccelerationJerkMagnitude-std()"      
[39] "timeBodyGyroscopeMagnitude-mean()"            
[40] "timeBodyGyroscopeMagnitude-std()"             
[41] "timeBodyGyroscopeJerkMagnitude-mean()"        
[42] "timeBodyGyroscopeJerkMagnitude-std()"         
[43] "frequencyBodyAcceleration-mean()-X"           
[44] "frequencyBodyAcceleration-mean()-Y"           
[45] "frequencyBodyAcceleration-mean()-Z"           
[46] "frequencyBodyAcceleration-std()-X"            
[47] "frequencyBodyAcceleration-std()-Y"            
[48] "frequencyBodyAcceleration-std()-Z"            
[49] "frequencyBodyAccelerationJerk-mean()-X"       
[50] "frequencyBodyAccelerationJerk-mean()-Y"       
[51] "frequencyBodyAccelerationJerk-mean()-Z"       
[52] "frequencyBodyAccelerationJerk-std()-X"        
[53] "frequencyBodyAccelerationJerk-std()-Y"        
[54] "frequencyBodyAccelerationJerk-std()-Z"        
[55] "frequencyBodyGyroscope-mean()-X"              
[56] "frequencyBodyGyroscope-mean()-Y"              
[57] "frequencyBodyGyroscope-mean()-Z"              
[58] "frequencyBodyGyroscope-std()-X"               
[59] "frequencyBodyGyroscope-std()-Y"               
[60] "frequencyBodyGyroscope-std()-Z"               
[61] "frequencyBodyAccelerationMagnitude-mean()"    
[62] "frequencyBodyAccelerationMagnitude-std()"     
[63] "frequencyBodyAccelerationJerkMagnitude-mean()"
[64] "frequencyBodyAccelerationJerkMagnitude-std()" 
[65] "frequencyBodyGyroscopeMagnitude-mean()"       
[66] "frequencyBodyGyroscopeMagnitude-std()"        
[67] "frequencyBodyGyroscopeJerkMagnitude-mean()"   
[68] "frequencyBodyGyroscopeJerkMagnitude-std()"  

## Citation Request:

Davide Anguita, Alessandro Ghio, Luca Oneto, Xavier Parra and Jorge L. Reyes-Ortiz. A Public Domain Dataset for Human Activity Recognition Using Smartphones. 21th European Symposium on Artificial Neural Networks, Computational Intelligence and Machine Learning, ESANN 2013. Bruges, Belgium 24-26 April 2013.
