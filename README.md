# provisioning-azure-with-terraform

This repository contains sample Terrform scripts for provisioning Azure infrastructure.

## Prerequisites
In order to deploy Terraform scripts from this repository you will need:
* [Terraform CLI tool](https://www.terraform.io/)
* [Azure CLI](https://docs.microsoft.com/pl-pl/cli/azure/install-azure-cli)
* Azure subscription

## Applying
Before applying Terraform scripts review changes to be applied with `terraform plan`.

Use `terraform apply` to deploy infrastructure.

## Destroying
You can destroy resources created by `terraform apply` by running `terraform destroy` command.