Getting and Cleaning Data - Course Project

run_analysis.R conducts the following:
1. Downloads the dataset from web if it does not already exist in the current working directory.
2. Reads the x, y and subject train/test datasets and merges them.
3. Loads the data feature, activity info and extract columns named 'mean' and 'standard'. Also,
it modifies column names to be descriptive.
4. Extracts data by selected columns and merges x, y and subject data, alongside with replacing
y column to its name by refering activity level.
5. Generates tidyData that consists of the mean of each variable for each subject and each activity. The result can be seen in the generated textfile tidy_dataset.txt.
