# terraform-http-alb-sample

This TF Project creates:
- 2 EC2 Instances
- 2 Security Groups
- An ALB
- An ALB Target Group
- A Target Group Attachment to ALB
- ALB Listener


Look at the file named `providers.tf` to setup your aws account creds.

Clone the project and just run below commands
```
terraform init
terraform plan
terraform apply
```
