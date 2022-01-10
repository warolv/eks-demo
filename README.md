# Install terraform

$ brew tap hashicorp/tap
$ brew install hashicorp/tap/terraform

# EKS Cluster provision with terraform

export AWS_ACCESS_KEY_ID="AWS_ACCESS_KEY_ID"

export AWS_SECRET_ACCESS_KEY="AWS_SECRET_ACCESS_KEY"

export AWS_DEFAULT_REGION="eu-west-2"

terraform init

terraform plan

terraform apply
