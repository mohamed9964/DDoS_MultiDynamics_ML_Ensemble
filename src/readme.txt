In this file we explain the steps to successfully run our work:
1)	Go to the following website : ‘DDoS 2019 | Datasets | Research | Canadian Institute for Cybersecurity | UNB’, you will find a button that you can click to download the download the dataset
2)	Only choose 4 files out of this dataset which are: ‘LDAP.csv’,’ MSSQL.csv’,’ UDP.csv’ and ‘UDPLag.csv’.
3)	Run the ‘Dataset_Creation.ipynb’ which is responsible of merging these files and making some data cleansing and balancing steps and then exporting a csv file named ‘final_data’ that will be used after that
4)	Run the ‘main.ipynb’ that is responsible for the preprocessing the dataset and training and testing of our models