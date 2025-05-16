
## Overview

Azure Resource Manager (ARM) Templates are a JSON implementation of Infrastructure as Code (IaC) for Azure. 

## Benefits

When possible resources are created in parallel when using ARM Templates, making them faster than scripted deployments. 

Resource Manager also has built-in validation to do checks before starting the deployment to ensure it will succeed. 

As a deployment becomes more complex you can break your ARM Templates into smaller reusable components. These smaller templates can be linked together at deployment time. Templates can also be nested inside other templates.

Using [[Azure DevOps]] and [[ARM Templates]] together you can continuously build and deploy your projects as updates are made and complete the CI/CD process.

## ARM Template Parts

schema:

Required section that defines the location of the JSON schema file that describes the structure of JSON data. The version number you use depends on the scope of the deployment and your JSON editor.

contentVersion:

Required section that defines the version of your template. You can use this value to document significant changes in your template.

apiProfile:

Optional section that defines a collection of API versions for resource types.

parameters:

Optional section where you define values that are provided during deployment.

variables:

Optional section where you define values that are used to simplify template language expressions.

functions:

Optional section where you can define user-defined functions that are available within the template. 

resources:

Required section that defines the actual items you want to deploy or update in a resource group or subscription.

output:

Optional section where you specify the values that are returned at the end of the deployment.