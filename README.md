# Terraform Apply

## Usage

```yaml

    - name: terraform apply
        uses: clockwork-marketing-uk/actions-terraform-apply@1.0.0
        with:
          path: my-terraform-config
          label: production
          var_file: env/prod.tfvars
          backend_config_file: env/prod.backend

```
