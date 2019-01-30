# terraform-eks
Terraform test project to create EKS cluster and kubernetes provider

I'm writing this project based on the basic knowledge shared in the blog post for EKS Introduction in hashicorp.com learn website: https://learn.hashicorp.com/terraform/aws/eks-intro

I want to create an independent EKS module that can be used to create multiple EKS clusters within a single VPC and sharing same subnets.

The goal of this project is just to cover that scenario, and might not be fully reusable unless you have the same need.

