### Terraform & AWS EKS

### Technologies used:

Terraform, AWS EKS, Docker, Linux, Git

### Project Description:

Automate provisioning EKS cluster with Terraform

### Usage Instructions:

1- Fill in variables into terraform.tfvars

```
vpc_cidr_block =
private_subnets_block =
public_subnets_block =
```

#sample:

![images](images/Screenshot%202023-04-22%20at%205.38.47%20pm.png)

```
terraform init
```

```
terraform plan
```

###### Create VPC and EKS cluster

```
terraform apply
```

![image](images/Screenshot%202023-04-22%20at%205.57.17%20pm.png)

###### Destroy vpc and EKS cluster

```
terraform destroy
```
