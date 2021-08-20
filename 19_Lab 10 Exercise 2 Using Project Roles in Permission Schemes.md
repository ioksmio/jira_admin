## Lab 10 Exercise 2 Using Project Roles in Permission Schemes 
>  In the last lab, we updated the Dev Permission Scheme so only members of the Development group could create issues. The Jira administrator needs to create more projects where only the members of the project should be able to create issues. But instead of creating individual permission schemes for each project, we'll update the Dev Permission Scheme to use a project role instead of a group. That way, different users can be in the role in different projects so we can share the one permission scheme.
1. Create project role: 

> a. Return to Dakota's window or log out and log back into your site as the Jira 
administrator, `Dakota Jones`. 

> b. Navigate to the `Project roles` Jira administration page (under `System`). 
* **Note**: Here are the default project roles. We see the Administrators role for administrators in a project. There's also a role, atlassian-addons-projectaccess, that provides project permissions to apps (addons). You also see some roles associated with Jira Service Management projects. Notice the Manage Default Members link. When you create a project, Jira automatically will assign any default members to the project role. The default members can be users and/or groups. 

> c. Scroll down to the `Add Project Role` section and enter: 

> i. Name: `Members` 

> ii. Optional Description: `This project role represents users who are members of 
a project and can create issues in the project` 

> iii. Click `Add Project Role`. 

> iv. Confirm the new `Members` role now appears on the page. We won't define any default members, as the members will be different for each project this is 
used in. 

2. Update the permissions in the scheme: 
Now we'll update the permissions so that only users who belong to the Members role can 
create issues. 

> a. Navigate to the `Permission schemes` Jira administration page (under Issues). 

> b. Click to open the `Dev Permission scheme`. 

> c. In the `Create Issues` row, click `Edit`. 

> i. Click the radio button to select `Project Role`. 

> ii. Select `Members` (the new project role you created earlier) 

> iii. Click `Grant`. 

> iv. In the `Create Issues` row, click `Remove`. 

> v. Select `Group - Development` and click `Remove`. 
* **Note**: Now, the Jira administrator can associate this permission scheme with any project that has the same permission requirements. 
3. Add users to a project role: 

> a. Using your incognito window, go to your site bookmark and log in as `Sophie 
Nguyen`, the project administrator, and project lead. 

> b. Navigate to the `Planets App` project settings `People` page. 

> c. Click `Add people`: 

> i. Search for and select the members of this project `Sophie Nguyen` and `Luis Beck`. 

> ii. From the Role drop-down, select your new role, `Members`. 

> iii. Click `Add`. 

> iv. Verify Luis is listed on the page with the new Members role, and Sophie now 
has two roles in the project - Administrators and Members. 

> v. Click `Add people` again. 

> vi. Cancel to close the dialog. 
* **Note**: You can enter an email address. If the site administrator set Existing users can send invitations to anyone to On in the Site access site administration page, then the project administrator can invite users to join the site and access the project. Even if this setting is Off, the project administrator can invite users in any approved domains here. 
4. Optionally, verify project roles and permissions: 

> a. Return to Dakota's window or log out and log back in as the Jira administrator, 
`Dakota Jones`. 

> b. Open the `Permission helper` at the top of the `Dev Permission scheme` page or go to 
the `Permission Helper` Jira administration page (under System). 

> c. Check the permission for a user who is not a member of the Planets App project. 

> i. User: `Max Taylor` 

> ii. Issue: Choose one of your Planets App test issues 

> iii. Permission: `Create Issues` 

> iv. Click `Submit` and confirm he doesn't have the permission. 

> v. Check the Create Issues permission for a Planets App project member, `Luis Beck`. He has the permission because he's a member of the Members project role in the project. 