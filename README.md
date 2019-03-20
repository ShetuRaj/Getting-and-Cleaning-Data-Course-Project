# Getting-and-Cleaning-Data-Course-Project
This Repository was made as a part of the Peer-graded assignment in Week 4.

In case you haven't downloaded the data set,below are the steps to guide you to do so:-
* Firstly, download and unzip the data file into your R working directory.
* Secondly, download the R source code into your R working directory.
* Finally, execute R source code to generate tidy data file.

The **R script** and **run_analysis.R** does the following:
* Loads both the training and test datasets, keeping only those columns which reflect a mean or standard deviation
* Loads the activity and subject data for each dataset, and merges those columns with the dataset
* Merges the two datasets
* Converts the activity and subject columns into factors
* Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.

The end result is shown in the file **tidy.txt**.
