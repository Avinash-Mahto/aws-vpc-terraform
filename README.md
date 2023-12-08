[![Logo](https://github.com/Avinash-Mahto/aws-vpc-terraform/blob/main/vpc-terraform.png)](https://github.com/Avinash-Mahto/aws-vpc-terraform)

# AWS VPC Terraform Script

## Overview

This Terraform script automates the creation of an AWS Virtual Private Cloud (VPC) with associated components. It's designed to streamline the process of setting up a basic network infrastructure on AWS.

## Prerequisites

Before you begin, ensure that you have the following:

- [Terraform](https://www.terraform.io/downloads.html) installed on your local machine.
- AWS credentials configured with the necessary permissions.

## Usage

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/Avinash-Mahto/aws-vpc-terraform.git

1. Navigate to the project directory:
   ```bash
   cd aws-vpc-terraform
2. Initialize the Terraform configuration:
   ```bash
   terraform init
3. Review and customize the variables.tf file according to your requirements.
4. Review and customize the provider.tf file if needed.
5. Execute the Terraform plan to preview the changes:
   ```bash
   terraform plan
6. Apply the Terraform configuration to create the AWS VPC:
   ```bash
   terraform apply
  You will be prompted to confirm the changes. Type yes and press Enter.

8. Once the script execution is complete, your AWS VPC and associated resources will be provisioned.
   ## Cleanup
   ```bash
   terraform destroy
## Variables

The variables.tf file contains variables that you can customize to tailor the AWS VPC to your specific needs. Review and update these variables before running Terraform.
## Contributing
If you find issues or have suggestions for improvements, feel free to open an issue or create a pull request.
