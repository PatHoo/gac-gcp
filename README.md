### Terraform GCP for GAC's TSP

##### GKE用户关系的几个点的相关文档

- GKE 快速上手
https://cloud.google.com/kubernetes-engine/docs/deploy-app-cluster

- GKE Node和Pod的网络划分，
https://cloud.google.com/kubernetes-engine/docs/concepts/network-overview
https://cloud.google.com/kubernetes-engine/docs/how-to/alias-ips

- Pod如何访问外网第三方服务和API? 
如果承载Pod的Node（GCE 虚拟机自己带有public ip的话，就可以直接访问），如果Node不带有public ip的话，通过创建VPC的Cloud NAT网关来访问公网，Pod就算在secondary ip range里面可以通过VPC的NAT访问互联网
https://cloud.google.com/nat/docs/gke-example

- Pod如何访问内网或者GKE的其他产品和服务，比如RDS数据
https://cloud.google.com/memorystore/docs/redis/connect-redis-instance-gke
https://cloud.google.com/sql/docs/mysql/connect-kubernetes-engine
https://medium.com/google-cloud/connecting-cloud-sql-kubernetes-sidecar-46e016e07bb4

- GKE 版本和升级相关文档，
https://cloud.google.com/kubernetes-engine/versioning 

- Service Account (类似于AWS EC2的Role)
https://cloud.google.com/kubernetes-engine/docs/how-to/kubernetes-service-accounts


##### Terraform for GCP Resource
https://github.com/GoogleCloudPlatform/gke-poc-toolkit
https://github.com/GoogleCloudPlatform/gke-enterprise-mt
https://github.com/GoogleCloudPlatform/gke-terraform-generator
https://github.com/GoogleCloudPlatform/terraform-google-secure-cicd
https://github.com/GoogleCloudPlatform/solutions-terraform-cloudbuild-gitops
https://github.com/terraform-google-modules/terraform-google-kubernetes-engine
