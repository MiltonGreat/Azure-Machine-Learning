# Azure Machine Learning Studio Model Deployment

This project demonstrates how to use Azure Machine Learning Studio to create, test, and deploy machine learning models with minimal coding. The model is trained using the Automated Machine Learning feature in Azure Machine Learning Studio, and it is tested and deployed using Python code in Google Colab.

### Project Overview

This project focuses on the process of training a machine learning model in Azure Machine Learning Studio, testing it with Google Colab, and deploying it in a minimal code environment. The model in this project is a regression model used to predict rental prices based on various input features (e.g., day, month, season, temperature, and more).

### Deployment with Azure

1. Create the Workspace:
- In Azure Machine Learning Studio, create a workspace where you can manage your experiments, models, and deployments.

2. Train the Model:
- Use the AutoML feature in Azure Machine Learning Studio to automatically train and select the best model based on your dataset.

3. Deploy the Model:
- After the model is trained, deploy it using the Real-time endpoint option.
- Configure the virtual machine (e.g., Standard_DS3_v2) and other deployment parameters, then deploy the model.

4. Test the Model:
- Once deployed, use the Azure portal to test the model by sending input data and receiving predictions.

### Results

- Predicted rental value: 365.46954999

### Source

https://learn.microsoft.com/en-ca/training/modules/fundamentals-machine-learning/10-exercise-auto-ml
