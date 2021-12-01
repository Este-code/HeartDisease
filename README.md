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


