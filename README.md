# DataScienceProject


1) Data Integration: We merge three files in one Pandas Dataframe. First file has biomarker_id with 0,1 numbers for each bimoraker_id. Second file is Json object with nested list and dict and has to be converted to tabular data to see patient profiles. We need to flatten “Patient_profiles “. Third file has patient_id, biomarker id and Target. To merge three files, first we merge first and third files on biomarker id. Then, the results will be merged by json file on patient id. Then, we have one file with features and Target. 
2) Data Transformation: I converted categorical data into numerical data.
3) Data Cleaning: We have missing data. Some of the columns (features) are nan. We have to remove the column if there are plenty of rows with null values. I removed columns with more than 30% missing (nan) data. Age just had around 7% missing data out of all data. So, I filled nan values of age with mean of age regarding gender and race. Other regression methods can be used for filling missing data.
4) checking Target whether is balanced or imbalanced: There are several methods (undersapmling and resampling) to balance data. Balancing can be applied both for test and train data. 
5) split data to train and test
6) Training a model like xgboost and check feature importance and Evaluation of Model (F1 score, precesion, Recall) 
7) Hyper parameter optimization



