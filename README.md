# Predicting Customer Churn: Building an Interactive Web App with Gradio
<img width="960" alt="image" src="https://github.com/aaronayitey/LP4-Gradio-Deployment/assets/63174936/0a328305-6a03-4496-a1b1-3ab3bdfa04bb">


This project utilizes Gradio to create an interactive web-based interface for predicting customer churn using a pre-trained machine learning model.

## Summary
| Code          |     Name                       | Published Article|    Deployment |
| ------------- | -------------                  | -------------    | ------------- |   
| LP4          | LP4- Embedding a Machine Learning Model in a Web App |  [Article](https://medium.com/@aaronayitey/predicting-customer-churn-building-an-interactive-web-app-with-gradio-a651585688f9) |[App](https://huggingface.co/spaces/aaronayitey/gradio-app)

# Introduction
In the competitive world of business, customer retention is a key factor in a company’s success. Customer churn, also known as customer attrition, is the rate at which customers stop doing business with a company. Predicting customer churn is crucial because it allows businesses to take proactive measures to retain their valuable customers. In this article, we will explore the process of building an interactive web application for predicting customer churn using a pre-trained machine-learning model and the Gradio library.

# Prerequisites
Before running the app, make sure you have the following installed:
* Python
* Virtual environment (optional but recommended)
* Dependencies listed in `requirements.txt`

# Building the Customer Churn Prediction Model
For our customer churn prediction model, we’ll use a pre-trained machine learning model. The model is loaded from joblib files, and the input data is processed using a preprocessor. This preprocessor is vital to ensure that the input data is in the same format as used during model training.

# Running the Application
To run the application, execute the Python script. This will start a local web server, and you can access the application in your web browser. Users can input customer information, and the application will provide predictions based on the machine learning model. However, to make this app available to the public on the internet, I chose to host it on [huggingface.co.](https://huggingface.co/)

Hugging Face Spaces is a platform that allows you to deploy and share your machine-learning models and applications. Here is the process of deploying the Gradio app on Hugging Face Spaces:
### Step 1: Create a Hugging Face account at huggingface.co.
Navigate to [huggingface.co](https://huggingface.co/) and sign up.
### Step 2: Create a New Space
* Log in to your Hugging Face account.
* Go to the [Hugging Face Spaces](https://huggingface.co/spaces) section.
* Click the “Create Space” button to create a new space. A space is where you can host your models and apps.
* Fill in the required details for your space, such as the name, description, visibility settings, and privacy settings. Select Gradio in this case.
* Click the “Create Space” button.

### Step 3: Upload Model Files
* Inside your new space under “Files”, click the “Upload model” button. This is where you’ll upload your Gradio app files, including your Python script and any model or data files.
* Choose your Gradio app script, along with any additional model files or data files, and upload them to your space. In my case, I uploaded the app.py, rf_model.joblib, preprocessor.joblib and requirements.txt.

# Usage 
* Fill in the input fields with relevant information.
* Click the "Predict" button to see the churn prediction.
* Click the "Clear" button to clear the input options.

# Conclusion
The above is a demonstration of how to build a customer churn prediction web app using Gradio and deploy on huggingface.co. This empowers businesses to leverage machine learning models for making informed decisions about customer retention. Gradio simplifies the process of creating user-friendly interfaces for machine learning models, making it accessible to a broader audience. With this tool, businesses can predict customer churn and take proactive steps to ensure customer satisfaction and loyalty. Gradio is an excellent addition to the toolkit of data scientists and developers looking to share their models and insights with the world.
