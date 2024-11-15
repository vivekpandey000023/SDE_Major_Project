To implement the concepts discussed in the IEEE paper "Containerization: Cloud Computing-based Inspiration Technology 
for Adoption through Docker and Kubernetes",We followed these steps to set up and deploy a containerized application of 
Customer Churn using both Docker and Kubernetes. 
The goal is to understand containerization for cloud computing and orchestration technologies, 
particularly through Docker and Kubernetes.

In a nutshell we performed the below steps to deply our churn prediction model to docker & Kubernetes:

1. stream_app.py: create a stream_app.py script that both defines our app layout and trigger-able backend logic. 
This logic activates when users interact with different UI components. Crucially, this file is reusable with any model. 

2. model_C=1.0.bin : saved model

3. Docker file : to create docker image

4. deplyment.yaml : to deploy app to kubernetes.

5. requirement.txt : all the dependent libraries .