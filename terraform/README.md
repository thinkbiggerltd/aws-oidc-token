#### Create infrastructure

1. Follow [README](init/README.md) in folder `init`
2. Execute in this folder (make sure you are looged in using aws cli):
   - `terraform init`
   - `terraform apply`

#### Destroy infrastructure

1. `terraform destroy` in this folder
2. `terraform destroy` in folder `init`

#### Reference Architecture
- https://github.com/WtfJoke/aws-gh-oidc
- https://blog.codecentric.de/en/2022/05/secretless-connections-from-github-actions-to-aws-using-oidc/