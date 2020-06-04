Example repo for <https://github.com/turnerlabs/fargate/pull/54>

- `cd` to **iac/env/dev**
- Run `terraform init` and `terraform apply`
- Run `fargate service deploy -f docker-compose.yml --compose-all`
- Run `terraform destroy` to cleanup
