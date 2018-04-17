# NodeJS1
This is sample Hello-world nodeJS  Application to Deploy with Ansible and Terraform

Terraform steps create scalable, secure infrastructure

steps:
Create IAM policies for S3 code bucket
Create VPC for out infrastructure
Defined Internet gateway
Route table
Created s3 VPC endpoint
subnet Associations
Security Group
Public Security Group
Private Security Group
RDS Security Group
S3 code bucket
compute service
dev server
load balancer
Auto Scaling Group
Route 53

Ansible steps:
Created nodejs.yaml file and configure the required steps to install npm packages and run the Application

Here we already configure load balancer and auto scaling group
We can use cloud watch alarm to send alert notification

Yes, my infrastructure is scalable and secure
we can implement Jenkins Pipeline in such a way that when Developer push any changes to code using github hook it will automatically trigger and deploy to our infrastructure using Jenkins file. or
we can create generic docker images for application when ever developer made changes to code jenkins will trigger the docker images and deploy the code in container in our defined infrastructure.  
