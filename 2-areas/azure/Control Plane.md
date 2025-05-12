
# Overview

The Control Plane is responsible for managing and configuring Azure resources. It handles operations like creating, updating and deleting resources.

Requests for Control Plane operations are sent to the [[Azure Resource Manager]] via a unified endpoint, [management.azure.com](https://management.azure.com). ARM authenticates the request and forwards it to the appropriate resource provider to complete the operation.

## Characterisitcs

- Authentication is typically done via Microsoft [[Entra ID]] using Azure [[Role Based Access Control]].
- Operations are management-focused and do not directly interact with the data or runtime capabilities of the resources.
- Even during Control Plane outages [[Data Plane]] operations may still function as they use separate endpoints.