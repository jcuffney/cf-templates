# CloudFormation Templates

> Reuseable cloud formation templates for various AWS services.  Meant to be building blocks for larger applications.

![primary](https://github.com/jcuffney/cf-templates/actions/workflows/primary.yml/badge.svg)

#### Cloudformation Templates

- [x] hosted-zone // [README](src/hosted-zone/README.md)
- [x] http-api-gateway // [README](src/http-api-gateway/README.md)
- [x] rest-api-gateway // [README](src/rest-api-gateway/README.md)
- [x] static-spa-website // [README](src/static-spa-website/README.md)
- [x] ecs-cluster // [README](src/ecs-cluster/README.md)
 
#### CI/CD

1. Validate all folders in `/src` to contain a valid `template.json`
2. Copy everything from `/src` to `s3://${BucketName}` per `/infra`
