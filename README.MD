
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
