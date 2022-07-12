# Networking services

## Azure Virtual Network:
- emulation of physical networking infrastructure
- logically isolated networking compomentes
- segmented into one or more subnets
- subnets are discrete sections
- enable communication of resources with each-other, internal and on-premises
- scoped to a single region
- VNet peering allows cross region communication
- isolation, segmentation, communication, filtering, routing

<img src="..\Images\azureVirtualNetwork.png" alt="azureVirtualNetwork.png" />

## Azure Load Balancer:
- even traffice distribution
- suports both inbount and outbound scenarios
- high-availability scenarious
- both TCP and UDP applications
- internal and external traffic
- port forwarding
- high scale with up to millions of flows

<img src="..\Images\azureLB.png" alt="azureLB.png" />

## VPN Gateway:
- specific type of virtual network gateway for on-premises to aure traffic over the public internet

<img src="..\Images\VPNGateway.png" alt="VPNGateway.png" />

## Application Gateway:
- web traffic load balancer
- web application firewall
- redirection
- session affinity
- url routing
- ssl termination

<img src="..\Images\appGW.png" alt="appGW.png" />

## Content Delivery Network
- define content
- minimize latency
- POP (points of presence) with many locations

<img src="..\Images\CDN.png" alt="CDN.png" />