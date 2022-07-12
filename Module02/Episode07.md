# Geographies, Regions and Availability Zones

## Data Center:
- physical facility
- hosting for group of networked servers
- own power, cooling and network infrastructure

<img src="..\Images\dataCenter.png" alt="costPerUnit.png" />

## Regions:
- geographical area on the planet
- one but usually more datacenters connected with low-latency network (<2 ms>)
- location for your services
- some services are available only in certain regions
- some services are global services, as such are not assigned/deployed in secific region
- globally available with 50+ regions
- special government regions
- special partnered regions

- azure speed test: https://azurespeedtest.azurewebsites.net/
- products available in specific region: https://azure.microsoft.com/en-us/global-infrastructure/services/

<img src="..\Images\regions.png" alt="regions.png" />

## Availability zones:
- Regional feature
- grouping of physically separate facilities designed to protect from data center failures
- if zone goes down other continue working

<img src="..\Images\availabilityZones.png" alt="availabilityZones.png" />


## Region Pairs:
- each region is paired with another region making it a region pair
- region pairs are static and cannot be chosen
- each pai resides within the same geography
- physical iolation with at least 300 miles distance
- Some services have platform-provided replication
- Planned updates across the pairs

<img src="..\Images\regionPairs.png" alt="regionPairs.png" />

## Geographies
- discrete market
- typically contains two or more regions
- ensures data residency, sovereignty, resilienca, and compliance requirements are met
- fault tolerant to protect from region wide failures
- each region belong only to one geography

<img src="..\Images\geographies.png" alt="geographies.png" />

