# Sirtuin6 BFE Classification

Proteins are complex molecules that play crucial roles in biological processes. Understanding the interactions between proteins and ligands is of great importance in the field of drug discovery. The binding free energy (BFE) of a ligand to a protein is a key factor in determining the affinity of the ligand for the protein. In this project, we develop a machine learning model based on logistic regression to classify BFE for the protein Sirtuin6.

## Dataset

The dataset used in this project was obtained from [UCI Machine Learning Repository](!https://archive-beta.ics.uci.edu/dataset/748/sirtuin6+small+molecules-1). The dataset includes 100 molecules with 6 most relevant descriptors to determine the candidate inhibitors of a target protein, Sirtuin6. The molecules are grouped based on their low- and high-BFEs.

## Methods

In this project, the Sirtuin6 dataset was split into 80% training and 20% testing sets, and the features were standardized using the StandarScaler method. Logistic regression, a popular method for binary classification problems, was then used to classify BFE as high or low for Sirtuin6.

## Results and Discussion

The logistic regression model achieved high performance in classifying Sirtuin6 binding free energy in both the training and test sets. The accuracy score of 81.43% and 86.67%, respectively, indicates that the model correctly classified a large proportion of the data points. The precision score of 81.57% and 87.56%, respectively, indicates that out of all the predicted positive cases, a high percentage of them were actually positive. The recall score of 81.43% and 86.67%, respectively, shows that the model was able to identify a high percentage of the actual positive cases. The F1 score of 81.35% and 86.73%, respectively, which is the harmonic mean of precision and recall, suggests that the model achieved a balance between precision and recall.

These high evaluation metrics indicate that the logistic regression model was effective in capturing the relationship between the input features and the output target variable. The model was able to classify the binding free energy of Sirtuin6 with high accuracy, precision, recall, and F1 score. Furthermore, the improvement in performance from the training set to the test set suggests that the model can generalize well to new, unseen data.

However, it is important to note that further evaluation and analysis are necessary to determine the robustness and generalizability of the model. This can include assessing the model's performance on larger and more diverse datasets, exploring the impact of feature selection and feature engineering on model performance, and assessing the model's ability to handle imbalanced datasets.

## Conclusion

In this project, we developed a machine learning model based on logistic regression to classify BFE for the protein Sirtuin6. The model performance demonstrating its potential as a tool for predicting ligand affinity. This work highlights the importance of machine learning in drug discovery and the potential for developing more accurate models to predict protein-ligand interactions.

## Acknowledgment

Tardu, M., Rahim, F., Kavakli, I. H., & Turkay, M. (2016). Milp-hyperbox classification for structure-based drug design in the discovery of small molecule inhibitors of Sirtuin6. RAIRO-Operations Research, 50(2), 387-400. 
https://doi.org/10.1051/ro/2015042