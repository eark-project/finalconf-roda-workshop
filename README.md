# E-ARK final conference Workshop Four materials
## *RODA & friends - An open source ecosystem that helps curate your digital information*

### Summary
In this workshop, attendees will have the opportunity to:

1. Get to know the new open-source software that will help them curate digital information in compliance with Open Archival Information System (OAIS);
2. Learn how to install and use each individual tool that is part of this ecosystem;
3. Experiment the software by following a step by step challenge.

### List of software tools

_**Database Preservation Toolkit**_ http://www.database-preservation.com/ - A tool that extracts data from relational databases and converts it to SIARD 2.0 for archival purposes.

_**RODA-in**_ http://rodain.roda-community.org/ - A tool packaging content and preparing it to be transferred and ingested into a preservation service.

_**RODA**_ https://github.com/keeps/roda/ - A long-term preservation digital repository for archival and preservation which implements OAIS functional entities.

_**Database Visualization Toolkit**_ https://visualization.database-preservation.com - A tool to explore the structure and data of an archived database in SIARD 2.0.


### Step by step challange
1. Download RODA-in
 - **Pre-requesites?** Java 8
 - **Where?** http://rodain.roda-community.org/
2. Download DB Preservation Toolkit
 - **Pre-requesites?** Java 8
 - **Where?** http://www.database-preservation.com/
3. Convert a database to SIARD 2.0
 - **Pre-requesites?** Command-line
 - **How to?** See how at http://www.database-preservation.com/#how-to-use
 - **Which database?** A mysql engine will available during the workshop with some sample databases. Hostname, credentials & sample database names will be announced during the workshop.
4. Package the SIARD file and add some metadata
 - **Pre-requesites?** RODA-in, SIARD file
 - **How to?** See how at http://rodain.roda-community.org/#how-to-use
5. Package some files in your hard drive
 - **Pre-requesites?** RODA-in, set of files
 - **How to?** See how at http://rodain.roda-community.org/#how-to-use
6. Transfer packages to RODA
 - **Pre-requesites?** Browser, packages generated
 - **How to?** A RODA instance will be available during the workshop. Hostname & credentials will be announced during workshop. Then, head to RODA and login using provided credentials. After the successful login, do:
    - Menu options _"Ingest > Transfer"_
    - Transfer the packages created in the previous steps by using the _Upload_ action. In the end, use the _Done_ action to complete the upload.
7. Start an ingest process
 - **Pre-requesites?** Browser, login made in RODA
 - **How to?**
    - Select one or all the packages transferred in the previous step, and hit _Process_ action.
    - Change the name of the process so you can easily recognize it.
    - Hit the _Create_ action & the ingest will start briefly.
8. Look at the result
 - **How to?** Look at the _Status_ column. When the status of process you created in the previous step turn into _done_, it means that the process has finished. Just click it, explore the information that will be presented to you & try to find the packages (AIPs) that were created from the packages (SIP) you've transferred.  
