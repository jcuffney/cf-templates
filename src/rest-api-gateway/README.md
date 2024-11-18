# REST API Gateway 

```json
{
    "Resources": {
        "Stack": {
            "Type": "AWS::CloudFormation::Stack",
            "Properties": {
                "TemplateURL": "https://s3.amazonaws.com/com.cuffney.cf-templates/rest-api-gateway/template.json",
                "Parameters": {}
            }
        }
    }
}
```
