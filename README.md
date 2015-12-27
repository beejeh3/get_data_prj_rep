# get_data_prj_rep
Getting and cleaning data set project assignment

1. if the data folder does not exist, create it

2. if the zip file does not exist, download "https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip"
it and unzip it.

3. install dplyr package

4. read subject_train.txt and subject_test.txt files into data tables then bind
them into a data table called subject with the column named 'subject'.

5.Read y_train.txt and y_test.txt files into data tables then bind them into a data table called activity with the column named 'activity'.

6.Read activity_labels.txt into a data table called activity_labels. 

7.Replace numeric values with descriptions of activities

8.Read X_train.txt and X_test.txt files into data tables then bind them into the data table called phone_data.

9. Read the features.txt into a data table called features.

10. Renamed the columns of phone_data in by using the the descriptions of
 the phone measurements contained in features.

11. Creates a data table that only contains column names that includes 'std' or 'mean',
    not case sensitive.

12  Bind the data tables subject, activity_list, and reduced_data
    into the data table called combined_data

13. Renames the column name 'activity_list' to 'activity'

14. creates a data table called tidy_data that is the result of
 grouping the combined_data table by subject and activity and finding the mean of each activity.

15. writes the table tidy_data to file tidy_data.txt 
