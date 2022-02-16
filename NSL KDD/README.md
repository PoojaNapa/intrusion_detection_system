1. Download the NSL-KDD dataset from the below url.
   https://www.unb.ca/cic/datasets/nsl.html
2. Consider KDDTrain+.TXT for training and KDDTest+.TXT for testing
3. Convert the .TXT files into .csv files
4. Input the path of the dataset files in NS_IDS_Preprocessing_Visualization.ipynb to create the training and testing datasets
5. Upon the running the above file , it will create the following pickle files 
			X_train_NSL_B.pickle
			y_train_NSL_B.pickle
			X_test_NSL_B.pickle
			y_test_NSL_B.pickle
			X_train_NSL_MC.pickle
			y_train_NSL_MC.pickle
			X_test_NSL_MC.pickle
			y_test_NSL_MC.pickle
6. Now you can try running other classifier files