### Terraform GCP for GAC's TSP

##### GKE用户关心的几个点的相关文档
- GKE快速上手
> https://cloud.google.com/kubernetes-engine/docs/deploy-app-cluster

- GKE Node和Pod的网络划分
> https://cloud.google.com/kubernetes-engine/docs/how-to/alias-ips

> https://cloud.google.com/kubernetes-engine/docs/concepts/network-overview

- Pod如何访问外网第三方服务和API? 

如果承载Pod的Node(GCE虚拟机)自己带有Public IP的话，就可以直接访问互联网；如果Node不带有Public IP的话，通过创建VPC的Cloud NAT网关来访问公网，Pod就算在Secondary IP Range里面也可以通过VPC的NAT访问互联网
> https://cloud.google.com/nat/docs/gke-example

- Pod如何访问内网或者GKE的其他产品和服务，比如RDS数据
> https://cloud.google.com/memorystore/docs/redis/connect-redis-instance-gke

> https://cloud.google.com/sql/docs/mysql/connect-kubernetes-engine

> https://medium.com/google-cloud/connecting-cloud-sql-kubernetes-sidecar-46e016e07bb4

- GKE版本和升级相关文档
> https://cloud.google.com/kubernetes-engine/versioning 

- Service Account
> https://cloud.google.com/kubernetes-engine/docs/how-to/kubernetes-service-accounts

### Terraform for GCP Resource
> https://github.com/GoogleCloudPlatform/gke-poc-toolkit

> https://github.com/GoogleCloudPlatform/gke-enterprise-mt

> https://github.com/GoogleCloudPlatform/gke-terraform-generator

> https://github.com/GoogleCloudPlatform/terraform-google-secure-cicd

> https://github.com/GoogleCloudPlatform/solutions-terraform-cloudbuild-gitops

> https://github.com/terraform-google-modules/terraform-google-kubernetes-engine

### Terraform BluePrints
> https://cloud.google.com/foundation-toolkit

### Cloud Foundation Toolkit
> https://cloud.google.com/docs/terraform/blueprints/terraform-blueprints

### Security Foundations Blueprint
> https://cloud.google.com/architecture/security-foundations

> https://github.com/terraform-google-modules/terraform-example-foundation

> https://github.com/search?q=topic%3Acft-terraform+org%3Aterraform-google-modules&type=Repositories
