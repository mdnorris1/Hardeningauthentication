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




![Screenshot 2024-05-09 224417](https://github.com/mdnorris1/Hardeningauthentication/assets/147259516/5ac7c605-a77c-4524-9872-16013f69b496)





https://github.com/mdnorris1/Hardeningauthentication/assets/147259516/63d2c7d3-21ed-4e9a-a190-e20bfbfe31a9

