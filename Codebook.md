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

 [1] "Subject" - subject identification                                      
 [2] "Activity" - measured activity                      
 [3] "timeBodyAcceleration-mean()-X" - mean time body acceleration in X direction                  
 [4] "timeBodyAcceleration-mean()-Y" - mean time body acceleration in Y direction
 [5] "timeBodyAcceleration-mean()-Z" - mean time body acceleration in Z direction                 
 [6] "timeBodyAcceleration-std()-X" - stdev time body acceleration in X direction                  
 [7] "timeBodyAcceleration-std()-Y" - stdev time body acceleration in Y direction                  
 [8] "timeBodyAcceleration-std()-Z" - stdev time body acceleration in Z direction                  
 [9] "timeGravityAcceleration-mean()-X"  - mean time gravity acceleration in X direction            
[10] "timeGravityAcceleration-mean()-Y"  - mean time gravity acceleration in Y direction              
[11] "timeGravityAcceleration-mean()-Z"  - mean time gravity acceleration in Z direction             
[12] "timeGravityAcceleration-std()-X" - stdev time gravity acceleration in X direction              
[13] "timeGravityAcceleration-std()-Y" - stdev time gravity acceleration in Y direction              
[14] "timeGravityAcceleration-std()-Z" - stdev time gravity acceleration in Z direction              
[15] "timeBodyAccelerationJerk-mean()-X" - mean time body acceleration jerk in X direction             
[16] "timeBodyAccelerationJerk-mean()-Y" - mean time body acceleration jerk in Y direction             
[17] "timeBodyAccelerationJerk-mean()-Z" - mean time body acceleration jerk in Z direction             
[18] "timeBodyAccelerationJerk-std()-X" - stdev time body acceleration jerk in X direction             
[19] "timeBodyAccelerationJerk-std()-Y" - stdev time body acceleration jerk in Y direction              
[20] "timeBodyAccelerationJerk-std()-Z" - stdev time body acceleration jerk in Z direction              
[21] "timeBodyGyroscope-mean()-X" - mean time body gyroscope in X direction                   
[22] "timeBodyGyroscope-mean()-Y" - mean time body gyroscope in Y direction                    
[23] "timeBodyGyroscope-mean()-Z" - mean time body gyroscope in Z direction                    
[24] "timeBodyGyroscope-std()-X" - stdev time body gyroscope in X direction                     
[25] "timeBodyGyroscope-std()-Y" - stdev time body gyroscope in Y direction                     
[26] "timeBodyGyroscope-std()-Z" - stdev time body gyroscope in Z direction                     
[27] "timeBodyGyroscopeJerk-mean()-X" - mean time body gyroscope jerk in X direction                
[28] "timeBodyGyroscopeJerk-mean()-Y" - mean time body gyroscope jerk in Y direction                
[29] "timeBodyGyroscopeJerk-mean()-Z" - mean time body gyroscope jerk in Z direction                
[30] "timeBodyGyroscopeJerk-std()-X" - stdev time body gyroscope jerk in X direction                  
[31] "timeBodyGyroscopeJerk-std()-Y" - stdev time body gyroscope jerk in Y direction                 
[32] "timeBodyGyroscopeJerk-std()-Z" - stdev time body gyroscope jerk in Z direction                 
[33] "timeBodyAccelerationMagnitude-mean()" - mean time body acceleration magnitude     
[34] "timeBodyAccelerationMagnitude-std()" - stdev time body acceleration magnitude
[35] "timeGravityAccelerationMagnitude-mean()" - mean time gravity acceleration magnitude       
[36] "timeGravityAccelerationMagnitude-std()" - stdev time gravity acceleration magnitude        
[37] "timeBodyAccelerationJerkMagnitude-mean()" - mean time body acceleration jerk magnitude 
[38] "timeBodyAccelerationJerkMagnitude-std()" - stdev time body acceleration jerk magnitude   
[39] "timeBodyGyroscopeMagnitude-mean()" - mean time body gyroscope magnitude             
[40] "timeBodyGyroscopeMagnitude-std()" - stdev time body gyroscope magnitude              
[41] "timeBodyGyroscopeJerkMagnitude-mean()" - mean time body gyroscope jerk magnitude        
[42] "timeBodyGyroscopeJerkMagnitude-std()" - stdev time body gyroscope jerk magnitude         
[43] "frequencyBodyAcceleration-mean()-X" - mean frequency body acceleration in X direction                 
[44] "frequencyBodyAcceleration-mean()-Y" - mean frequency body acceleration in Y direction            
[45] "frequencyBodyAcceleration-mean()-Z" - mean frequency body acceleration in Z direction           
[46] "frequencyBodyAcceleration-std()-X" - stdev frequency body acceleration in X direction            
[47] "frequencyBodyAcceleration-std()-Y" - stdev frequency body acceleration in Y direction             
[48] "frequencyBodyAcceleration-std()-Z" - stdev frequency body acceleration in Z direction             
[49] "frequencyBodyAccelerationJerk-mean()-X" - mean frequency body acceleration jerk in X direction
[50] "frequencyBodyAccelerationJerk-mean()-Y" - mean frequency body acceleration jerk in Y direction        
[51] "frequencyBodyAccelerationJerk-mean()-Z" - mean frequency body acceleration jerk in Z direction     
[52] "frequencyBodyAccelerationJerk-std()-X" - stdev frequency body acceleration jerk in X direction         
[53] "frequencyBodyAccelerationJerk-std()-Y" - stdev frequency body acceleration jerk in Y direction         
[54] "frequencyBodyAccelerationJerk-std()-Z" - stdev frequency body acceleration jerk in Z direction         
[55] "frequencyBodyGyroscope-mean()-X" - mean frequency body gyroscope in X direction               
[56] "frequencyBodyGyroscope-mean()-Y" - mean frequency body gyroscope in Y direction               
[57] "frequencyBodyGyroscope-mean()-Z" - mean frequency body gyroscope in Z direction              
[58] "frequencyBodyGyroscope-std()-X" - stdev frequency body gyroscope in X direction               
[59] "frequencyBodyGyroscope-std()-Y" - stdev frequency body gyroscope in Y direction                
[60] "frequencyBodyGyroscope-std()-Z" - stdev frequency body gyroscope in Z direction                
[61] "frequencyBodyAccelerationMagnitude-mean()" - mean frequency body acceleration magnitude
[62] "frequencyBodyAccelerationMagnitude-std()" - stdev frequency body acceleration magnitude      
[63] "frequencyBodyAccelerationJerkMagnitude-mean()" - mean frequency body acceleration jerk magnitude
[64] "frequencyBodyAccelerationJerkMagnitude-std()" - stdev frequency body acceleration jerk magnitude
[65] "frequencyBodyGyroscopeMagnitude-mean()" - mean frequency body gyroscope magnitude       
[66] "frequencyBodyGyroscopeMagnitude-std()" - stdev frequency body gyroscope magnitude        
[67] "frequencyBodyGyroscopeJerkMagnitude-mean()" - mean frequency body gyroscope jerk magnitude   
[68] "frequencyBodyGyroscopeJerkMagnitude-std()" - stdev frequency body gyroscope jerk magnitude

## Citation Request:

Davide Anguita, Alessandro Ghio, Luca Oneto, Xavier Parra and Jorge L. Reyes-Ortiz. A Public Domain Dataset for Human Activity Recognition Using Smartphones. 21th European Symposium on Artificial Neural Networks, Computational Intelligence and Machine Learning, ESANN 2013. Bruges, Belgium 24-26 April 2013.
