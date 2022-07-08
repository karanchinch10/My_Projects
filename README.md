
<h1><a href="https://github.com/karanchinch10/Oldcar_Sell_Regression">1. Predict Price of old Car</a></h1>
Now a day we know many peoples are going to <strong>buy second hand car instaed of buying new one</strong>, because its is better investment option where we get almost <strong>30-40% discount</strong>. but main question arise here is how will us know <strong>actual selling price of old car</strong> base on their features or which factor matters most to determine selling price of car?? So in orer to solve this complex problem, I have build <strong>machine learning model</strong> which will predict the <strong>estimated price of car</strong> at which car should be sold base on given features.

- I have made <strong>ML model</strong> which will predict estimated price of old car base on thier features such as <strong>brand,KM drive,Power,Year and so on..</strong>
- Completed stepwise <strong>EDA (Exploratory Data Analysis)</strong> then visualizatiion to get some idea about <strong>important features or correlation</strong> of each feature with output which dominates more to predict price
- Then I have done <strong>Feature Engineering</strong> which includes <strong>features extraction & features construction</strong> based on my domian knowledge and visualization followed by label encoding
- <strong>Train multiples ML models</strong> then Analysed & compare performance of differents models based of accuracy and complexity
- Used all regression algorithms to train model and after comparing result of all, got well accuracy by <strong>RandomForestRegressor(cross validation--around 90%)</strong>
- Finally <strong>Build web application</strong> using streamlit and <strong>deploy</strong> the model 
- Web App 👉 <https://karanchinch10-oldcar-sell-streamlit-app-p6gwqq.streamlitapp.com/> 💝
- Technical tools or library used -- <code>Python,Numpy,Pandas,sklearn,matplotllib,html,css,streamlit</code>
-  
  -  <a href="https://www.kaggle.com/code/karanchinchpure/predict-price-of-used-cars-regression-problem">View On Kaggle</a> 💝
  -  <a href="https://github.com/karanchinch10/Oldcar_Sell_Regression">View On Github</a> 💝
  
<h1><a href="https://github.com/karanchinch10/Oldcar_Sell_Regression">2. Bank Marketing Campaign</a></h1>
<strong>Marketing campaigns</strong> are sets of strategic activities that promote a <strong>business’s goal</strong> or objective. A marketing campaign could be used to promote a product, a service, or the brand as a whole. To achieve the most effective results, campaigns are carefully planned and the activities are varied. Marketing campaigns are characterized by focusing on the <strong>customer needs</strong> and their overall satisfaction.
The following project focus on the analysis of a dataset of <strong>Bank Marketing</strong> which contains data or information about customers and aims to get useful insights from the data and <strong>predict if a new customer will accept a deposit offer or not</strong>.
By understanding important factors or features and <strong>patterns of target customers</strong> those subscribed for deposit so that company can improve this factors and <strong>improve business</strong> and also which will help to get best strategies to improve for the next marketing campaign

- I have made ML model which will predict either new customer will accept offer deposit or not?
- Completed stepwise <strong>EDA (Exploratory Data Analysis)</strong> then visualizatiion to get some idea about important features or correlation 
- Done <strong>Feature Engineering</strong> which includes features extraction & features construction based on domain knowledge and <strong>visualization</strong> followed by label encoding
- Train ML models with multiples algorithms then Analysed & compare <strong>performance of differents models</strong> based of accuracy and complexity
- after comparing with all, got well accuracy by <strong>RandomForest and XG boost</strong> 
- Finally after cross validation <strong>XG boost<strong> won (accuarcy of 85% and <strong>recall score 88%</strong>)
- Technical tools or library used -- <code>Python,Numpy,Pandas,sklearn,matplotllib,XG boost</code>
-  
  -  <a href="https://www.kaggle.com/code/karanchinchpure/bank-marketing-who-will-subscribe-for-deposit">View On Kaggle</a> 💝
  -  <a href="#">View On Github</a> 💝

<h1><a href="https://github.com/karanchinch10/IRIS_Classification">3. IRIS flowers Detection</a></h1>
To determine <strong>class or cateogry of flower</strong> which its belong to base on their 4 features or parameters such as sepal length,sepal width, petal length and petal width. Dataset contains total 3 category of flowers of 50 instances each(setosa,virginica,versicolor), where each class refers to a type of iris plant. One class is linearly separable from the other 2; the latter are NOT linearly separable from each other.


- I have made model which will predict cateogry of flower which its belong to base on their 4 features.
- Done stepwise EDA (Exploratory Data Analysis) and visualization to get some idea about important features
- After Visualization found that sepal length & sepal width has strong correlation while petal length & petal width has poor relation
- Train model with multiples classification algorithms
- Analysed & compare performance of differents models based on confusion matrix F1 score
- After traning with mulptiples algo SVM and KNN had given best accuracy 
- Vary K value still accuracy was almost same 97.2 which approximate equal to SVM  then after cross validation SVM accuracy was better than KNN
- Finally Build web application using streamlit and deploy the model. 
- Web App👉 <https://karanchinch10-streamlit-iris-app-0k57bb.streamlitapp.com//> 💝
- Technical tools or library used -- <code>Python,Numpy,Pandas,sklearn,matplotllib,html,css,streamlit</code>
- 
  -  <a href="https://www.kaggle.com/code/karanchinchpure/iris-classification-problem-eda">View On Kaggle</a> 💝
  -  <a href="https://github.com/karanchinch10/IRIS_Classification">View On Github</a> 💝

<h1><a href="https://github.com/karanchinch10/Exploratory-Data-Analysis-EDA-/blob/main/EDA%20data/gplay-playstore-data-visualization-EDA.ipynb">4. Visualization of Google Playstore Apps</a></h1>
Google Play Store team is about to launch a new feature wherein, certain apps that are promising, are boosted in visibility. The boost will manifest in multiple ways including higher priority in recommendations sections (“Similar apps”, “You might also like”, “New and updated games”). These will also get a boost in search results visibility. This feature will help bring more attention to newer apps that have the potential.

- Perform EDA, Data cleaning and Data correction 
- Done details visualization on gplay store apps to get basic information or data insight and that will be helpful for decision making like

   1) Total No of apps of all category (like games,sports,medical,education,beauty..etc) to understand whcih category has highest apps 
   2) Which category has highest demand, rating, installation & reviews
   3) Total percentages of free and paid apps available in glapy store
   4) Which category of apps are most installed or like to user
   5) Average price of paid apps and their demands
   6) Is there is any relation of apps rating and reviews with insatllation?
- Technical tools or library used -- <code>Python,Numpy,Pandas,sklearn,matplotllib,seaborn,html,css</code>
- 
  -  <a href="https://www.kaggle.com/code/karanchinchpure/gplay-playstore-data-visualization-eda">View On Kaggle</a> 💝
  -  <a href="https://github.com/karanchinch10/Exploratory-Data-Analysis-EDA-/blob/main/EDA%20data/gplay-playstore-data-visualization-EDA.ipynb">View On Github</a> 💝 

<h1><a href="https://drive.google.com/file/d/1OWEpEZOMQLKn9l1bylQrqw8NeEoizxoF/view?usp=sharing">5. Bank Management Web Application</a></h1>
<h3><strong>Python | Flask | SQL | HTML | CSS </strong><h3>

- I have made this flask project of bank management web application system
- Front end was created by HTML and CSS without use of bootstrap
- Project is specially designed for customer/bank holder to get all basic bank services
- First customer has to open their bank account by filling basic bank details such as Name, Password, DOB, mob no, Initial Deposit and register their bank account 
- Once account has  been created then they can login with their user ID and password
- User can view and modify their personal details from profile section 
- User can withdraw, credit money into their account
- Minimum credit and withdraw should be RS 200 and RS50  and minimum initial deposit should be min 1000 RS while opening account
- User can also change their password by clicking on forgot password and set new password by confirming their name and email ID 
- User can Login and Logout their account anytime
- Technical tools or library used -- <code>Python,Flask,MySql Database,XAMPP,html,CSS</code>
- 
  -  <a href="https://drive.google.com/file/d/1OWEpEZOMQLKn9l1bylQrqw8NeEoizxoF/view?usp=sharing">View Project Report</a> 💝
  -  👉<a href="#">View On Github</a> 💝

<h1><a href="https://drive.google.com/file/d/1OWEpEZOMQLKn9l1bylQrqw8NeEoizxoF/view?usp=sharing">6. Personal PortFolio</a></h1>
I have
