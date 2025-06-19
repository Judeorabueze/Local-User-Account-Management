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

<b>1. Add a local user "Richard" and set the user's password to ask for a change at next logon.</b>
- Open VirtualBox Hypervisor and start Windows 11 Virtual Machine.
- Search for Run and open the Run prompt.
- Enter lusrmgr.msc and click OK.

![Run](https://github.com/Judeorabueze/Local-User-Account-Management/blob/main/Run.png)

(lusrmgr.msc represent Local Users and Group Management Service) This will open the Local Users and Groups page.
- Double click on the Users folder to open.
- Right click in the Users folder and select New User.
  
![Users](https://github.com/Judeorabueze/Local-User-Account-Management/blob/main/User%20page.png)

In the New User account setup page:
-	Enter the new user’s name – Richard (As contained in the Ticket).
-	Set a password for the new user.
-	Check the box ‘User must change password at next logon’ (As direted in the ticket).

![new user](https://github.com/Judeorabueze/Local-User-Account-Management/blob/main/new%20user.png)

- Click on Create to add Richard to the Users list.

<b>2. Make the user (Richard) a local administrator.</b>
- On the Local Users and Groups page, double-click on Groups. This opens the local groups in the machine.
- Double-click on Administrators to open a box containing members of the Administrators group.

![Administrator](https://github.com/Judeorabueze/Local-User-Account-Management/blob/main/rsz_admina.png)

- Select Add (This will enable us to add a user to the Administrator group).
- Enter the name of the user to be addwd to Administrator group (Richard).

![Richard adm](https://github.com/Judeorabueze/Local-User-Account-Management/blob/main/Richard%20add.PNG)
- Click on Check Names to confirm the name is correct.
- Enter OK to add Richard to Administrator group.

![Richard adm 2](https://github.com/Judeorabueze/Local-User-Account-Management/blob/main/Richard%20add%202.PNG)
- Select OK.

<b>3. Check if pasword change is well set.</b>
- Restart the Windows 11 Virtual Machine.
- Attempt to login as Richard using the login credentials earlier set.
  
![Rich 1](https://github.com/Judeorabueze/Local-User-Account-Management/blob/main/Rich.PNG)
- Enter the password earlier set.

![Rich 2](https://github.com/Judeorabueze/Local-User-Account-Management/blob/main/Rich%202.PNG)

- Feom the screenshot above, the new user (Richard) was prompted to change his password. Click OK.
