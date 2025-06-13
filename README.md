# webapp-on-EKS

Person A, a member of the DevOps team of a famous Korean company, will be in charge of a project to develop a new web applications. The application should be satisfied with the following:

Quickly reflect changes when new requests are occurred
Easy scaling
Operate and develop application with fewer people
After confirming the above requirements, Person A decided to build Modern Application, and after discussing with team members, A wants to build the web application through MSA, container, CI/CD. And they choose kubernetes as container orchestration tool based on majority opinion.

There are few team members and not enough time to work directly to build everything by using open source. Expanding infrastructure is also a pain point. And there are some people who don't know Kubernetes precisely.

At this point, Person A found out managed kubernetes service, Amazon Elastic Kubernetes Service . And to understand the advantages and characteristics of the Amazon EKS, A determined to do simple PoC(Proof of Concept)!

-Build a workspace with AWS Cloud9
-Create container image using Docker
-Upload container images to Amazon ECR
-Deploy Amazon EKS clusters and services
-Explore Container Insights
-Auto-Scaling Pod and Cluster
-Deploy service with AWS Fargate
-Build CI/CD Pipeline

