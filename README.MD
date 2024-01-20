Git Commands
-------------------

Git commands and process
---------------------------
Create repo - terraform in vsc
create repo - git hub
$ git init
$ git branch -M main
$ git remote add origin <ssh>

terraform commands
------------------------
$ terraform init
$ terraform plan
$ terraform apply
$ terraform apply -auto-approve
$ terraform destroy -auto-approve

$ terraform plan -var="instance-type=t3.medium"
$ terrafrom plan -var-file="roboshop.vars"

$ terraform apply -var-file=dev/dev.tfvars
$ terraform apply -var-file=prod/prod.tfvars

$ terraform init -reconfigure -backend-config=dev/backend.tf # use while switching the environments

terraform access keys
---------------------
AKIA22DFFKLYQZ46ASGE
aBvvb11zr15ZfpOifLza0/TpPhZDF4mY8uacsu0P