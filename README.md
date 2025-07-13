## Introduction
Hi! This is my repository for my AWS Dask-Geopandas experiment. It is so exciting, isn't it?

We will be using Terraform to define the infrastructure using AWS Elastic Kubernetes Service. 
Once that is done up, we will spin up a Dask-Geopandas cluster and give it a proper test drive.

Update: EKS is a little to expensive for me to leave up. Terraform/Kubernetes/Dask worked great - see notebook.

Dask-Geopandas gave me some dependency trouble. Things between the client and Dask workers need to match. Will revisit this when I have a proper k8s cluster up.