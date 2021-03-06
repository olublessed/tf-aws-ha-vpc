### Terraform AWS HA VPC Module

This module is intended to be used for deployment scenarios that require high 
availability deployments for applications deployed within private subnets. 

#### Features

* Multiple Availability Zones
  * NAT Gateways and Bastion Hosts
* Bastion Hosts are deployed as part of an auto scaling group behind a load balancer


#### Diagram

![diagram](https://raw.githubusercontent.com/spohnan/tf-aws-ha-vpc/master/diagrams/ha-vpc.png)