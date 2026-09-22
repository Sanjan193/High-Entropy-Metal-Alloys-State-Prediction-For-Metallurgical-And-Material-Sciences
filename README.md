# High Entropy Metal Alloys State Prediction For Metallurgical And Material Sciences
## Overview

The High Entropy Alloys(HEA) data available in the literature provides an opportunity to use Machine Learning (ML) algorithms for identifying the composition space or predicting the phase formation for a particular composition. ML is used in many fields of material science like energy applications.
## About The Data
The initial dataset contains collection of 1,361 High Entropy Alloy records containing elemental composition, thermodynamic properties, processing parameters, and microstructural and enthalpy related information. I used the dataset to investigate alloy-state classification through exploratory analysis and comparative machine learning, with and without PCA (To Explore about the Dataset and full article about the research [Click Here](https://www.sciencedirect.com/science/article/pii/S2352340921006302?via%3Dihub)) and got overall increased models accuracy later.
## About The Project
  1. [Data Cleaning](Notebooks/Data_cleaning.ipynb)
     
  2. [Exploratory Data Visualization](Notebooks/EDA.ipynb) : Visualized the atomic features of the metal alloys
  
  3. [Data Preprocessing and Model Comparisons](Notebooks/Models_comparison.ipynb) : Preprocessed the data before feeding to the models and Compared Multiple Classification models to predict the states of the alloys
  
  

## Model Comparison And Results
<table>
  <tr>
    <th colspan="2">Models Accuracy Before And After Applying PCA</th>
  </tr>
  <tr>
    <td>
      <img src="Plots/Model_Comparisons/Screenshot 2026-08-12 204901.png" width="500">
    </td>
    <td>
      <img src="Plots/Model_Comparisons/Screenshot 2026-08-12 204927.png" width="500">
    </td>
  </tr>

