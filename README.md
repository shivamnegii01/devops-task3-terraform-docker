# DevOps Internship Task 3 - Terraform Docker

## Objective

Provision a local Docker container using Terraform.

## Tools Used

- Terraform
- Docker
- Git
- GitHub

## Infrastructure

Terraform is used to create an Nginx Docker container.

### Container Configuration

- Image: nginx:latest
- Container Name: terraform-nginx
- Internal Port: 80
- External Port: 8080

## Terraform Workflow

The following Terraform commands were used:

```bash
terraform init
terraform plan
terraform apply
terraform state list
terraform destroy