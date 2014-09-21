##Codebook
Code book for the Coursera Peer review project for Getting and cleaning data.

Source of the original data: [https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip] (https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip)

Original description: [http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)

###Variable list and descriptions
------------------------------

    Variable name    | Description
    -----------------|------------
    subject          | ID the subject who performed the activity for each window sample. Its range is  from 1 to 30.
    activity         | Activity name
    featDomain       | Feature: Time domain signal or frequency domain signal (Time or Freq)
    featInstrument   | Feature: Measuring instrument (Accelerometer or Gyroscope)
    featAcceleration | Feature: Acceleration signal (Body or Gravity)
    featVariable     | Feature: Variable (Mean or SD)
    featJerk         | Feature: Jerk signal
    featMagnitude    | Feature: Magnitude of the signals calculated using the Euclidean norm
    featAxis         | Feature: 3-axial signals in the X, Y and Z directions (X, Y, or Z)
    featCount        | Feature: Count of data points used to compute `average`
    featAverage      | Feature: Average of each variable for each activity and each subject


### List the key variables in the data table
----------------------------------------



    "subject"          "activity"         "featDomain"      
    "featAcceleration" "featInstrument"   "featJerk"        
    "featMagnitude"    "featVariable"     "featAxis"


###List of all possible features 

     featDomain featAcceleration featInstrument featJerk featMagnitude
       Time               NA      Gyroscope       NA            NA
       Time               NA      Gyroscope       NA            NA
       Time               NA      Gyroscope       NA            NA
       Time               NA      Gyroscope       NA            NA
       Time               NA      Gyroscope       NA            NA
       Time               NA      Gyroscope       NA            NA
       Time               NA      Gyroscope       NA     Magnitude
       Time               NA      Gyroscope       NA     Magnitude
       Time               NA      Gyroscope     Jerk            NA
       Time               NA      Gyroscope     Jerk            NA
       Time               NA      Gyroscope     Jerk            NA
       Time               NA      Gyroscope     Jerk            NA
       Time               NA      Gyroscope     Jerk            NA
       Time               NA      Gyroscope     Jerk            NA
       Time               NA      Gyroscope     Jerk     Magnitude
       Time               NA      Gyroscope     Jerk     Magnitude
       Time             Body  Accelerometer       NA            NA
       Time             Body  Accelerometer       NA            NA
       Time             Body  Accelerometer       NA            NA
       Time             Body  Accelerometer       NA            NA
       Time             Body  Accelerometer       NA            NA
       Time             Body  Accelerometer       NA            NA
       Time             Body  Accelerometer       NA     Magnitude
       Time             Body  Accelerometer       NA     Magnitude
       Time             Body  Accelerometer     Jerk            NA
       Time             Body  Accelerometer     Jerk            NA
       Time             Body  Accelerometer     Jerk            NA
       Time             Body  Accelerometer     Jerk            NA
       Time             Body  Accelerometer     Jerk            NA
       Time             Body  Accelerometer     Jerk            NA
       Time             Body  Accelerometer     Jerk     Magnitude
       Time             Body  Accelerometer     Jerk     Magnitude
       Time          Gravity  Accelerometer       NA            NA
       Time          Gravity  Accelerometer       NA            NA
       Time          Gravity  Accelerometer       NA            NA
       Time          Gravity  Accelerometer       NA            NA
       Time          Gravity  Accelerometer       NA            NA
       Time          Gravity  Accelerometer       NA            NA
       Time          Gravity  Accelerometer       NA     Magnitude
       Time          Gravity  Accelerometer       NA     Magnitude
       Freq               NA      Gyroscope       NA            NA
       Freq               NA      Gyroscope       NA            NA
       Freq               NA      Gyroscope       NA            NA
       Freq               NA      Gyroscope       NA            NA
       Freq               NA      Gyroscope       NA            NA
       Freq               NA      Gyroscope       NA            NA
       Freq               NA      Gyroscope       NA     Magnitude
       Freq               NA      Gyroscope       NA     Magnitude
       Freq               NA      Gyroscope     Jerk     Magnitude
       Freq               NA      Gyroscope     Jerk     Magnitude
       Freq             Body  Accelerometer       NA            NA
       Freq             Body  Accelerometer       NA            NA
       Freq             Body  Accelerometer       NA            NA
       Freq             Body  Accelerometer       NA            NA
       Freq             Body  Accelerometer       NA            NA
       Freq             Body  Accelerometer       NA            NA
       Freq             Body  Accelerometer       NA     Magnitude
       Freq             Body  Accelerometer       NA     Magnitude
       Freq             Body  Accelerometer     Jerk            NA
       Freq             Body  Accelerometer     Jerk            NA
       Freq             Body  Accelerometer     Jerk            NA
       Freq             Body  Accelerometer     Jerk            NA
       Freq             Body  Accelerometer     Jerk            NA
       Freq             Body  Accelerometer     Jerk            NA
       Freq             Body  Accelerometer     Jerk     Magnitude
       Freq             Body  Accelerometer     Jerk     Magnitude
