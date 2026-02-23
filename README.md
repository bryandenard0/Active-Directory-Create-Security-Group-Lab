# Active Directory Home Lab: Create Security Group

## Project Summary

This lab demonstrates the creation and validation of a security group
within Active Directory. The objective was to simulate a standard
administrative task used to organize users and manage access to network
resources.

This project reinforces foundational Active Directory group management
concepts relevant to IT support and systems administration roles.

------------------------------------------------------------------------

## Environment

-   Windows Server
-   Active Directory Domain Services (AD DS)
-   Active Directory Users and Computers (ADUC)

------------------------------------------------------------------------

## Objectives

-   Create a new security group in Active Directory
-   Verify successful group creation
-   Understand the role of groups in access control

------------------------------------------------------------------------

## Implementation Steps

### Created New Security Group

Using Active Directory Users and Computers (ADUC), a new security group
was created with the following configuration:

**Group Name:** SchoolGroup

The group was created using standard domain defaults appropriate for
centralized permission management.
<img width="1919" height="1079" alt="Created A Group" src="https://github.com/user-attachments/assets/cff38773-1957-4fa4-a1b9-cff05b550577" />

### Verified Group Creation

After creation, the group was located within ADUC to confirm successful
deployment. Group properties were reviewed to ensure correct
configuration and availability for user membership assignment.
<img width="1919" height="1077" alt="Confirmed the group Was created" src="https://github.com/user-attachments/assets/ee19ebce-43ca-4c60-8bd8-b95aadfb3937" />

------------------------------------------------------------------------

## Validation

-   Confirmed SchoolGroup appears in Active Directory
-   Verified group type and scope settings
-   Confirmed the group is ready for user membership and permission
    assignment

------------------------------------------------------------------------

## Skills Demonstrated

-   Active Directory group provisioning\
-   Security group configuration\
-   Access control fundamentals\
-   ADUC administrative navigation\
-   Identity infrastructure management

------------------------------------------------------------------------

## Use Case

This lab simulates the creation of a department or project-based group
used to assign permissions to shared resources such as file shares,
applications, or network services.

------------------------------------------------------------------------

## Future Enhancements

-   Add users to SchoolGroup
-   Assign NTFS or shared folder permissions to the group
-   Apply Group Policy to the group
-   Test access from a domain-joined workstation
-   Automate group creation using PowerShell

------------------------------------------------------------------------

## Author

Home Lab Project -- Active Directory Group Creation
