# Resources, Resource Groups and Resource Manager

## Resources:
- object to manage services in Azure
- Represent service lifecycle

<img src="..\Images\resources.png" alt="resources.png" />

- Objects used to manage services in Azure
- Represent service lifecycle
- Saved as JSON definition

<img src="..\Images\resourceJSON.png" alt="resourceJSON.png" />

## Resource Groups:
- grouping of resources
- holds logically related resources
- organizing by:
    - type
    - lifecycle
    - department
    - billing, location or combination of those

<img src="..\Images\resourceGroups.png" alt="resourceGroups.png" />

- each resource must be in one, and only one resource group
- resource group have their own location assigned (this location is only use to store metadata)
- resource in the resource group can reside in different location
- resource can be moved between reousce group
- resource groups can't be nested

## Resource Manager:
- user can manage your resources using az portal, rest, powershell, cli and SDKs
- unified language
Azure resource manager is connected with azure ad

<img src="..\Images\resourceManager.png" alt="resourceManager.png" />