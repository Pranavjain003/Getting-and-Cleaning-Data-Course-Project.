# CodeBook

## Overview
This CodeBook describes the data, variables, and transformations applied in the `run_analysis.R` script to clean and prepare the dataset.

## Variables

- `subject`: ID of the participant.
- `activity`: Type of activity performed by the participant.
- All other variables represent mean and standard deviation measurements from accelerometer and gyroscope signals.

## Transformations
1. **Merging Datasets**: The training and test datasets were merged to create a single dataset.
2. **Extracting Mean and Standard Deviation**: Only measurements of mean and standard deviation for each measurement were extracted.
3. **Descriptive Activity Names**: Activity names were added to the dataset based on activity codes.
4. **Labeling Variables**: Variables were renamed for better readability:
    - "Acc" -> "Accelerometer"
    - "Gyro" -> "Gyroscope"
    - "BodyBody" -> "Body"
    - "Mag" -> "Magnitude"
    - "t" prefix -> "Time"
    - "f" prefix -> "Frequency"
5. **Final Tidy Data Set**: A second dataset was created with the average of each variable for each activity and subject, saved as `FinalData.txt`.

## Data Source
Data for this project was obtained from:
[Human Activity Recognition Using Smartphones Dataset](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)
