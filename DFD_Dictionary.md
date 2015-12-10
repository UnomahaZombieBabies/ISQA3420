# Data Flow Diagram Dictionary

## Entities
###### Corporate Manager
> *Employee in the corporation responsible for reviewing and approving open source software based off its licenses and vulnerabilities*

###### Corporate Developer
> *Employee in the corporation responsible for developing software and incorporating open source software*
> *Submits open source software contributions for projects she/he is involved*

###### Open Source Repository
> *Outside repository for the open source community, similar to GitHub*

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

## Data Flows  

###### CPE Request
>*Todo*

###### CPE Response
>*Todo*

###### File/ Package License Information
>*Todo*

###### File/ Package License Lookup
>*Todo*

###### Package Vulnerability Lookup
>*Todo*

###### Vulnerability Information Response
>*Todo*

###### CVE Request
>*Using the CPE of a package, request the related CVE information*

###### CVE Response
>*Return the related CVE information given a CPE*

###### CVE Information Load
>*Pass the CVE information to be stored into the database*

###### Project File
>*Code to be checked into the Version Control System*

###### Project File/Info Request
>*For a given project, return the related document, package, and file information*

###### Project File/Info Response
>*The related document, package, and file information for a given project*

###### File/ Package
>*Submission of a file or package to be stored in the SPDX DB with retrieved license and vulnerabilities*

###### File/ Package Response
>*Indication that the submission was successful or not*

###### Updated Codebase
>*Open source software that is contributed back to the open source community*

###### File SHA1 Request
>*Using the SHA1 as an identifier, is this package/file in the database?*

###### File SHA1 Response
>*Yes or No response to notify if the package/file is in the database.*

###### File License and CPE Info
>*For a given file / package, the license, CPE, and CVE information returned from the lookup processes*

###### Project Info Request
>*For a given project, return the related document, package, and file information*

###### Project Info Response
>*The related document, package, and file information for a given project*

###### Project Policy Request
>*Retrieve, add, or update the current policy on vulernabilities and licenses*

###### Project Policy Response
>*Returns the current policy on vulnerabilities and licenses*
