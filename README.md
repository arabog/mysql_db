# MySQL Databas
Create a CloudFormation script that deploys a MySQL DB with an associated security group.  

## Bonus Steps
Export a few resources, such as private Subnet IDs, from your previous stack. Then only you can cross-reference the resources from another stack, such as using:  
`Fn::ImportValue: <Exported_value>`  
Use parameters from a separate file to make your template script reusable. In your new template file, use the substitution function, `!Sub "${parameter}` to refer to any parameter variable.  


