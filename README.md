# Getting-and-Cleaning-Data-Course-Project
This is the project submission for the Getting and Cleaning Data course project. The submission contains follow files:

1. Souce data "getdata_dataset.zip"
2. Extracted source data "UCI HAR Dataset" folder
3. This ReadMe file
4. The CodeBook file that explains the data cleaning procedure
4. The R code "run_analysis.R"
5. The generated tidy data file

The "run_analysis.R" code does following things:

1. Download the dataset if it's not available in the working directory.
2. Load the activity and feature data
3. Load the training and test dataset, keep only mean and standard deviation
4. Load the activity and subject data for each dataset and merge those columns
5. Merge the two dataset
6. Convert the activity and subject columns into factors
7. Create the tidy dataset that has the mean value for each variable by subject and activity and write the data into tidy.txt