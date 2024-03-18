# DevOps-Project-Management-Terraform

## Initialize Terraform

```bash
  terraform init -upgrade
```

## Create a Terraform execution plan

```bash
terraform plan -out main.tfplan
```

## Apply a Terraform execution plan

```bash
terraform apply main.tfplan
```

## Clean up resources

```bash
terraform plan -destroy -out main.destroy.tfplan
terraform apply main.destroy.tfplan
```
