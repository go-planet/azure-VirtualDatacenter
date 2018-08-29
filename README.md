# azure-VirtualDatacenter
ARM Templates and Scripts for Deploying a Virtual Datacenter in Azure
---
## Network
This template Deploys the base networking components for the VDC. The template includes accomodations for a Production and Development subscription linked by VNet Peering

## Firewalls
This is a modified template from Palo Alto that deploys a set of virtual firewalls to be used with the base networking components above. Has an additional HA component that can be deployed as well.

## Identity
This Template deploys the server and network components for an Active Directory and Public facing ADFS setup. Some components are optional and can be disabled when deploying the template.
