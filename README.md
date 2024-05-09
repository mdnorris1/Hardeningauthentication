# Hardening Authentication

Restrict Local Accounts
You are the IT security administrator for a small corporate network. You are working to increase the authentication security of the domain. You need to ensure that only authorised users have administrative rights to all local machines. Local users and groups can be controlled through a GPO linked to the domain.

In this lab, the task is to edit the Default Domain Policy and configure the Local Users and Groups policy settings as follows:

Create a policy to update the built-in Administrator local group.
Delete all member users.
Delete all member groups.
Add BUILTIN\Administrator to the group.
Add %DOMAINNAME%\Domain Admins to the group.
The policy you create should remove all members of the built-in Administrators group and then add only the members specified. Use BUILTIN\Administrator and %DOMAINNAME%\Domain Admins in the policy to indicate which accounts to add.



https://github.com/mdnorris1/Hardeningauthentication/assets/147259516/00066b87-4c8f-46e3-884e-ba88be6f408b


You are the IT administrator for a small corporate network. The company has a single Active Directory domain named CorpNet.local. You need to increase the domain's authentication security. You need to make sure that User Account Control (UAC) settings are consistent throughout the domain and in accordance with industry recommendations.

In this lab, your task is to configure the following UAC settings in the Default Domain Policy on CorpDC as follows:

User Account Control	Setting
Admin Approval mode for the built-in Administrator account	Enabled
Allow UIAccess applications to prompt for elevation without using the secure desktop	Disabled
Behavior of the elevation prompt for administrators in Admin Approval mode	Prompt for credentials
Behavior of the elevation prompt for standard users	Automatically deny elevation requests
Detect application installations and prompt for elevation	Enabled
Only elevate UIAccess applications that are installed in secure locations	Enabled
Only elevate executables that are signed and validated	Disabled
Run all administrators in Admin Approval mode	Enabled
Switch to the secure desktop when prompting for elevation	Enabled
Virtualize file and registry write failures to per-user locations	Enabled
User Account Control policies are set in a GPO linked to the domain. In this scenario, edit the Default Domain Policy and configure settings in the following path:
Computer Configuration > Policies > Windows Settings > Security Settings > Local Policies > Security Options.
