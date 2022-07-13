# Azure Policy

- governance, security, compliance and cost management

- designed to help with resource governance, security, compliance, cost management, etc.
- policies focuse on resource properties (RBAC focused on user actions)
- policy definition - defines what shoud happedn
  - define the condition (if/else) and the effect (deny, audit, append, modify, etc.)
  - example include allowed resource types, allowed locations, allowed SKUs, inherit resource tags
  - built-in and custom policies are supported
- policy initiative - a group of policy definitions
- policy assignment - assignment of a policy definition/initiative to a scope

<img src="..\Images\azurePolicy.png" alt="azurePolicy.png" />

