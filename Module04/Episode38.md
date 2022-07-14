# Azure Service Level Agreement (Azure SLA)

## SLA:
- is a formal agreement between a service provider and a customer
- SLA is a promise of a service's availability(uptime and connectivity)
- availability is a measure of time that a service remain operational

## Azure SLA
- each service has its own SLA
- ranges from 99% to 99.999%
- free service typically don't have an SLA

## Formulas

### Logical AND - adding dependency
-availability of S1 AND S2 = availability(S1) * Availability(S2)
- scenario - azure webiste with SQL backend DB
  - availability = availability(web) * availability(sql)
  - availability = 99.95% * 99.95%
  - availability = 0.9995 * 0.9995
  - availability = 0.99900025
  - availability = ~ 99.9%

### Logical OR - adding redundancy
- availability (both-web) = 100% - (unavailability(web1) * unavelability(web2))
- availability (both-web) = 100% - (0.05% * 0.05%)
- availability (both-web) = 1 - 0.00000025
- availability (both-web) = 0.99999976
- availability (both-web) = 99.9999%
- but if we have in front of this web services load balacncer, than we need to consider about him into our calculations (logical AND)
  - availability = availability(lb) * availability(both-web)
  - availability = 0.9999 * 0.999999
  - availability = 0.99989
  - availability ~ 99.98%

- adding more redundant services have positive SLA impact
- adding more dependent services have negative SLA impact