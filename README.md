*NOTE:* This file is a template that you can use to create the README for your project. The *TODO* comments below will highlight the information you should be sure to include.


# Your Project Title Here

In this project , we are going to create a Auto ML to classify whether the client will do a fixed deposit in the bank or not using the conversation and details of the client avaiable in the BankMarketing data. Goal of the project is deploy the Model and consume it. Below is the Architectural diagram and the process flow of the problem. 

## Architectural Diagram

Load the BankMarketing Dataset in the Notebook and run the Automl Pipleline by setting up the Automl config. Choose the best model based on the AUC metric and deploy the model. When you deploy the model , enable Authentication and deploy it using the Azure container services. Once deployed , enable the logs.py in endpoint and enable the application insights because if there are any issues wrt any of the data , application insights page would help us to understand it better. One the Model is deployed in the Swagger host  , we can interact with the deployed model using the Swagger API using the HTTP Post and Get request.  In the swagger page , Post request and gives a Json Input wth the sample dat so here we give the input to interact with the model using the endpoint.py and we get the final prediction of the model.    

![image](https://user-images.githubusercontent.com/92014201/142157410-b3cf6962-53c9-4d82-b884-0d4887b00ab0.png)


*TODO*: Provide an architectual diagram of the project and give an introduction of each step.


![Bank Marketing Dataset registered](https://user-images.githubusercontent.com/92014201/142161294-4be0b700-e370-4985-b5a4-46361a288e7c.png)


## Key Steps
*TODO*: Write a short discription of the key steps. Remeber to include all the screencasts required to demonstrate key steps. 

*TODO* Remeber to provide screenshots of the `RunDetails` widget as well as a screenshot of the best model trained with it's parameters.

## Screen Recording
*TODO* Provide a link to a screen recording of the project in action. Remember that the screencast should demonstrate:

## Standout Suggestions
*TODO (Optional):* This is where you can provide information about any standout suggestions that you have attempted.
