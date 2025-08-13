# Terraform Labs

This repository contains a collection of practical labs and examples for learning and working with Terraform. Each folder represents a different project or concept, designed to help you understand how to use Terraform to provision and manage infrastructure.

## Getting Started

To get started with these labs, you'll need to have [Terraform](https://www.terraform.io/downloads.html) installed on your system.

### Prerequisites

- [Terraform CLI](https://www.terraform.io/downloads.html) installed on your local machine.
- An account with one or more cloud providers (e.g., AWS, Azure, GCP).
- The necessary cloud provider credentials configured on your system.

### Lab Structure

Each lab is contained within its own directory. Inside each directory, you'll find:

- Terraform configuration files (`.tf`).
- A `README.md` file specific to the lab, explaining its purpose and instructions.
- Example `terraform.tfvars` files (if applicable) for customizing the lab.

### Basic Workflow

For each lab, the general workflow is as follows:

1.  **Navigate to the lab directory:**
    ```bash
    cd <lab_name>
    ```

2.  **Initialize the Terraform working directory:**
    ```bash
    terraform init
    ```

3.  **Review the execution plan:**
    ```bash
    terraform plan
    ```

4.  **Apply the configuration:**
    ```bash
    terraform apply
    ```
    This will prompt you for confirmation before provisioning the resources.

5.  **Destroy the resources when finished:**
    ```bash
    terraform destroy
    ```
    This will tear down all the resources created by the lab.

## Contents

A list of the labs included in this repository will go here. You can update this section as you add more labs.

- `aws-s3-bucket`: A basic lab to create an S3 bucket in AWS.
- `azure-resource-group`: A lab to create a resource group in Azure.
- `gcp-storage-bucket`: A lab to create a storage bucket in GCP.
- `aws-ec2-instance`: A more advanced lab to provision an EC2 instance with a security group.

## Contributing

If you'd like to contribute a new lab or improve an existing one, please feel free to open a pull request. Contributions are welcome!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
