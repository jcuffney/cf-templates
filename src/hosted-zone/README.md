# Hosted Zone 

```json
{
    "Resources": {
        "Stack": {
            "Type": "AWS::CloudFormation::Stack",
            "Properties": {
                "TemplateURL": "https://s3.amazonaws.com/com.cuffney.cf-templates/hosted-zone/template.json",
                "Parameters": {}
            }
        }
    }
}
```
