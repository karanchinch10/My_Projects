
<h1><a href="https://www.youtube.com/watch?v=5s0L1YtdjTI&ab_channel=HansrajSongs">1. Predict Price of old Car</a></h1>
Now a day we know many peoples are going to buy second hand car instaed of buying new one, because its is better investment option where we get almost 30-40% discount. but main question arise here is how will us know actual selling price of old car base on their features or which factor matters most to determine selling price of car?? So in orer to solve this complex problem, I have build machine learning model which will predict the estimated price of car at which car should be sold base on given features.

- I have made ML model which will predict estimated price of old car base on thier features such as brand,KM drive,Power,Year and so on..
- Completed stepwise EDA (Exploratory Data Analysis) then visualizatiion to get some idea about important features or correlation of each feature with output which dominates more to predict price
- Then I have done Feature Engineering which inclueds features extraction & features construction based on my domian knowledge and visualization followed by label encoding
- Train multiples ML models then Analysed & compare performance of differents models based of accuracy and complexity
- Used all regression algorithms to train model and after comparing result of all, got well accuracy by RandomForestRegressor(cross validation--around 90%)
- Finally Build web application using streamlit and deploy the model 
- <https://karanchinch10-oldcar-sell-streamlit-app-p6gwqq.streamlitapp.com/> works too
- Technical tools or library used -- <code>Python,Numpy,Pandas,sklearn,matplotllib,html,css,streamlit</code>

<h1><a href="https://www.youtube.com/watch?v=5s0L1YtdjTI&ab_channel=HansrajSongs">2.IRIS flowers Detection</a></h1>
To determine class or cateogry of flower which its belong to base on their 4 features or parameters such as sepal length,sepal width, petal length and petal width. Dataset contains total 3 category of flowers of 50 instances each(setosa,virginica,versicolor), where each class refers to a type of iris plant. One class is linearly separable from the other 2; the latter are NOT linearly separable from each other.

- I have made model which will predict cateogry of flower which its belong to base on their 4 features(sepal length,sepal width, petal length and petal width).
- Done stepwise EDA (Exploratory Data Analysis) and visualization to get some idea about important features
- After Visualization found that sepal length & sepal width has strong correlation while petal length & petal width has poor relation
- Train model with multiples classification algorithms
- Analysed & compare performance of differents models based on confusion matrix F1 score
- After traning with mulptiples algo SVM and KNN had given best accuracy 
- Vary K value still accuracy was almost same 97.2 which approximate equal to SVM  then after cross validation SVM accuracy was better than KNN
- Finally Build web application using streamlit and deploy the model. 
- <https://karanchinch10-streamlit-iris-app-0k57bb.streamlitapp.com//> works too.
- Technical tools or library used -- <code>Python,Numpy,Pandas,sklearn,matplotllib,html,css,streamlit</code>

<h1><a href="https://www.youtube.com/watch?v=5s0L1YtdjTI&ab_channel=HansrajSongs">3.Visualization of Google Playstore Apps</a></h1>
Google Play Store team is about to launch a new feature wherein, certain apps that are promising, are boosted in visibility. The boost will manifest in multiple ways including higher priority in recommendations sections (“Similar apps”, “You might also like”, “New and updated games”). These will also get a boost in search results visibility. This feature will help bring more attention to newer apps that have the potential.


- Perform EDA, Data cleaning and Data correction 
- Done details visualization on gplay store apps to get basic information or data insight and that will be helpful for decision making like

   1) Total No of apps of all category (like games,sports,medical,education,beauty..etc) to understand whcih category has highest apps 
   2) Which category has highest demand, rating, installation & reviews
   3) Total percentages of free and paid apps available in glapy store
   4) Which category of apps are most installed or like to user
   5) Average price of paid apps and their demands
   6) Is there is any relation of apps rating and reviews with insatllation?
- Technical tools or library used -- <code>Python,Numpy,Pandas,sklearn,matplotllib,html,css,streamlit</code>
- <https://www.kaggle.com/code/karanchinchpure/gplay-playstore-data-visualization-eda/>
- https://github.com/karanchinch10/Exploratory-Data-Analysis-EDA-/blob/main/EDA%20data/gplay-playstore-data-visualization-EDA.ipynb
- <a href="https://github.com/karanchinch10/Exploratory-Data-Analysis-EDA-/blob/main/EDA%20data/gplay-playstore-data-visualization-EDA.ipynb">link text</a>
