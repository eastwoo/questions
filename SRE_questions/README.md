# SRE assignments
## Q1

Provisioning the EKS cluster in AWS:
1. Each subnets have at least 1024 ip address
2. Some endpoints need to accessed through public internet
3. Two ASGs, one is running on-demand instances, the other is running spot instances.

## Q2
Provining the ingress controller

1. Using NLB as the entry
2. Two ingress controller, one is internet-facing, the other one is internal

## Assignment contents
1. Infrastructure code to provisioning EKS cluster
2. Commands to run for provisioning

Hint: you can use terraform code or script for the provisioning

## how to upload your assignments
You can raise a PR with the code you need to upload
