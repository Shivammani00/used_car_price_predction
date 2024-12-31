----------Used Car Price Prediction---------------

----Overview---

       This project is a machine learning-based web application that predicts the price of a used car based on its features. It uses a Random Forest Regression model to provide accurate predictions and is 
       deployed using Flask for easy accessibility.

------Features-------

Predicts the price of a used car based on:

        Number of years driven
        Original purchase price
        Number of previous owners
        Fuel type (Petrol/Diesel/Other)
        Seller type (Dealer/Individual)
        Transmission type (Manual/Automatic)
        Kilometers driven
        User-friendly interface developed with Flask. Provides insights into car pricing trends.

----Technology Stack-----

       Programming Language: Python
       Framework: Flask
       Machine Learning Algorithm: Random Forest Regression
       Data Analysis: Pandas, NumPy, Seaborn
       Visualization: Matplotlib, Seaborn
  
----Dataset-----

       The dataset used in this project is stored at: D:/College_pro/car data.csv-------------any one can use it according to their file name where they are saving it--

------Model Training---------

Data Preprocessing:

    Handled missing values.
    Encoded categorical variables using One-Hot Encoding and Label Encoding.
    Scaled numerical features.
    Split the dataset into training and testing sets.

- Model Selection:
        Chose Random Forest Regression for its accuracy and robustness.

- Hyperparameter Tuning:

    Optimized the model using GridSearchCV.

-----Usage------

     Input the car details on the web interface.
     Click the 'Predict' button.
     The predicted price will be displayed on the screen.
  
-----Limitations-----

     Model performance may vary for unseen data.
     Assumes data provided is accurate and consistent.
     Limited to the features available in the dataset.
  
-----Future Enhancements------

  Add more features like car brand, model, and condition.
  Use advanced algorithms like XGBoost for better accuracy.
  Deploy the application to a cloud platform for public access.
  Provide visualization of price trends for user insights.
