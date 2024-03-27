# Project Summary
### This is a project to build a comprehensive end-to-end DevOps pipeline to support an organization's internal web application, designed to manage and monitor deliveries across the company. The final DevOps pipeline architecture project deliverable is shown below. Also, the steps in the processes involved in the project delivery are itemized below with links to the documents containing the necessary steps in the individual process. 

## DevOps Pipeline Architecture
![image](https://github.com/HKasie/aks-terraform-main/assets/22567426/3d4582bd-fa46-46d8-8557-c916167581be)


## Project Delivery Process:
### Version control process was embarked by following these [steps #1](https://github.com/HKasie/aks-terraform-main/blob/main/Documentation/Documentation%20-%20version%20control.pdf)

### Next, the application was containerized creating a docker image. The process for creating the docker image entailed the following [steps #2](https://github.com/HKasie/aks-terraform-main/blob/main/Documentation/Documentation%20-%20Docker-containerisation%20.pdf)

### To deploy the containerized application the network services have to be defined and provisioned or setup in Azure using Terraform's infrastructure as code (IaC) to ensure the cluster’s seamless operations and secure communication. Took the following [steps#3](https://github.com/HKasie/aks-terraform-main/blob/main/Documentation/Documentation%20-%20Defining%20network%20services%20with%20IaC.pdf) 

### Implemented the necessary resources using infrastructure as code (IaC) for automating the provisioning of an AKS cluster using these [steps#4](https://github.com/HKasie/aks-terraform-main/blob/main/Documentation/Documentation-%20Defining%20an%20AKS%20cluster%20with%20IaC.pdf).

### Completed the provisioning of the AKS cluster using both the network and aks-cluster modules that were created above by initializing and applying the Terraform project using IaC. Details in [steps#5](https://github.com/HKasie/aks-terraform-main/blob/main/Documentation/Documentation-%20Creating%20an%20AKS%20cluster%20with%20IaC.pdf) 
