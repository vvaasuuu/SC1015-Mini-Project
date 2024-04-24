# Deepdive into Diabetes Dataset

## Contents 
1) [Our Dataset](https://github.com/vvaasuuu/SC1015-Mini-Project/blob/53cea610dd99038553a6dc9b9f360bc1186cd981/Our%20Dataset.ipynb)
2) [Exploratory Data Analysis](https://github.com/vvaasuuu/SC1015-Mini-Project/blob/53cea610dd99038553a6dc9b9f360bc1186cd981/Exploratory%20Data%20Analysis.ipynb)
3) [Classification](https://github.com/vvaasuuu/SC1015-Mini-Project/blob/53cea610dd99038553a6dc9b9f360bc1186cd981/Classification%20Model.ipynb)
4) [Prediciton of Diabetes Type, Risk of DKA and Risk of Hypertension](https://github.com/vvaasuuu/SC1015-Mini-Project/blob/53cea610dd99038553a6dc9b9f360bc1186cd981/Prediction%20of%20Diabetes%20Type%2C%20Risk%20of%20DKA%20and%20Risk%20of%20Hypertension.ipynb
)
5) [Optimisation Model - Random Forest](https://github.com/vvaasuuu/SC1015-Mini-Project/blob/53cea610dd99038553a6dc9b9f360bc1186cd981/Optimisation%20Model%20-%20Random%20Forest.ipynb)
6) [Deep Learning](https://github.com/vvaasuuu/SC1015-Mini-Project/blob/53cea610dd99038553a6dc9b9f360bc1186cd981/Deep%20Learning.ipynb)

## Problem Definition 
This study analyzes a diabetes dataset to uncover factors affecting health and diabetes risk. 
We then leveraged our knowledge to predict: 1) diabetes type, 2) DKA risk (a serious complication), and 3) hypertension risk

## Models Used
- Classification Model: Decision Tree
- Optimisation Model: Random Forest
- Deep Learning: Tenserflow

## Conclusion
- We began by investigating a diabetes dataset to understand the key factors impacting patients.
- We used various visualizations, including scatter plots and boxplots amongst others, to do EDA and understand the relationships between different variables.
- Classification techniques helped determine the contribution every factor had towards the outcome.
- We created new columns to determine the type of diabetes along with identifying patients at risk for Diabetic Ketoacidosis) and hypertension.
- We used a Random Forest optimization model to determine the most influential factor.

Based on the combined observations made from EDA, classification, and the Random Forest optimisation model, we concluded that glucose levels have the strongest association. 

- We also explored the potential of deep learning in analyzing our dataset. We implemented a deep learning model with two hidden layers to predict the likelihood of diabetes based on the input variables.
- We trained the model using a subset of the dataset and tested it on the remaining data.
- Our results showed that the model was able to predict diabetes with an accuracy of 87.7%. This is a significant improvement compared to the classification tree model, which was 74.1%

We realised that with further improvement and continued optimization and testing, our deep learning model can be a powerful tool in predicting and diagnosing diabetes as wells as other health issues like Diabetic Ketoacidosis and hypertension, ultimately improving patient outcomes and reducing health risks.


## Contributors
- *Audrey --> Classficiation - Decision Tree Model*
- *Kavya --> Prediction of Diabetes Type, Risk of DKA and Risk of Hypertension* and *Deep Learning*
- *Vasumathi --> Exploratory Data Analysis* and *Optimisation Model - Random Forest*

## References
- https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset
- https://medium.datadriveninvestor.com/optimizing-a-random-forest-44ad5f44ef0c
- https://www.datacamp.com/tutorial/random-forests-classifier-python
- https://www.youtube.com/watch?v=mozBidd58VQ
