# Association-between-IDO2-and-Lactic-Acid-
Objective: Analyze the association between IDO2 and Lactic Acid. Lactic Acid (a.k.a. Lactate) is a by-product of anaerobic metabolism, or metabolism when there is not sufficient oxygen present to support aerobic metabolism. 

Hypothesis: Elevated levels of IDO2 are associated with elevated levels of lactic acid. 

Data set: The dataset contains 43 neonate patients for which IDO2 was calculated. There are a total of 2106 lactic acid measurements. There are two types of data files contained. The first is a csv for the lactic acid data (lactic_acid_data.csv). This contains all lactic acid measurements for all of the patients. The data fields are as follows:

lactic_acid_data.csv
timestamp - timestamp of the lactic acid measurement
patient_id - unique patient_id for the measurement
lactic_acid - lactic acid measurements in mmol/L. There are more than one measurement per patient.

The second type of data file are IDO2 files for each patient. The file name is ido2_data_"patient_id".csv which matches the patient_id field in the lactic_acid_data.csv

The IDO2 data file fields are as follows:
timestamp - timestamp of each IDO2 data point
ido2 - IDO2 value which ranges from 0 to 100. Missing values are empty. 
