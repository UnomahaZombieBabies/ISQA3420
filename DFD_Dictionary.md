# Data Flow Diagram Dictionary

## Entities
###### Corporate Manager
> Employee in the corporation responsible for reviewing and approving open source software based off its licenses and vulnerabilities

###### Corporate Developer
> Employee in the corporation responsible for developing software and incorporating open source software  
> Submits open source software contributions for projects she/he is involved

###### Open Source Repository
> Outside repository for the open source community, similar to GitHub

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

###### Manage Project Policy Information
>*Process by which all project policies are handled*

###### Contributing Back to Open Source Community
>*Process by which the corporate developer pushes code changes out to the community*

###### CVE Information Retrieval
>*Process that sends request to National Vulnerability Database for CVE information*  
>*Process which receives CVE information to incorporate with managed code*

## Data Stores  
###### NIST CPE Information  
>*Store for all application classes mainly to be used in conjunction with the National Vulnerability Database*

###### SPDX D
>*Repository for all data regarding the development and deployment of an application*

###### National Vulnerabilty Database
>*U.S. government repository of standards-based vulnerability management data represented using SCAP*

###### Project Policy DB
>*Store for all project policies*
