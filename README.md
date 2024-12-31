**Name**: Heer Chauhan <br>
**Company**: CODTECH IT SOLULTIONS <br>
**ID**: CS24NY354846 <br>
**DOMAIN**: DATA SCIENCE <br>
**DURATION**: DECEMBER TO JANUARY 2025 <br>
**Objective** <br>
**Train a Machine Learning Model**: Build a model to predict the species of an Iris flower based on its features (sepal length, sepal width, petal length, petal width) using a machine learning algorithm.<br>
**Save the Model**: Once the model is trained, save it to a file so that it can be easily reused for making predictions in the future without retraining.<br>
**Deploy the Model**: Create a web application using Flask or FastAPI to deploy the trained model. This web app will allow users to input flower measurements and receive predictions about the species.<br>
**Provide an Accessible API**: Expose the trained model as an API, enabling users to interact with the model over the web and receive real-time predictions.<br>
**Dataset Overview** <br>
The **Iris dataset** is a well-known dataset used in machine learning, often for classification tasks. It contains measurements of different parts of Iris flowers from three species. Here's an overview of the data:<br>
**Features (Attributes):**
1. **Sepal Length:** The length of the sepal (in cm).
2. **Sepal Width:** The width of the sepal (in cm).
3. **Petal Length:** The length of the petal (in cm).
4. **Petal Width:** The width of the petal (in cm).

**Target (Label):**
- **Species:** The species of the Iris flower. There are three possible classes:
  1. **Setosa**
  2. **Versicolor**
  3. **Virginica**

 **Dataset Structure:**
- **Number of Instances:** 150 (50 instances for each species)
- **Number of Features:** 4 (Sepal Length, Sepal Width, Petal Length, Petal Width)
- **Target Classes:** 3 (Setosa, Versicolor, Virginica)

**Use in the Project:**
- The dataset is typically used for classification tasks. The goal is to predict the species of the flower based on its sepal and petal measurements.<br>
**Technologies Used**<br>
For this end-to-end data science project, the following technologies are used:<br>
**1. Python**
Purpose: The primary programming language for data manipulation, model training, and web deployment.<br>
**2. Pandas**
Purpose: Used for data manipulation and analysis. It helps load, preprocess, and organize the Iris dataset in tabular form (data frames).<br>
**3. Scikit-learn**
Purpose: Provides tools for machine learning algorithms and model evaluation.<br>
In this project:
DecisionTreeClassifier is used to build the classification model.
train_test_split is used for splitting the dataset into training and testing sets.
accuracy_score is used to evaluate the model’s performance.<br>
**4. Joblib**
Purpose: A library used to save the trained machine learning model to a file (.pkl format), so it can be loaded later without retraining.<>br
**5. Flask**
Purpose: A lightweight web framework used to deploy the trained model as a RESTful API. It handles HTTP requests and serves the model's predictions based on the input features.<br>
**6. HTML & JSON**
Purpose: HTML is used for the structure of the web page (if building a frontend for the API). JSON is used for data exchange between the Flask app and clients (i.e., to send input features and receive predictions).<br>
**7. Postman / cURL**
Purpose: Used to test the Flask API by sending POST requests with input features and receiving the predicted species as a response. <br>
**8. Jupyter Notebook**
Purpose: A popular tool for exploratory data analysis (EDA) and prototyping in Python, which might be used for initial data exploration and model training before creating the Flask app.  <br>

**Result**<br>
In short, the result of this project will be:

1. A **trained Decision Tree model** that predicts the species of an Iris flower based on its features.
2. **Model accuracy** displayed (e.g., 100% accuracy on the test set).
3. A **Flask web application** deployed locally, where users can input flower measurements and receive species predictions in return.
4. The model will be saved and available for future use.
    
