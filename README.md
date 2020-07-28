# Week-4-Getting-and-Cleaning-Data

The associated script, "run_analysis.R" does the following.

1. Downloads the data set "UCI Har Dataset".

2. Assigns variables to each piece of data where:
  features is associated with the features file.
  activities is associated with the activity_labels file.
  subject_test is associated with the subject_test file.
  x_test is associated with the x_test file.
  y_test is associated with the y_test file.
  subject_train is associated with the subject_train file
  y_train is associated with the y_train file.
  
3. The training and test sets are then merged, with X corresponding to x_train and x_test and Y corresponding to y_train and y_test. Subject combines the subject_train and subject_test sets, and all three are combined into merged_data.

4. The mean and std dev is extracted for each measurement.

5. The activities are given descriptive names within the data set.

6. The data variables are also gven descriptive names.

7. A second, tidy data set is generated as the text file final_data.
