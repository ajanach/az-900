# Azure Resource Locks

- designed to prevent accidental deletion and/or modification
- used in conjuction with RBAC
- two types of locks
  - red-only - only read action allowed
  - delete - all cations except delete are allowed
- scopes are hierarchical
- management groups can't be locked
- only owner and user access administrator roles can manage locks

<img src="..\Images\resourceLocks.png" alt="resourceLocks.png" />