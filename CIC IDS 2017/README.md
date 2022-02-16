1. Download the CICIDS 2017 dataset from the below url.
   https://www.unb.ca/cic/datasets/ids-2017.html
2. It contains the below csv files 
   cic_ids2017_benign
   cic_ids2017_botnet
   cic_ids2017_bruteforce
   cic_ids2017_ddos
   cic_ids2017_dos_ddos
   cic_ids2017_infilteration
   cic_ids2017_port_scan
   cic_ids2017_web_attacks
3. Input the path of the dataset files(except benign.csv) in NS_IDS_CICID_DS_Pickle_Final.ipynb to create the training and testing datasets.
   We have removed the benign as rest of the files contained enough benign data for training. 
5. Upon the running the above file , it will create the following pickle files 
			X_train_rusb.pickle
			y_train_rusb.pickle
			X_test_rusb.pickle
			y_test_rusb.pickle
6. Now you can try running other classifier files