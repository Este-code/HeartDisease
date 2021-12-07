# HeartDisease

The dataset for this project can be found here:
  https://www.kaggle.com/fedesoriano/heart-failure-prediction
  
**Task**: Classify observations in two categories: affected or not affected by an heart disease.

**Dataset**

This is not a generalization; there are 918 observations in this dataset and they come from different palces (USA, Hungary, Switzerland),
therefore, through this dataset, one can only find insights based on a relatively small amount of cases.

![alt text](https://github.com/Este-code/HeartDisease/blob/main/images/image_1.png)

This dataframe has 12 features, categorical and nurmerical.

'HeartDisease' will be the target on which I will be building the model.

![alt text](https://github.com/Este-code/HeartDisease/blob/main/images/Image_2.png)

From the dataframe descriction one can notice an intersting factor; the minimum value of Cholesterol and FastingBS are both zero.

In this dataset there a no missing values.

**Plots**

![alt text](https://github.com/Este-code/HeartDisease/blob/main/images/Plot_1.png)

From the countplot graph, one can clearly see how males are particulalry affeccted by heart diseases.

![alt text](https://github.com/Este-code/HeartDisease/blob/main/images/Plot_2.png)

The graph above shows who is affected by an heart disease, in relation with someone age.
Focusing on the orange curve, the density starts growing approximatley around 45, reaching his peak at 60 and decreasing constantly until it touches 70.

![alt text](https://github.com/Este-code/HeartDisease/blob/main/images/Plot_3.png)

Chest pain type:
- TA: Typical Angina, 
- ATA: Atypical Angina, 
- NAP: Non-Anginal Pain, 
- ASY: Asymptomatic.

Based on this graph, ATA is the one that occurs more often that the others.

![alt text](https://github.com/Este-code/HeartDisease/blob/main/images/heatmap.png)

From the heatmp one can see that there are not high related features, therefore I can only assume that all the features are important for the purpose of the model.

**Model**

For this dataset I will use a supervised learning method.
The first step is to do a basic feature engineering, in order to extrapolate the best accuracy and to feed the model with every feature.

![alt text](https://github.com/Este-code/HeartDisease/blob/main/images/features.png)

This are the first five rows of the dataset, after I changed the categorical features by simply replacing each unique observation with a numerical value.

**Logistic regression**

Since our target has a binary output, I decided to use the logistic regression model.

![alt text](https://github.com/Este-code/HeartDisease/blob/main/images/logistic_regression.png)

I trained this model with 80% of data from the dataset, using all the features. 
The accuracy of prediction is 84%, which is really good, however ther is still room for improvement.




