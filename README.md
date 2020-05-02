# BayesianAnomalyDetection
Using PyMC3 and Bayesian Inference to Detect anomalies in electrical grids.

There are several Jupyter notebooks available in this repository:

- `Bayesian Anomaly Detection.ipynb`
  - Contains a the first analysis used with a univariate autoregressive model for predicting grid operation. The prediction is combined with a p = 0.05 hypothesis test to determine if an observed signal is anomalous. 
  - The data for this notebook can be found [here](https://drive.google.com/open?id=1TrCfPnLnR_jvMMvg2MUJNI27_QwoY6ql).
  
- 'RTLabAnomalyDetection.ipynb'
  - This notebook contains updates to `Bayesian Anomaly Detection.ipynb`
  - It is updated to work with Google Colab
  - This notebook was made for a set of data generated using a system in RT-Lab.
  - For the Google Drive integration, the data needs to be placed in the 'My Drive' Directory of Google Drive.
  - Data for this notebook can be found [here](https://drive.google.com/drive/folders/1LYQTkiCzn7PQoBX44am3L9R7KpXT2wUy?usp=sharing)
  
- `ZoneNData_Overview.ipynb`
  - This notebook does some simple plotting of the data from RTLab.

