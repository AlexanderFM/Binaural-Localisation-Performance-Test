# Binaural-Localisation-Performance-Test
A program for collating my test results.

Program intended for use with Jupyter, Anaconda.

ProcessingAnswerFiles.ipynb will collate data from source (.csv) files. This must be run first. This will output “wheel_test_[Letter]_Results.csv”.

ComputeWheelResultDistance.ipynb Will calculate the distance between the submitted answers and the predefined correct answers and output “wheel_test_[Letter]_distances.csv”.

To change between result set A and B on Processing Answer Files, change “Test_ID=[Letter]” in block 2 and on Results Distance change top line “Test_ID=[Letter]”.

Note that ProcessingAnswerFiles will print any missing labels (answers) and stop at any duplicates to help prevent human error. It will also ignore any file names starting with the word Void.
