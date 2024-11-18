# CloudFormation Templates

> Reuseable cloud formation templates for various AWS services.  Meant to be building blocks for larger applications.

![primary](https://github.com/jcuffney/cf-templates/actions/workflows/primary.yml/badge.svg)

#### Cloudformation Templates

- [x] http-api-gateway
- [x] rest-api-gateway
- [x] static-spa-website
- [x] ecs-cluster
 
#### CI/CD

1. Validate all folders in `/src` to contain a valid `template.json`
2. Copy everything from `/src` to `s3://${BucketName}` per `/infra`
