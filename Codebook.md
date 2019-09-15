Code Book
This code book summarizes the results reported in the tidy.txt data in this repository.

README.txt describes the process of how publishers of URI HAR dataset did the experiment and got the data result.
The project uses six inputs from the URI HAR Dataset  
x_train.txt 
x_test.txt
y_train.txt
y_test.txt
subject_train.txt
subject_test.txt.
The training and test sets were merged extracting only mean and std to create new data sets features and activity_labels
features.txt contains variable names corresponding to the columns of x_train.txt and x_test.txt. 
Descriptive Variable Names
Accelerometer 
Gyroscope
Magnitude
Frequency
Mean
StandardDeviation 
activity_labels.txt contains the descriptive names for the activity labels from the numbers in y_train.txt and y_test.txt.
Descriptive Activity Labels
WALKING - subject was walking during the test
WALKING_UPSTAIRS - subject was walking up a staircase during the test
WALKING_DOWNSTAIRS - subject was walking down a staircase during the test
SITTING - subject was sitting during the test
STANDING - subject was standing during the test
LAYING - subject was laying down during the test





