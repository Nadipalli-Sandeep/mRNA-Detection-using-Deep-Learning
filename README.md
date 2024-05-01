# mRNA-Detection-using-Deep-Learning
Designing a deep learning model that will predict degradation rates at each base of an RNA molecule using the Eterna dataset comprising over 3000 RNA molecules.
mRNA vaccines are at forefront of battling the COVID-19 pandemic and they come with limitations. The stability issue in messenger RNA (mRNA) molecules limits us to package it in a disposable syringe and distribute it around the world using the refrigerating system (nih.gov). The main challenge is to design a stable mRNA vaccine that can survive shipment around the world as a single cut can render the entire vaccine useless. The researchers have also discovered that mRNA molecules tend to degrade quickly, and, in this project, we are going to design the model to predict degradation rate that can help scientists and researchers design more stable vaccines in the future. Currently, to overcome this problem we are keeping these vaccines under intense refrigeration but that is also limited as these vaccines are available to fewer people around the world. 
![Screenshot_20240501_161751](https://github.com/Nadipalli-Sandeep/mRNA-Detection-using-Deep-Learning/assets/106082542/dc2c79d7-aae4-4578-93c1-c6aeccf874e6)

The ouput Predictions are as fololows:
![Screenshot_20240501_162754](https://github.com/Nadipalli-Sandeep/mRNA-Detection-using-Deep-Learning/assets/106082542/e76f1e14-af17-4203-98c8-1dfbf14ab076)

id_seqpos: This column contains unique identifiers for each prediction. Each identifier represents a specific RNA molecule at a particular position.

reactivity, deg_Mg_pH10, deg_Mg_50C, deg_pH10, deg_50C: These columns represent the predicted degradation rates at each base of the RNA molecule under different conditions. Each value in these columns corresponds to the predicted degradation rate at a specific base of the RNA molecule for a particular condition.

reactivity: This column predicts the degradation rate of the RNA molecule under normal conditions.

deg_Mg_pH10: This column predicts the degradation rate of the RNA molecule under conditions with magnesium at pH 10.

deg_Mg_50C: This column predicts the degradation rate of the RNA molecule under conditions with magnesium at 50 degrees Celsius.

deg_pH10: This column predicts the degradation rate of the RNA molecule under conditions without magnesium at pH 10.

deg_50C: This column predicts the degradation rate of the RNA molecule under conditions without magnesium at 50 degrees Celsius.

Each row in this table represents the predicted degradation rates for a specific RNA molecule at different positions along its sequence under various experimental conditions. These predictions are essential for understanding how stable the RNA molecule is under different circumstances, which helps in designing more stable mRNA vaccines.
