# Azure Machine Learning Studio Model Deployment

This project demonstrates how to use Azure Machine Learning Studio to create, test, and deploy machine learning models with minimal coding. The model is trained using the Automated Machine Learning feature in Azure Machine Learning Studio, and it is tested and deployed using Python code in Google Colab.

### Project Overview

This project focuses on the process of training a machine learning model in Azure Machine Learning Studio, testing it with Google Colab, and deploying it in a minimal code environment. The model in this project is a regression model used to predict rental prices based on various input features (e.g., day, month, season, temperature, and more).

##### Sample page of Workspace

![screenshot-ml azure com-2025 01 24-12_28_10](https://github.com/user-attachments/assets/379d04e9-73ba-4d58-8c24-51d39ab5c1d6)

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

##### Samples 1 of Model Performance

![metrics](https://github.com/user-attachments/assets/8e011b4d-79b8-4d8d-b4e8-db22456b3110)

##### Sample 2 of Model Performance

![metrics2](https://github.com/user-attachments/assets/de8f1468-f3c6-41da-82fc-a9d67d6c5494)

### Source

https://learn.microsoft.com/en-ca/training/modules/fundamentals-machine-learning/10-exercise-auto-ml
