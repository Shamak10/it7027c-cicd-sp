# it7027c-cicd-sp

IT 7027C Module 13: a GitHub Actions pipeline that gates Terraform provisioning.

- **Pull request to `main`:** `terraform init`, `terraform validate`, `terraform plan`
- **Push to `main`:** `terraform apply -auto-approve`

`main.tf` uses the Docker provider to run a single nginx container on the ephemeral GitHub-hosted runner.
