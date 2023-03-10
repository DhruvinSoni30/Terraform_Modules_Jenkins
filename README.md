# How to deploy Jenkins server on AWS using Terraform Modules?


### Prerequisites

Before you begin, you'll need:

* An AWS account
* Terraform installed on your local machine
* AWS CLI installed on your local machine

### Usage

* Clone this repository to your local machine.
* Modify the variables in variables.tf to suit your needs.
* Run `terraform init` to initialize the working directory.
* Run `terraform plan` to preview the changes that will be made to your infrastructure.
* Run `terraform apply` to create the resources.
* Once the resources have been created, you can access Jenkins by navigating to the public IP address of the EC2 instance in your web browser.
* When you are finished using the resources, you can destroy them by running `terraform destroy`.

![1](https://github.com/DhruvinSoni30/Terraform_Modules_Jenkins/blob/main/images/1.png)
