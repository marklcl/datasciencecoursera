This is the Readme Markdown file providing instructions on how to use the run_analysis R Script with the data from the UCI HAR (Human Activity Recognition) experiment. My name is Mark Lim and I'm doing this as part of my course for the Coursera Data Science Program. I'm using a Mac and hence the info here are related to Mac. if you are using Windows, please take note of the differences between Mac and Windows. 

Step 1. Download the zip file from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

Step 2. Unzip it into a folder on your local directory where you plan to use as your working directory
    
Step 3. Go to terminal and type pwd to find out which directory your files are in. (mine is /Users/Mark/datasciencecoursera/Course3 on my Mac as this is where my files are on my local drive) for windows users, the file directory listing will be different. (e.g. C:\\users\...)

Step 4. Put run_analysis.R (which consists of the 5 steps) into unzip folder on your local directory (mine is /Users/Mark/datasciencecoursera/Course3/UCI HAR Dataset/). Y

Step 5. In RStudio: setwd("/Users/Mark/datasciencecoursera/Course3/UCI HAR Dataset/"). This is to set the working directory to where your files are.  
    
Step 6. Type source("run_analysis.R")

Step 7. In order to import the new tidy data, type data <- read.table("tidy_data.txt") to read the file and assign to data. It is 180x68 because there are 30 subjects and 6 activities, thus "for each activity and each subject" means 30 * 6 = 180 rows. Note that the provided R script has no assumptions on numbers of records, only on locations of files.
