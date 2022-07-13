# Security Groups

## Network Security Groups:
- designed to filter traffic to (inbound) and from (outbound) azure resources located in azure virtual network
- filtering controller by rules
- ability to have multiple inbound and outbound rules
- rules are created by specifying:
  - source/destination - IP address
  - protocol
  - port
  - direction
  - priority

<img src="..\Images\NSG.png" alt="NSG.png" />

## Application Security Groups:
- feature that allows grouping of virtual machines located in azure virtual network
- designed to reduce the maintenance effort (assign ASG insted of the explicit IP address)

<img src="..\Images\ASG.png" alt="ASG.png" />