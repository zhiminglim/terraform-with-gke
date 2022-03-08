# GKE Cluster with Terraform

This sample repo creates a VPC and subnet for the GKE cluster. This is not
required but highly recommended to keep your GKE cluster isolated.

The GKE Cluster targets a zone which results in 2 nodes created as a sample terraform workflow.

## Development

To develop this project, the terraform CLI is required and can be installed with various methods as shown [here](https://www.terraform.io/downloads).

This project requires a `credentials.json` file which contains the service account to your GCP project.

## References

- [Provision a GKE Cluster learn guide](https://learn.hashicorp.com/terraform/kubernetes/provision-gke-cluster)
