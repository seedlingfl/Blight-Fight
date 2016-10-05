# Blight-Fight
Urban blight refers to the deterioration and decay of buildings and older areas of large cities, due to neglect, crime, or lack of economic support. This is a typical sight in many US cities, such as the city of Detroit. As a city gets older, some buildings or properties are not maintained and become run-down, abandoned or condemned.

The city planners are actively trying to predict which properties are likely to become officially classified as blighted ahead of time. This can help the city take preventative action: a targeted demolition or renovation can prevent the spread of urban blight and facilitate economic revitalization of often distressed areas.

In this project, I work with real data from the [Open Data Portal of Detroit](https://data.detroitmi.gov/) to help urban planners build a blight prediction model. This is a real-world problem: the data is not perfectly clean, the questions are not perfectly unambiguous.

There are two major things that I did in order to build a good blight prediction model with Scikit Learn: 
  * Created a list of buildings from all the geo-located incidents collected through the open data portal;
  * Improved the accuracy of the model by extracting a richer set of features and selecting the best model from SVM, Decision Tree, Random Forests by cross validation.

Please see [BlightPrediction-Summary](https://github.com/seedlingfl/Blight-Fight/blob/master/BlightPrediction-Summary.ipynb) for the entire process of data acquisition, preprocess, modeling and analysis. If you want to play with the data, you can open the [BlightPrediction](https://github.com/seedlingfl/Blight-Fight/blob/master/BlightPrediction.ipynb) ipython notebook in which the data are shown explicitly. 
