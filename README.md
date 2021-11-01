# AZ900-Notes

## IaaS
+ when needed 
+ powerful VMs
+ Cloud Services
  + Security 
  + Backup
  + log analytics
  
+ BAD OS Updates yourself

## PaaS
+ No need to manage OS
+ Use provided App frameworks
+ Lift and Shift

+ BAD less flexible with OS updates etc.

## SaaS
+ Pay as go
+ No Management 
+ Multiple device support
+ No IT (sort of)

+ BAD locked in
+ BAD all access lost in an outage

## Public cloud
+ Shared provider of infra
+ Multi tenants
+ cost controlled
+ BAD loss of detailed control/regulatory requirements

## Private cloud
+ Dedicated to your company
+ Private network
+ Separated from internet
+ Can be hosted on 3rd party premises

+ BAD Higher cost - hardware, IT staff etc.

## Hybrid cloud
+ pub and private
+ better legacy support
+ control sensisitive data and infra

+ BAD complex connectivity
+ BAD data compatibility issues
+ BAD Extra IT skills

## Geography / region / datacenter
24 Geographys :  UK, US etc.
Has 1 or more regions

Every region has multiple datacenters
Private network cables, custom owned

Regions are grouped into regional pairs upgrade in sequence

## Availability zones
+ Physically separate locations within a region
+ 1 or more DCs within an availability zone
+ \>= 3 availability zones within a region
+ Low latency (2ms) networking between availability zones within a region

*Zonal services*
e.g. VMs explicitly deployed to Availability Zones

*Zone Redundant services *
Define them as redundant and AZ deals with the rest

## Resource Groups
Container of resources
Delete all contained resources together
tag for billing
Redeployable with remplates (ARM)

## Subscription
Highest level azure resource
Has a max size
Is a billing unit for invoicing

Free trial, Pay as go, PAYG Dev/Test, Enterprise Agreement

## Management Groups

