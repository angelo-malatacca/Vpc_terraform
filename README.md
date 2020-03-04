## Creation of Vpc, Public & Private Subnets, Nat gateway, Route Tables and Eip in 3 differents Availability Zones

### To create resources run these commands:

| Command  			 | Description 									|
|--------------------|----------------------------------------------|
| terraform init 	 | Initialize a Terraform working directory		|
| terraform validate | Validates the Terraform files 				|
| terraform graph 	 | Create a visual graph of Terraform resources |
| terrafom plan		 | Generate and show an execution plan 			|
| terraform apply 	 | Builds or changes infrastructure 			|
	
You will be asked to choose the region where deploy the infrastructure, for example ``eu-central-1``

### To destroy the resources

| Command 			| Description							   |
|-------------------|------------------------------------------|
| terraform destroy | Destroy Terraform-managed infrastructure |

### For other commands check: https://www.terraform.io/docs/commands/index.html