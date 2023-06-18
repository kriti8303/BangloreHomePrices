# BangaloreHomePrices
This is a data science project in which I have built a model for real estate price prediction. I have used bangalore home prices dataset from kaggle.com and used linear regression model for prediction. I have made a flask server that uses this saved model to serve http requests. Finally for the front end, HTML, CSS and JavaScript is used to allow the user to enter the attributes like square ft area, bedrooms etc and the model will call python flask server to retrieve the predicted price. Technology and tools used:
1. Python
2. Numpy and Pandas for data cleaning
3. Matplotlib for data visualization
4. Sklearn for model building
5. Jupyter notebook, visual studio code and pycharm as IDE
6. Python flask for http server
7. HTML/CSS/Javascript for UI
# Demo
1.  We enter the requested values and click on the 'Submit' button below.
![bhp1](https://github.com/kriti8303/BangloreHomePrices/assets/86372176/4ab96676-0330-4c42-a713-ac0b6f7a07ed)
2. The web app produces a prediction on the price.
![bhp2](https://github.com/kriti8303/BangloreHomePrices/assets/86372176/c18356fe-e47e-4607-811a-e96f7e58bb93)
# Conclusion
This is a complete end-to-end project from data cleaning, EDA, model selection to deploying and creating UI. While choosing models, GridSearchCV was used along with k-fold cross validation. In this, Linear Regression gave the best accuracy. Flask API endpoints were created to fetch the list of locaitons and to predict the results.
