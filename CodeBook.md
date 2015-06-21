#Course Project Code Book


##Introduction 

    Merges the training and test sets to create one data set, namely train/X_train.txt with test/X_test.txt, the result of which is a data frame.
    train/subject_train.txt with test/subject_test.txt, the result of which is  data frame with subject IDs, and train/y_train.txt with test/y_test.txt, the result of which is also a data frame with activity IDs.
    Reads features.txt and extracts only the measurements on the mean and standard deviation for each measurement. The result is a data frame.
    Finally, the script creates a 2nd, independent tidy data set with the average of each measurement for each activity and each subject. The result is saved as data_set_averages.txt.

	
##Variables

	lire1 and lire2 contain the data from the downloaded files.
	X, S and Y merge the previous datasets to further analysis.
	indices_of_good_features contains the correct names for the x_data dataset
	Finally, result contains the relevant averages which will be later stored in a .txt file.
