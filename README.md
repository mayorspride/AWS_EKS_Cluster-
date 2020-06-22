# AWS_EKS_Cluster
This repository contains code for deploying an AWS EKS cluster

__NOTE:__
- This Cluster is provisioned in the us-east-2 region with eksctl using the eks-cluster file which also creates the managed-cluster and two Auto Scaling Group (ng-1 and ng-2) stacks.
- AllowExternal DNSUpdateIAM  policy gives ExternalDNS the necessary IAM permissions to view and manage the hosted zone and it was performed via the AWS web console.
