cp -r vpshere rancher-for-issue-xyz
touch rancher-for-issue-xyz/terraform.tfvars # Populate this file with the required variables and other customizations
terraform apply -var-file terraform.tfvars
terraform destroy -var-file terraform.tfvars # Delete once done

