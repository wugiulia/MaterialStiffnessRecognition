# MaterialStiffnessRecognition
This repository contains the code relevant for "Machine Learning Recognition Via Machine Learning" report. The code is split into two sections:

1. Data cleaning and processing: the raw data in the .txt files extracted from LabView are cleaned and processed to obtain values of stress-strain and voltage-time. With the curve-fit function, Mooney Rivlin and Power Law model are used to fit both stress-strain and voltage-time data, extracting the respective material coefficients.

2. Rigression Analysis: Linear regression, Ridge regression, Random Forest (RFR), and Support Vector Regressor (SVR) are used and compared in relating the input variables (voltage, time, and speed) with the output labels (material coefficients).
