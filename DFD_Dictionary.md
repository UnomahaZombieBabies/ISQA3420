# Data Flow Diagram Dictionary

## Entities
###### Corporate Manager
> Employee in the corporation responsible for reviewing and approving open source software based off its licenses and vulnerabilities

###### Corporate Developer

> Employee in the corporation responsible for developing software and incorporating open source software 


## Processes
###### License Scanner  
>*Receives File/Package from Process Manage Code Information*  
>*Sends File/Package License Information to Process Manage Code Information*  

###### Manage Code Information  
>*Primary process for entire Package management*

###### Version Control / Build Server
>*Controls build versions for files & packages*

###### Manage CPE Information
>*Go between process for sending/receiving CPE information between NIST CPE and National Vulnerability Database*

###### Manage Project Information
>*Go between process for sending/receiving project information between the Corporate Manager and SPDX DB*

## Data Stores
###### NIST CPE Information
###### SPDX DB
###### National Vulnerabilty Database
