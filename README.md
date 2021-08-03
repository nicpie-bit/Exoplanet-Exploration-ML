# Exoplanet Exploration

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

To help process this data, I created machine learning models capable of classifying candidate exoplanets from the raw dataset.

I created a:

1. Support Vector Machine
2. K Nearest Neighbors Algorithm
3. Randon Forest Tree
4. Logistic Regression Model

For Each Model I:

1. Preprocessed the data by performing feature selection and the removeal of unnecessary features. 
2. As well as using 'MinMaxScaler' to scale the numerical data and separating the testing and training data.
3. I used 'GridSearch' to tune model parameters.

## Conclusions
After completing all the models I concluded that the Random Forest Tree had the highest accuracy with 77.6%. With this model I was also able to look at the importance of each feature. It showed that 'koi_model_snr' was the feature that influenced the data the most. The feature 'koi_tce_plnt_num' influenced the data the least. Once I did a GridSearch on the data it did not increase the accuracy which I thought was interesting. With the SVM Model, the highest accuracy was 62.8%. With the KNN Algorithm, the highest accuracy was with k=13 and that was 61.3%. So those percentages were close together but, not very high. The last model that I did was Logistic Regression. The Logistic Regression Model had 64.4% accuracy. I think for dealing with real world data; 77.6% accuracy is good for predicting new exoplanets. Of course having more data would help with increasing the accuracy of my models. 

## Resources

* [Exoplanet Data Source](https://www.kaggle.com/nasa/kepler-exoplanet-search-results)
