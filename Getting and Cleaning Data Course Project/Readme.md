# Getting-Cleaning-Data-Course-Project
- This course project is to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis.
- The data for this project can be downloaded through the following link: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
- Full description of the data can be found here: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

# Files
- [CodeBook.md](https://github.com/parijaat007/datasciencecoursera/blob/master/Getting%20and%20Cleaning%20Data%20Course%20Project/CodeBook.md) describes the variables, the data, and any work that are performed to clean up the data.

- [run_analysis.R](https://github.com/parijaat007/datasciencecoursera/blob/master/Getting%20and%20Cleaning%20Data%20Course%20Project/run_analysis.R) contains all the coding for doing the course project, that includes downloading and unzipping the dataset that is used for this project.

- [averagedata.txt](https://github.com/parijaat007/datasciencecoursera/blob/master/Getting%20and%20Cleaning%20Data%20Course%20Project/averagedata.txt) is a written out text file from [run_analysis.R](https://github.com/parijaat007/datasciencecoursera/blob/master/Getting%20and%20Cleaning%20Data%20Course%20Project/run_analysis.R), which is the average features of each subject and each activity. Please refer to [CodeBook.md](https://github.com/parijaat007/datasciencecoursera/blob/master/Getting%20and%20Cleaning%20Data%20Course%20Project/CodeBook.md) for more explicit information.

The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data.

The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain.
