# Real Estate Price Prediction Website

This is a real estate price prediction website. The project consists of three main components:

1. **Model Building**: We built a model using `sklearn` and `Linear Regression` on the Bangalore home prices dataset from Kaggle. During this phase, various data science concepts were employed, including data loading and cleaning, outlier detection and removal, feature engineering, dimensionality reduction, `GridSearchCV` for hyperparameter tuning, and k-fold cross-validation.

2. **Python Flask Server**: The second step was to create a Python Flask server that uses the saved model to serve HTTP requests. This server processes the input data and returns the predicted home prices.

3. **Frontend Website**: The third component is the user interface, which was built using HTML, CSS, and JavaScript. This website allows users to input home features such as square footage, number of bedrooms, etc., and calls the Python Flask server to retrieve and display the predicted price.

## Technology and Tools

This project covers a range of technologies and tools:

1. **Python**: The core programming language used for model building and server-side logic.
2. **Numpy and Pandas**: Used for data cleaning and manipulation.
3. **Matplotlib**: Utilized for data visualization.
4. **Sklearn**: Used for model building and machine learning tasks.
5. **Jupyter Notebook, Visual Studio Code, and PyCharm**: IDEs used during the development process.
6. **Python Flask**: Employed to create the HTTP server for handling requests.
7. **HTML/CSS/JavaScript**: Technologies used for building the user interface.

