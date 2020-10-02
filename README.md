# aws-api-gateway-lambda

### Deploying a new version
`terraform apply -var="app_version=1.0.1"`

### Rolling Back to an older version
`terraform apply -var="app_version=1.0.0"`

### Cleaning up
`terraform destroy -var="app_version=0.0.0"`
