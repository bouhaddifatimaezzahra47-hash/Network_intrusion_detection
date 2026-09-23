# Network_intrusion_detection

A hybrid network intrusion detection system built with CICIDS2017, combining supervised machine learning and unsupervised anomaly detection to identify known and potentially unseen attacks, with data preprocessing, feature selection, data splitting, feature scaling, hyperparameter tuning, and model evaluation.



## Built with:
  - programming language : Python
  - Data manipulation and analysis : Pandas and Numpy
  - supervised model : Scikit-learn(random-forest)
  - unsuoervised model : TensorFlow (auotencoder)
  - Borderline-SMOTE :Imbalanced-learn
  - Data visualization : Matplotlib

    
## DATASET:
 - source: https://www.unb.ca/cic/datasets/ids-2017.html
 - Description of dataset: CICIDS2017 dataset contains benign and the most up-to-date common attacks, which resembles the true real-                             world data (PCAPs). It also includes the results of the network traffic analysis using CICFlowMeter with                              labeled flows based on the time stamp, source, and destination IPs, source and destination ports,
                            protocols and attack (CSV files).
   
   [2026-2027 _ 2027-2028 _ Office of International Education.pdf](https://github.com/user-attachments/files/32579859/2026-2027._.2027-2028._.Office.of.International.Education.pdf)



   <img width="522" height="339" alt="Screenshot 2026-09-23 21 30 44" src="https://github.com/user-attachments/assets/de6546d0-815d-40eb-835a-9f51827fbd7e" />



## Models Results :

### Random Forest Metrics:
   - Accuracy/ F1 score /precision/Recall:
      <img width="348" height="92" alt="Screenshot 2026-09-23 21 34 10" src="https://github.com/user-attachments/assets/e053d5f4-bce3-4fac-bae0-6966dc243422" />

   - confusion metrics:
     <img width="441" height="335" alt="Screenshot 2026-09-23 21 32 33" src="https://github.com/user-attachments/assets/c7aa0a31-4183-46f5-bb5e-0766f1628713" />

### Autoencoder :
The limited performance is mainly related to feature selection. A subset of relevant features was used to optimize memory and computational resources in Google Colab, which may have reduced the model's ability to detect some attack patterns.

<img width="320" height="92" alt="Screenshot 2026-09-23 21 35 52" src="https://github.com/user-attachments/assets/4c109f7c-9058-4e12-bdd2-13402d8d7259" />




    
   
