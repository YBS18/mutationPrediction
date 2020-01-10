## Mutation Prediction

### Data
preparetoClassify.csv file includes dataset with labels and used for training of model. Around 4500 data.
allResults.txt includes mutations with features from ELASPIC this dataset is for prediction.

### Dependencies
Pandas
Numpy
Matplotlib
XGBoost
scikit-learn

### Objective
This project was done to implement a machine learning model to predict type of mutations.ELASPIC was used to extract features from INTACT mutation interaction dataset.

### Elaspic
http://elaspic.kimlab.org/

### Intact Dataset
https://www.ebi.ac.uk/intact/resources/datasets#mutationDs

### Output
Output is in the form "1	ENST00000002596.F89Y" leftmost part is predicted class right part is protein and its mutation. Output is in the file "noeff+incvsdisruptiveV2.txt"
