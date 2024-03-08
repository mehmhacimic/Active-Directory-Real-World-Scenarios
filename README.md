
<h1>Active Directory Real-World Scenarios</h1>
This tutorial provides a few examples of on-the-job scenarios you might encounter when using Active Directory.


<h2>Video Demonstration</h2>

- ### [YouTube: On-the-job Active Directory Scenarios](https://www.youtube.com) * **COMING SOON** *

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (22H2)
---
**1. Scenario: User Account Management**

  Objective: Create, modify, and manage user accounts within Active Directory.

  Steps:
  * Open Active Directory Users and Computers (ADUC) on the Domain Controller.
  * Create a new user account for a new employee, specifying relevant details.
  * Modify an existing user account, adjusting permissions or group memberships.
  * Disable or delete a user account for an employee who has left the organization.

**2. Scenario: Group Policy Application**

  Objective: Implement Group Policies to enforce security and configuration settings.

  Steps:

  * Open Group Policy Management Console (GPMC) on the Domain Controller.
  * Create a new Group Policy Object (GPO) for password policies, specifying complexity requirements.
  * Link the GPO to an Organizational Unit (OU) containing user accounts.
  * Implement a GPO to control desktop background settings or restrict access to specific applications.
  * Ensure policies are successfully applied by running *gpupdate* /force on client machines.

**3. Scenario: Active Directory Replication Monitoring**

  Objective: Monitor and troubleshoot Active Directory replication for optimal performance.

  Steps:
  * Open Active Directory Sites and Services on the Domain Controller.
  * Review replication topology to ensure efficient communication between domain controllers.
  * Monitor replication status using the *repadmin* command-line tool.
  * Troubleshoot replication issues, such as lingering objects or connectivity problems.
  * Schedule regular replication consistency checks and address any reported errors.
