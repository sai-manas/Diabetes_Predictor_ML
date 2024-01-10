# Diabetes Web App Predictor using Classification Models

## Overview

Diabetes Predictor web application predicts diabetes in patients using classification models. The implementation includes Logistic Regression, Decision Tree, Naive Bayes, and Support Vector Machines. The selection process involved a comprehensive comparison, evaluation, and cross-validation to identify the most effective model. After rigorous cross-validation and metric analysis, the Logistic Regression model emerged as the optimal choice, exhibiting superior performance with an accuracy of 80%.

The Logistic Regression model, deemed the most reliable, has been deployed in a flask web application using AWS. The web application utilizes the `LogisticModel.pkl` file, which contains the trained Logistic Regression model, offering a user-friendly interface for diabetes prediction.

## Screen Recording of Diabetes predictor application deployed on AWS
https://github.com/sai-manas/Diabetes_Predictor_ML/assets/106865226/030066b0-c8db-46ea-add6-499387c57783

## Jupyter Notebook

1. [**Logistic Regression:**](https://github.com/sai-manas/Diabetes_Predictor_ML/blob/main/Notebooks/Logistic_Regresssion.ipynb) Notebook focusing on Logistic Regression classification.
2. [**Decision Tree:**](https://github.com/sai-manas/Diabetes_Predictor_ML/blob/main/Notebooks/Decision_Tree_Classifier.ipynb) Notebook dedicated to Decision Tree classification.
3. [**Naive Bayes:**](https://github.com/sai-manas/Diabetes_Predictor_ML/blob/main/Notebooks/Naive_Bayes_GaussianNB.ipynb) Notebook demonstrating the implementation of Naive Bayes classification.
4. [**Support Vector Machines:**](https://github.com/sai-manas/Diabetes_Predictor_ML/blob/main/Notebooks/Support_Vector_Classification.ipynb) Notebook showcasing Support Vector Machines classification.

## Technologies Used

- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn , Pickle, Warnings
- **Web Framework:** Flask
- **Frontend:** HTML, CSS
- **Deployment:** AWS Elastic Beanstalk, AWS CodePipeline

## Model Evaluation

Each notebook evaluates the performance of the respective model using various metrics, including accuracy, classification report, cross-validation score, and Grid Search CV best score. The Logistic Regression model exhibited promising results, providing valuable insights into Diabetes prediction.

## Model Deployment

To make the model accessible, I developed a web application using Flask, a Python web framework. The Logistic Regression model has been deployed in a web application using the pickle library. 

The application is deployed on AWS Elastic Beanstalk, with continuous integration and deployment facilitated by AWS CodePipeline.

## How to use

### I. Notebook Usage
   - Explore the notebooks to understand the implementation and evaluation of different Classification models [Note Books](https://github.com/sai-manas/Diabetes_Predictor_ML/tree/main/Notebooks).

> Hosted this web application using Flask and deployed on AWS
### II. Flask
1. **Clone the GitHub Repository:**
   - Open your terminal or command prompt.
   - Navigate to the directory where you want to clone the repository.
   - Run the following command to clone my GitHub repository:
     ```
     git clone https://github.com/my-username/my-repo.git
     ```
   - Replace `my-username` with my GitHub username and `my-repo` with the name of my repository.
     
2. **Install Python:**
   - If you haven't already, make sure you have Python installed on your system. You can download it from the official Python website (https://www.python.org/downloads/) and follow the installation instructions for your operating system.
     
3. **Create a Virtual Environment (Optional but recommended):**
   - It's a good practice to create a virtual environment to isolate the dependencies of your project. You can create a virtual environment using the following command:
     ```
     python -m venv venv
     ```
4. **Activate the Virtual Environment (Optional but recommended):**
   - Activate the virtual environment using the appropriate command based on your operating system:
     - On Windows:
       ```
       venv\Scripts\activate
       ```
     - On macOS and Linux:
       ```
       source venv/bin/activate
       ```
5. **Install Required Packages:**
   - Navigate to the root folder of your cloned repository.
   - Run the following command to install the required Python packages listed in the `requirements.txt` file:
     ```
     pip install -r requirements.txt
     ```
6. **Run the Flask Application:**
   - Once the packages are installed, you can start your Flask application. In your repository's root folder, you should typically have a file named `application.py`, which is the main Flask application file.
   - Run the application with the following command:
     ```
     python application.py
     ```
7. **Access the Application:**
   - Your Flask application should now be running. You can access it in your web browser by navigating to `http://localhost:5000` or the URL provided by your application.

### III. AWS (ELastic Beanstalk,Code Pipeline)
1. **Fork the GitHub Repository:**
   - Click the "Fork" button in the top-right corner of this repository's page.
   - This action will create a copy of my repository under your GitHub account.
   - Use this as a source for deploying application in AWS
     
2. **Deploy application using ELastic Beanstalk and Code Pipeline in AWS**
   - Follow the steps in this Article for deploying Web application in AWS. URL - https://dev.to/wardaliaqat01/cicd-pipeline-hands-on-aws-code-pipeline-elastic-beanstalk-github-35n3
