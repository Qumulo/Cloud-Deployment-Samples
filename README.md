# Qumulo Cloud Deployment Samples
Samples for deploying Qumulo Core in AWS using popular orchestration
technologies.  Right now we have a sample template for Terraform, but please
open an issue or PR and we'll add your favorite orchestration technology.

## Terraform
www.terraform.io

`qumulo.tf` contains a terraform template for deploying Qumulo clusters.  Set 
the number of nodes in the `cluster_config` variable (either 1, or 4+).
A tfvars file can be used to provide the necessary variables from your
environment.
