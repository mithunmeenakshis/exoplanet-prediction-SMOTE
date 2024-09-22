# exoplanet-prediction-SMOTE
In this project, I aim to classify the planetary candidates from TESS data as planet or not, and evaluating performance on balanced vs unbalanced datasets.
TESS Data has many categories for planetary candidates namely: 
FP - False Positive, 
PC - Planetary Candidate, 
KP - Known Planet, 
APC - Ambiguous Planetary Candidate, 
CP - Confirmed Planet, 
FA - False Alarm.
For this analysis, I have renamed KP and CP as 'yes' planets, and remaining as not planets for simplicity and interpretability. 
Detailed documentation about the source data can be found [here](https://exoplanetarchive.ipac.caltech.edu/docs/API_TOI_columns.html)
The dataset used for this project was retrieved  dfrom NASA Exoplanet Archive on Sep 5 2024.
Original source: [here](https://exoplanetarchive.ipac.caltech.edu/cgi-bin/TblView/nph-tblView?app=ExoTbls&config=TOI)
Kaggle dataset link: [here](https://www.kaggle.com/datasets/mithunmeenakshis/tess-exoplanet-dataset)

