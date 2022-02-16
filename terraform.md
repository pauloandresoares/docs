**[<< Voltar](./readme.md)**

<br/>
<div><img src="images/Terraform_Logo.svg" style="max-width:400px;"/></div>

## Terraform


+ Site: https://www.terraform.io/
+ Registry: Módulos, providers https://registry.terraform.io/

## Instalando o Terraform

Ubuntu

```sh
curl -fsSL https://apt.releases.hashicorp.com/gpg | sudo apt-key add -
sudo apt-add-repository "deb [arch=amd64] https://apt.releases.hashicorp.com $(lsb_release -cs) main"
sudo apt-get update && sudo apt-get install terraform
```


CentOS/ RHEL

```sh
sudo yum install -y yum-utils
sudo yum-config-manager --add-repo https://rpm.releases.hashicorp.com/RHEL/hashicorp.repo
sudo yum -y install terraform
```

## Iniciando o terraform

terraform init
terraform plan
terraform apply



terraform.tfstate
terraform.tfvars

Variaveis

Outputs

Data Souces - Serve para ler algo que já exista

VPC na AWS
