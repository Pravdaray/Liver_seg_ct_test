This is a repository for testing the trained model for CT liver segmentation. 
You could follow the steps below to process the database for testing

Step 1:
Run process_test_database.py file with the required path , this will create the test files

Step 2: 
Run Create_Test.py, this will give you the text file with all the test volumes 

Step 3:

Run the script for testing, seg_test.py

Now you get the npy files as results, run npy_to_volume, you get the corresponding 3D npy array of corresponding test volumes 
