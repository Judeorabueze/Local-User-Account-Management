# Local User Account Management

## Introduction
I created this project to demonstrate my ability to manage user permissions in Windows environments. It details the process of creating a new user account on a Windows 11 virtual machine and assigning administrative privileges using the Local Users and Groups Management Console (lusrmgr.msc).

This task was completed in response to a training ticket assigned during my hands-on Practical Help Desk course with TCM Academy. The goal was to add a new user and assign administrative privileges on a Windows 11 VM.

### Ticket

![Ticket](https://github.com/Judeorabueze/Local-User-Account-Management/blob/main/Ticket.PNG)

## Objectives
- Create a new local user account named Richard.
- Assign administrative rights to the new user.
- Enforce password change at next logon.
- Demonstrate proper use of Windows local user management tools.

## Tools and Technologies
- Operating System: Windows 11 (Virtual Machine).
- Administrative Tool: Local Users and Groups (lusrmgr.msc).
- Environment: Virtualized home lab.

## Methodology / Approach Adopted
- Open VirtualBox Hypervisor and start Windows 11 Virtual Machine.
- Search for Run and open the Run prompt.
- Enter lusrmgr.msc and click OK.

![Run](https://github.com/Judeorabueze/Local-User-Account-Management/blob/main/Run.png)

(lusrmgr.msc represent Local Users and Group Management Service) This will open the Local Users and Groups page.
- Double click on the Users folder to open.
- Right click in the Users folder and select New User.
  
![Users](https://github.com/Judeorabueze/Local-User-Account-Management/blob/main/User%20page.png)


