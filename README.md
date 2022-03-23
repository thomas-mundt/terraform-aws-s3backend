# terraform aws init


Usage in Terraform
```
module "s3backend" {
    source ="github.com/thomas-mundt/terraform-aws-s3backend"
}
```

```
output "s3backend_config" {
  value = module.s3backend.config
}
```


