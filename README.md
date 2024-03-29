APO FSO Lab AWS EKS
This code repository is a DevOps project that is a subset of the FSO Lab DevOps project. Its specific purpose is to help automate the deployment of AWS resources via Terraform for the Cisco Full Stack Observability (FSO) series of workshops for AppDynamics partners and customers.

Although these Terraform code templates could be used in a stand-alone fashion, they are actually tightly integrated with the Cisco SRE Terraform Cloud Workspaces in order to trigger deployment of the AWS workshop resources. As changes are committed to this repository, Terraform Cloud automatically initiates a new Plan action.

## AWS Architecture

Here is a diagram of the workshop architecture components that are deployed to the AWS Cloud Platform:  

__FSO Lab DevOps: Workshop Deployment on AWS__
![Workshop_Deployment_on_AWS](./docs/images/FSO-Lab-DevOps-Workshop-Deployment-on-AWS.png)

