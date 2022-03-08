# GKE Cluster with Terraform

This sample repo creates a VPC and subnet for the GKE cluster. This is not
required but highly recommended to keep your GKE cluster isolated.

The GKE Cluster targets a zone which results in 3 nodes created as a sample terraform workflow. The number of nodes is defined in `variables.tf` with the following code block:

```tf
variable "gke_num_nodes" {
  default     = 3
  description = "number of gke nodes"
}
```

## Development

To develop this project, the terraform CLI is required and can be installed with various methods as shown [here](https://www.terraform.io/downloads).

This project requires a `credentials.json` file which contains the service account to your GCP project.

# WIP

To add deployment of custom resources to the Kubernetes cluster.


## References

- [Provision a GKE Cluster learn guide](https://learn.hashicorp.com/terraform/kubernetes/provision-gke-cluster)
