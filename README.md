# CleaningData
1. Get the data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip and store it in a folder
   called data.
2. unzip the zip file into a folder 'data'
3. Check the list of files and as per the readme.txt files only some of the files are relevant for this project.
4. Read the files(train and Test files) into local variables.
5. Combine both test and train datasets into one dataset for each variables.
6. Set names for both activity and subject datasets
7. Merge the subject, activity and Features datasets into a single data set using cbind()
8. Subset the feature names
9. Read descriptive activity labels
10. Set appropriate names to the columns by using gsub() function
11. Tiny Data set is produced.
