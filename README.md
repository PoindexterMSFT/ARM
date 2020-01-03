# GTP AAD Demo Lab
## Creates deployments necessary for GTP Demo Lab. End goal is to have all necessary software, permissions, and subnets installed and configured for use.
## Quick start

## Details
* Deploys the following infrastructure:
  * Virtual Network
  * Public IP Address
  * VM
  
## Notes
* The NSG is defined for reference, but is not production ready. Holes are also opened for RDP and public IPs are allocated.
* One VM size is specified for all VMs

## NOTICE/WARNING
* This template is explicitly designed for a lab/classroom environment. A few compromises were made, especially with regards to credential passing to DSC and script automation, that WILL result in clear text passwords being left behind in the DSC/scriptextension package folders, Azure log folders, and system event logs on the resulting VMs. 
