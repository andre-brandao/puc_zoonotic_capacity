# puc_zoonotic_capacity

This project is based on the original work of [HanLabDiseaseEcology](https://github.com/HanLabDiseaseEcology/zoonotic_capacity).


## Data

The `input` folder contains the necessary CSV files for training models and using models to make predictions.

- `MammalTrainingData080221_NvAdded.csv`: Training data on wild mammal species used for making the highest-accuracy zoonotic capacity model.
- `MammalPredictionData231220_wildCategory.csv`: Trait data for 5,400 mammals used for making predictions based on the fitted zoonotic capacity model.

For more information on the predictor fields, refer to the Supplementary Tables and Figures in the original paper's figshare repository: [https://doi.org/10.25390/caryinstitute.c.5293339](https://doi.org/10.25390/caryinstitute.c.5293339)

## Methods Used

- Naive Bayes
- Decision Tree
- Random Forest
- XGBoost
- AdaBoost
- Support Vector Machine (SVM)
- Logistic Regression
- Neural Network
