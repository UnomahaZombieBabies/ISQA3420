# Use Case 1

**Title:**
Determine License and Vulnerability Information for Project

**Primary Actor:**
Corporate Manager

**Goal in Context:**
The corporate manager is able to determine license and vulnerability information from provided project information

**Stakeholders:**
* Corporate Manager: To receive clear and relevant project information
* Corporate Developer: To provide the relevant file/package level information
* Project Owner: To clearly understand corporate manager decisions to green/red light a project

**Preconditions:**
* Relevant file/package information is in the SPDX database
* Proper project information has been provided

**Main Success Scenario:**
Corporate manager receives accurate license and vulnerability information for the requested project packages

**Failed End Conditions:**
Corporate manager receives inaccurate or invalid license and vulnerability information for the requested project packages

**Trigger:**
Corporate manager uploads or identifies project information to which license and vulnerability information is provided


# Use Case 2

**Title:**
Supply software to the system.

**Primary Actor:**
Corporate Developer

# Use Case 3

**Title:**
Contributing Back to Open Source Community

**Primary Actor:**
<TBD>

**Goal in Context:**
When the company decides they are going to sell a product that contains open source software with licensing restrictions (such copy left), they are required to contribue the source back to the open source community.

**Stakeholders:**
* Corporate Manager: Marks a project as used externally.  Looks up the projects relevant packages.  Sends notification and packages to the corporate developer.
* Corporate Developer: Receives package list from corporate manager.  Identifies and finds modified packages.  Posts modified packages to the correct web location.

**Preconditions:**
* The company has decided to sell a product which contains software with licensing restrictions

**Main Success Scenario:**
Corporate developer identifies correct source and posts modified source to the open source community.

**Failed End Conditions:**
Corporate developer fails to post the source back to the community or the source is not the relevant source.

**Trigger:**
Corporate manager notifies the corporate developer that we need to contribute the source for a project backup to the open source community. 
