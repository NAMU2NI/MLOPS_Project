*NOTE:* This file is a template that you can use to create the README for your project. The *TODO* comments below will highlight the information you should be sure to include.


# Your Project Title Here

In this project , we are going to create a Auto ML to classify whether the client will do a fixed deposit in the bank or not using the conversation and details of the client avaiable in the BankMarketing data. Goal of the project is deploy the Model and consume it. Below is the Architectural diagram and the process flow of the problem. 

## Architectural Diagram

Load the BankMarketing Dataset in the Notebook and run the Automl Pipleline by setting up the Automl config. Choose the best model based on the AUC metric and deploy the model. When you deploy the model , enable Authentication and deploy it using the Azure container services. Once deployed , enable the logs.py in endpoint and enable the application insights because if there are any issues wrt any of the data , application insights page would help us to understand it better. One the Model is deployed in the Swagger host  , we can interact with the deployed model using the Swagger API using the HTTP Post and Get request.  In the swagger page , Post request and gives a Json Input wth the sample dat so here we give the input to interact with the model using the endpoint.py and we get the final prediction of the model.    

![image](https://user-images.githubusercontent.com/92014201/142157410-b3cf6962-53c9-4d82-b884-0d4887b00ab0.png)


*TODO*: Provide an architectual diagram of the project and give an introduction of each step.


### Bank Marketing Data set registered in the Dataset 
![Bank Marketing Dataset registered](https://user-images.githubusercontent.com/92014201/142161294-4be0b700-e370-4985-b5a4-46361a288e7c.png)

### AutoML Experiment submitted 

![image](https://user-images.githubusercontent.com/92014201/142161623-50d25f82-1de2-45b3-b504-0fbe2a23940c.png)

### Selecting the best model for Deployment
Model selection happens based on the Accuracy of AUC Weighted , Voting Ensemble is the best model for deployment 
![image](https://user-images.githubusercontent.com/92014201/142161727-6c852079-670c-4a0e-86a6-7f2cf54cadbb.png)

### Completed Status of the Best Model 
![image](https://user-images.githubusercontent.com/92014201/142162186-01c7c9a0-546c-4037-b00d-81a990f91989.png)
![image](https://user-images.githubusercontent.com/92014201/142162672-6c2b0b45-59f3-44df-b72a-a7deecaf608a.png)

### Best Model showing the Accuracy 
![image](https://user-images.githubusercontent.com/92014201/142162720-01b43ab1-797c-41ad-b0bb-daaa5223b909.png)

### Deploying the Best Model 
 Best Model was deployed using ACI and with Authentication and Deplyed was named as "model-deploy". this can be found in the End Points in Azure tab. Please refer the staus of the Deployed Model in "Deployment State". Once the Model was deployed , logs.py was run to check the logs and enabled the application insights which is quite helpful during the catostrophic events or any major changes in the data. 
 ![image](https://user-images.githubusercontent.com/92014201/142163464-1e2fde68-6d37-49df-8ff8-4741f0b16484.png)
 
### Enabled Application Insights 
 ![image](https://user-images.githubusercontent.com/92014201/142163426-4ae09d7c-b90d-4bcc-9499-71fb771be46d.png)

### Logs.py codes to check the logs 
![image](https://user-images.githubusercontent.com/92014201/142163551-ccd76584-ab6e-4882-b563-4b3a1f185826.png)

### Swagger API 
Once the model is deployed , Swagger  helps us to interact with the model with ease. Model is deployed in the swagger local host 9000 
![image](https://user-images.githubusercontent.com/92014201/142164445-34f858d4-6359-4f95-be5d-88ad86c6f924.png)

### Model Interaction 
Post request can be made to interact with the model , basic sample input request can be found in the data 
![image](https://user-images.githubusercontent.com/92014201/142165534-f0bf3857-3c98-4d42-8e8b-9442e33a4542.png)
![image](https://user-images.githubusercontent.com/92014201/142165540-2ca2bf1a-4c3b-4316-8057-f9e333016397.png)

### Consuming the Deployed Model 
Sample of 2 data points is shared with the endpoint.py to get the prediction of the Model 
![image](https://user-images.githubusercontent.com/92014201/142165845-c124f915-11bc-4e1b-ad1d-c0dfff4fe4ba.png)

### Pipe line End point 

![image](https://user-images.githubusercontent.com/92014201/142165922-05689bd5-3ce4-495c-9923-ab3f29bac1e3.png)

### Pipeline showing status completed 
![image](https://user-images.githubusercontent.com/92014201/142165966-f92d5279-7226-447c-8369-39d9761680f7.png)

### Pipeline run overview 
![image](https://user-images.githubusercontent.com/92014201/142166063-13fc61ef-2853-49c7-bf7f-4775ed5a2cfa.png)

### Published Pipeline run overview 
![image](https://user-images.githubusercontent.com/92014201/142166117-99a383f0-0d28-4668-a00d-d2abbe02583d.png)

### Run Details Widget Pipleline 
![image](https://user-images.githubusercontent.com/92014201/142166198-3025f032-67b9-4a3d-974a-ffc4c9f2b0ba.png)

### ML Studio showing scheduled run 
![image](https://user-images.githubusercontent.com/92014201/142166248-a8342425-a235-4a8f-b2bf-e1391f266b7c.png)




## Key Steps
*TODO*: Write a short discription of the key steps. Remeber to include all the screencasts required to demonstrate key steps. 

*TODO* Remeber to provide screenshots of the `RunDetails` widget as well as a screenshot of the best model trained with it's parameters.

## Screen Recording
*TODO* Provide a link to a screen recording of the project in action. Remember that the screencast should demonstrate:

## Standout Suggestions
*TODO (Optional):* This is where you can provide information about any standout suggestions that you have attempted.
