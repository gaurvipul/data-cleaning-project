# Getting and Cleaning Data Project

##Files

### Data File

The data is to be obtained from following link:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

### R Script: run_analysis.R

Program flow details: 

as shared in the CodeBook.


## How To Run

- Extract the data file into the R working directory and you'll obtain folder named "UCI HAR Dataset"
- Put the run_analysis.R script into the R working directory
- from R command line run: source "run_analysis.R" 

This will generate following output:

```
[run_analysis.R] Getting and Cleaning data - Project Week 3 
[run_analysis.R] --- 
[run_analysis.R] Run analysis now 
[run_analysis.R] Reading datasets 
[run_analysis.R] Getting data from  ./UCI HAR Dataset/test 
[run_analysis.R]   reading features... 
[run_analysis.R]   reading activities... 
[run_analysis.R]   reading subjects... 
[run_analysis.R] Getting data from  ./UCI HAR Dataset/train 
[run_analysis.R]   reading features... 
[run_analysis.R]   reading activities... 
[run_analysis.R]   reading subjects... 
[run_analysis.R] Joining datasets. 
[run_analysis.R] Saving clean data to: ./UCI HAR Dataset/tidy_data.txt 
```

## Cleaned Data

The resulting clean dataset is saved at './UCI HAR Dataset/tidy_data.txt' where '.' is the R working directory.
