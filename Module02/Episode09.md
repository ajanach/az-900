# Compute Services

## Virtual Machines (IaaS):
- total controll over the operating system and the software
- bupports marketplace and custom images
- best suited for: 
    - custom software requiring custom system configuration
    - Lift-and-shift scenarios
- can run any application/scenario:
    - web app & web services
    - databases
    - desktop applications
    - jumpboxes
    - gateways

<img src="..\Images\virtualMachine.png" alt="virtualMachine.png" />


## Virtual Machine Scale Sets (IaaS):
- set of identical virtual machines
- built-in auto scaling features
- designed for manual and auto-scaled workloads like web services, batch processing

<img src="..\Images\VMScaleSet.png" alt="VMScaleSet.png" />

### Containers:
- user host's operating system
- emulate operating system
- lightweigh (no O/S)
    - development effort
    - maintenance
    - compute & storage requirements
- respond quiker to demand changes

<img src="..\Images\Containers.png" alt="Containers.png" />

## Azure Container Instances (PaaS):
- simple and fastest way to run container in Azure
- serverless containers
- designed for:
    - small and simple web apps/services
    - background jobs
    - scheduled scripts

<img src="..\Images\azureContainerInstances.png" alt="azureContainerInstances.png" />

## Azure Kubernetes Service (PaaS):
- open-source container orchestration platform
- highly scalable and customizable
- designed for high scale container deployment

<img src="..\Images\azureKubernetesServices.png" alt="azureKubernetesServices.png" />

## App service (PaaS):
- designed as enterprise grade web application service
- supports multiple programming languages and containers

<img src="..\Images\appService.png" alt="appService.png" />

## Azure Functions (PaaS):
- serverless
- two hosting/pricing models:
    - consumption-based plan
    - dedicated plan
- designed for micro/nano-services

<img src="..\Images\functionApps.png" alt="functionApps.png" />

## Summary:
- virtual machine (IaaS)
- VM Scale Sets (IaaS)
- Container (PaaS)
- Azure Container Instances (PaaS)
- Azure Kubernetes Services (PaaS)
- Application Service (PaaS)
- Azure functions (PaaS)