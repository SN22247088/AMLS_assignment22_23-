# libraries used
Pandas, numpy as np, sklearn, PIL and matplotlib.pyplot as plt

# to run this file
# 1 - uploading the datasets and addding their respective paths
the datasets must be uploaded in the the datasets folder. The model expects the following sets: cartoon_set, cartoon_set_test, celeba and celeba_test.
It expects the following labels: "gender", "smiling", "face_shape", "eye_color"
once these files have been uploaded add the relative path/ path of each data set to it's respective path name. These are:
    #Binary Tasks
    A_train_csv = "Datasets/celeba/labels.csv"
    A_train_img = "Datasets/celeba/img/"
    A_test_csv = "Datasets/celeba_test/labels.csv"
    A_test_img = "Datasets/celeba_test/img/"

    #Multiclass Tasks
    B_train_csv = "Datasets/cartoon_set/labels.csv"
    B_train_img = "Datasets/cartoon_set/img/"
    B_test_csv = "Datasets/cartoon_set_test/labels.csv"
    B_test_img = "Datasets/cartoon_set_test/img/"

# run the main file
the main file has been divided into cell through "#%%". Run each cell individually to define the functions. 
the last two cells run the models on the train and test data that is uploaded. This takes a while and it is recommended that the two cells are run saperately as they are very computation heavy. 

# individual files
the individual files solve all 4 tasks saperately. the process to run them is the same as the main file. Upload the relevant paths to each file and hit run. 

# GitHub link: 
https://github.com/Samreen-Abbas/ML-Coursework-
