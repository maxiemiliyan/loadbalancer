# Azure Virtual Machines with Load Balancer Deployment

This project facilitates the deployment of two Azure virtual machines (VMs) and adds them to the backend pool of an Azure Load Balancer. The purpose of this setup is to achieve high availability and distribute incoming network traffic across multiple VMs.

 Prerequisites

Before proceeding with the deployment, ensure you have the following prerequisites in place:

1. Azure Subscription: Obtain an Azure subscription.

## Deployment Steps

Follow these steps to deploy the Azure resources:

### 1. Clone the Repository

Clone this repository to your local machine:

```powershell
git clone https://github.com/maxiemiliyan/loadbalancer.git
```

2. Navigate to the Project Directory
Change your working directory to the project folder:
```powershell
cd loadbalancer
```

3. Modify Parameters
Adjust the parameters in the 'arm_templates/parms.json' files according to your requirements. This file includes settings such as VM size, OS version, admin credentials, and more.

4. Run the Deployment Script

Run the deployment script in the powershell terminal as given in the 'deployments/deploy.ps' file.

5.Folder Structure
The project follows a structured organization:

arm-templates:

1.Contains Azure Resource Manager (ARM) templates for VMs and Load Balancer.
2.Contains Parameter files for the ARM templates and Load Balancer.

Deployment: 
Contains deployment scripts.

6.License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.















