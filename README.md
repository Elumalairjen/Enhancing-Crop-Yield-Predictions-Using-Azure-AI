 # Crop-Yield-Prediction



This project enables users to predict crop yields using advanced Azure AI tools and visualize results in Power BI Desktop. The ML model is trained, deployed as a REST API, and integrated with Power BI for testing and reporting.


## Features
- **Crop Yield Prediction:** Predicts the agricultural yield based on input parameters such as crop type, season, area, and year.
- **Data Visualization:** Creates interactive dashboards using Power BI Desktop to present and analyze prediction results effectively.
- **REST API Integration**: Provides real-time predictions through a REST API, enabling seamless integration with other applications and tools.

## Project Workflow

![image](https://github.com/user-attachments/assets/0627ff30-3fea-47d2-969c-bb76a002eac3)


## Overview
This application consists of two main components:
1. **Backend (Azure ML REST API)**:  A RESTful API deployed on Azure Machine Learning that accepts user input, processes it using a trained machine learning model, and provides crop yield predictions.
2. **Frontend (Power BI )**: An interactive dashboard created using Power BI, where users can input data, view predictions, and analyze results through dynamic visualizations and reports.


### Functionalities
- **User Input Form**: Users can input crop-related data such as Crop Type, Season, Area, and Year.  
- **Prediction**: The app predicts crop yield based on the provided input data using a trained machine learning model.  
- **Visualization Dashboard**: Results and insights are displayed in interactive dashboards created using Power BI Desktop.  
- **Minimalistic Design**: The system is designed to ensure a seamless experience with clean and intuitive interfaces for data entry and visualization.  

 
## **Tech Stack**
- **Backend:**  
  - Azure ML Workspace (for model training and deployment)  
  - REST API using Azure App Services  

- **Frontend:**  
  - Power BI Desktop (for data visualization and reporting)  

- **Deployment:**  
  - Azure App Services (for REST API hosting)  
  - Azure Blob Storage (for storing datasets)  
  - Azure AI Cognitive Services (for advanced analytics)  



## Model Training  
The crop yield prediction model was trained using **Azure ML Workspace**. The dataset was uploaded and stored in **Azure Blob Storage**, ensuring scalability and seamless access. The model training process was carried out in **Azure ML Workspace** for optimal accuracy.

## Data Integration  
The project integrates data processing and prediction through **Azure Blob Storage** and a REST API. Users can send data to the API and receive predictions for crop yield based on inputs like area, season, and crop type.

## Power BI Integration  
The project uses **Power BI Desktop** to visualize predictions and provide insightful reports. REST API integration ensures real-time data flow, enabling users to test predictions and analyze results interactively.

## Deployments  
This project was deployed using **Azure App Services** to make the model accessible as a REST API. The deployment ensures reliability, scalability, and seamless integration with Power BI for end-user testing and visualization.

## Credits  

- **Azure ML Workspace**  
  Used to train and deploy the **crop yield prediction model**, leveraging scalable cloud-based machine learning tools to streamline the model development and deployment process.

- **Azure Blob Storage**  
  Facilitated secure storage and easy access to datasets used for training the machine learning model.

- **Power BI Desktop**  
  Enabled interactive visualization and reporting of prediction results through seamless integration with the REST API.

- **Azure App Services**  
  Hosted the deployed REST API, ensuring high availability, scalability, and secure integration with other Azure services.

- **REST API**  
  Provided real-time prediction capabilities, making the model accessible for integration with external tools like Power BI.  

## Demo Video 

https://github.com/user-attachments/assets/dbb6fda5-f57f-48f4-84fc-8767e7b2a274



## Presentation link :

[Click Here](https://stdntpartners-my.sharepoint.com/:p:/g/personal/elumalai_ramalingam_studentambassadors_com/ESPYdLV0LEJGpDRQspuqftwB_2sglRg8C0piE-DJAt40fw?e=wmQV60)


