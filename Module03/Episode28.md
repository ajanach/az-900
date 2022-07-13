# Role-Based Access Control (RBAC)

## Role (role definition):
- answers the question what can be done? 

<img src="..\Images\role.png" alt="role.png" />

## Security principals:
- answers the question who can do it?
- represent users, group users, applications

<img src="..\Images\securityPrincipals.png" alt="securityPrincipals.png" />

## Scopes:
- answers the quiestion where can it be done?

<img src="..\Images\scopes.png" alt="scopes.png" />

## Role Assignment:
- is group of:
  - role definition
  - security principals
  - scopes

## Role-Based Access Control:
- authorization system built on azure resource manager
- designed for fine-grained access management of azure resources
- role assigment is combination of:
  - role definition - list of permissions like create VM, delete SQL, assign permissions, etc.
  - security principal - user, group, service principal and managed identity
  - scope - resource, resource groups, subscription, management group
- scopes are hierarchical
  - management groups -> subscription -> resource groups -> resources
- built-in and custom roles are supported

