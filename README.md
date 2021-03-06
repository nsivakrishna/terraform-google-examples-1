Google Cloud Platform Terraform module examples
=====

Collection of examples for using Terraform with Google Cloud Platform.

Clone the repository:

```
git clone https://github.com/GoogleCloudPlatform/terraform-google-examples.git
cd terraform-google-examples
git submodule init && git submodule update
```

The example directories are all symlinked to their module subdirectories. 

Change to the directory with the example:

```
cd EXAMPLE_NAME
```

Follow instructions in the README.md for the example.

__Table of Contents__

1. [example-lb](#example-lb)
1. [example-lb-http](#example-lb-http)
1. [example-lb-https-gke](#example-lb-https-gke)
1. [example-lb-http-nat-gateway](#example-lb-http-nat-gateway)
1. [example-lb-https-content](#example-lb-https-content)
1. [example-lb-internal](#example-lb-internal)
1. [example-k8s-gce](#example-k8s-gce)
1. [example-gke-nat-gateway](#example-gke-nat-gateway)
1. [example-sql-db](#example-sql-db)
1. [example-vault-on-gce](#example-vault-on-gce)

## [example-lb](https://github.com/GoogleCloudPlatform/terraform-google-lb/tree/master/examples/basic)

**Figure 1.** *example-lb diagram*

<img src="https://github.com/GoogleCloudPlatform/terraform-google-lb/raw/master/examples/basic/diagram.png" width="800px"></img>

Modules used:

- [terraform-google-managed-instance-group](https://github.com/GoogleCloudPlatform/terraform-google-managed-instance-group)
- [terraform-google-lb](https://github.com/GoogleCloudPlatform/terraform-google-lb)

## [example-lb-http](https://github.com/GoogleCloudPlatform/terraform-google-lb/tree/master/examples/basic)

**Figure 1.** *example-lb-http diagram*

<img src="https://github.com/GoogleCloudPlatform/terraform-google-lb/raw/master/examples/basic/diagram.png" width="800px"></img>

Modules used:

- [terraform-google-managed-instance-group](https://github.com/GoogleCloudPlatform/terraform-google-managed-instance-group)
- [terraform-google-lb-http](https://github.com/GoogleCloudPlatform/terraform-google-lb-http)

## [example-lb-https-gke](https://github.com/GoogleCloudPlatform/terraform-google-lb-http/tree/master/examples/https-gke)

**Figure 1.** *example-lb-https-gke diagram*

<img src="https://github.com/GoogleCloudPlatform/terraform-google-lb-http/raw/master/examples/https-gke/diagram.png" width="800px"></img>

Modules used:

- [terraform-google-lb-http](https://github.com/GoogleCloudPlatform/terraform-google-lb-http)

## [example-lb-http-nat-gateway](https://github.com/GoogleCloudPlatform/terraform-google-lb-http/tree/master/examples/http-nat-gateway)

**Figure 1.** *example-lb-http-nat-gateway diagram*

<img src="https://github.com/GoogleCloudPlatform/terraform-google-lb-http/raw/master/examples/http-nat-gateway/diagram.png" width="800px"></img>

Modules used:

- [terraform-google-managed-instance-group](https://github.com/GoogleCloudPlatform/terraform-google-managed-instance-group)
- [terraform-google-lb-http](https://github.com/GoogleCloudPlatform/terraform-google-lb-http)
- [terraform-google-nat-gateway](https://github.com/GoogleCloudPlatform/terraform-google-nat-gateway)

## [example-lb-https-content](https://github.com/GoogleCloudPlatform/terraform-google-lb-http/tree/master/examples/https-content)

**Figure 1.** *example-lb-https-content diagram*

<img src="https://github.com/GoogleCloudPlatform/terraform-google-lb-http/raw/master/examples/https-content/diagram.png" width="800px"></img>

Modules used:

- [terraform-google-managed-instance-group](https://github.com/GoogleCloudPlatform/terraform-google-managed-instance-group)
- [terraform-google-lb-http](https://github.com/GoogleCloudPlatform/terraform-google-lb-http)

## [example-lb-internal](https://github.com/GoogleCloudPlatform/terraform-google-lb-internal/tree/master/examples/simple)

**Figure 1.** *example-lb-internal diagram*

<img src="https://github.com/GoogleCloudPlatform/terraform-google-lb-internal/raw/master/examples/simple/diagram.png" width="800px"></img>

Modules used:

- [terraform-google-managed-instance-group](https://github.com/GoogleCloudPlatform/terraform-google-managed-instance-group)
- [terraform-google-lb](https://github.com/GoogleCloudPlatform/terraform-google-lb)
- [terraform-google-lb-internal](https://github.com/GoogleCloudPlatform/terraform-google-lb-internal)

## [example-k8s-gce-nat-calico](https://github.com/GoogleCloudPlatform/terraform-google-k8s-gce/tree/master/examples/k8s-gce-nat-calico)

**Figure 1.** *example-k8s-gce-calico diagram*

<img src="https://github.com/GoogleCloudPlatform/terraform-google-k8s-gce/raw/master/examples/k8s-gce-nat-calico/diagram.png" width="800px"></img>

Modules used:

- [terraform-google-k8s-gce](https://github.com/GoogleCloudPlatform/terraform-google-k8s-gce)
- [terraform-google-nat-gateway](https://github.com/GoogleCloudPlatform/terraform-google-nat-gateway)

## [example-k8s-gce-nat-kubenet](https://github.com/GoogleCloudPlatform/terraform-google-k8s-gce/tree/master/examples/k8s-gce-nat-kubenet)

**Figure 1.** *example-k8s-gce-kubenet diagram*

<img src="https://github.com/GoogleCloudPlatform/terraform-google-k8s-gce/raw/master/examples/k8s-gce-nat-kubenet/diagram.png" width="800px"></img>

Modules used:

- [terraform-google-k8s-gce](https://github.com/GoogleCloudPlatform/terraform-google-k8s-gce)
- [terraform-google-nat-gateway](https://github.com/GoogleCloudPlatform/terraform-google-nat-gateway)

## [example-gke-nat-gateway](https://github.com/GoogleCloudPlatform/terraform-google-nat-gateway/tree/master/examples/gke-nat-gateway)

**Figure 1.** *example-gke-nat-gateway diagram*

<img src="https://github.com/GoogleCloudPlatform/terraform-google-nat-gateway/raw/master/examples/gke-nat-gateway/diagram.png" width="800px"></img>

Modules used:

- [terraform-google-nat-gateway](https://github.com/GoogleCloudPlatform/terraform-google-nat-gateway)

## [example-sql-db](https://github.com/GoogleCloudPlatform/terraform-google-sql-db/tree/master/examples/mysql-and-postgres)

**Figure 1.** *example-sql-db diagram*

<img src="https://github.com/GoogleCloudPlatform/terraform-google-sql-db/raw/master/examples/mysql-and-postgres/diagram.png" width="800px"></img>

Modules used:

- [terraform-google-sql-db](https://github.com/GoogleCloudPlatform/terraform-google-sql-db)

## [example-vault-on-gce](https://github.com/GoogleCloudPlatform/terraform-google-vault/tree/master/examples/vault-on-gce)

**Figure 1.** *example-vault-on-gce diagram*

<img src="https://github.com/GoogleCloudPlatform/terraform-google-vault/raw/master/examples/vault-on-gce/diagram.png" width="800px"></img>

Modules used:

- [terraform-google-vault](https://github.com/GoogleCloudPlatform/terraform-google-vault)