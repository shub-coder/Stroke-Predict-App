## Stroke-Predict-App

<div>
<img src="https://github.com/gprzy/stroke-prediction/blob/main/assets/stroke.jpeg" width="50%" height="50%"/>
</div>

* Demo of the web app can be found at - https://strokeprediction-app.herokuapp.com/*

# Problem
 
According to the World Health Organization (WHO) stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths.
This dataset is used to predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient. 

# Binary Classification

The problem can be approached as a binary classification task, in which the main objective is to correctly classify patients who are most likely to have a stroke. The data in question is unbalanced, making it difficult and inaccurate to use metrics such as accuracy. In this case, the metric chosen was the F1 score, as well as the ROC curve. From the metrics above, the equal error rate (EER) was calculated, as well as the optimal threshold to correctly classify the largest number of stroke patients as likely to have stroke (true positives).

<div>
<img src="https://github.com/shub-coder/Stroke-Predict-App/main/images/img1.png" width="500" height="300"/>
</div>

# Mobile View

<div>
<img src="https://github.com/shub-coder/Stroke-Predict-App/main/images/img2.png" width="500" height="300"/>
</div>
