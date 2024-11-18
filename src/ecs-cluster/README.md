## ECS Cluster 

```json
{
    "Resources": {
        "Stack": {
            "Type": "AWS::CloudFormation::Stack",
            "Properties": {
                "TemplateURL": "https://s3.amazonaws.com/com.cuffney.cf-templates/ecs-cluster/template.json",
                "Parameters": {
                    "ClusterName": "cuffney-dev-cluster",
                }
            }
        }
    }
}
```

```bash
aws cloudformation deploy \
    --stack-name cuffney-dev-ecs-cluster \
    --template-file ./template.json \
    --no-fail-on-empty-changeset \
    --parameter-overrides \
        ClusterName=cuffney-dev-ecs-cluster \
    --region us-east-1


aws cloudformation delete-stack \
    --stack-name cuffney-dev-ecs-cluster
```