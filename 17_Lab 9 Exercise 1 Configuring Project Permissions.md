##  Lab 9 Exercise 1 Configuring Project Permissions 
> The Planets App project lead wants only the members of the Development group to be able to create issues in the Planets App project. Members of other teams will only be able to view issues in this project. 
1. View the default permission scheme: 
a. Log in to your cloud site as the Jira administrator, `Dakota Jones`. 
b. Navigate to the `Permission schemes` Jira administration page (under Issues) by 
using the cog icon or the. or `gg` shortcut. 
* **Note**: Here you see two permission schemes. The Default Permission Scheme is the default permission scheme for Business projects. The Default software scheme is the default permission scheme for Software projects. This scheme is associated with your Software project. 
c. Click to open the `Default software scheme`. 
d. Scroll down and view the default permissions. 
* **Note**: A permission scheme associates various permissions (for the project, issues, comments, etc.) with various roles, for example, the Administrators project role. Note that the Browse Projects project permission is assigned to Any logged in user. This means that any user who's logged in to Jira is allowed to see Software projects and the issues within it. The default permission schemes in Jira have an open approach to accessing the projects and issues. If your organization doesn't want to provide that much access to projects, as the Jira administrator, you could edit this scheme, but changes will apply to all new projects. The atlassian-addons-project-access role enables products that extend Jira to have permissions to do their work. 
2. Copy the default permission scheme: 
a. Click the `Permission schemes` link above the name of the scheme to return to that 
page. 
b. In the `Default software scheme` row, click `Copy`. 
c. In the new `Copy of Default software scheme` row, click `Edit`: 
i. Name: `Dev Permission Scheme` 
ii. Description: `Permission scheme for Development projects`. 
iii. Click `Update`. 
* **Question**: As the Jira administrator, could we simply edit the Default software scheme to update the permissions for the Planets App project? 
* **Answer**: It depends. Any changes we make to this default scheme will be shared with all new Software projects that are created. If this is a change all Software projects will use, then you could edit the default scheme. However, if it's a change you think will only apply to this one project (or to a subset of all Software projects) then you need to make a copy of the default scheme and edit the copy. 
* **Note**: If you're going to have a lot of projects and a lot of project schemes, always use a descriptive name and add a description so you can easily see what each one is. 
3. Update the permissions in the scheme: Now we'll update the permissions so that only users who belong to the Development group can create issues. 
a. Click `Dev Permission Scheme` to open the scheme. 
b. In the `Create Issues` permission row, click `Edit`. 
i. Click `Show more` and review the different roles, users, groups, etc. you can 
assign this permission to. 
* **Question**: Can you grant a permission to just the users of a particular Jira product? 
* **Answer**: Yes, you could. If you click Application access, then the dropdown you will see all the Jira products that you have subscribed to. The default, Any logged in user, means any user from any Jira product who's logged in. (Don't change the setting here.) 
ii. Click the radio button to select `Group` then select `Development` (the group 
you created earlier). 
iii. Click `Grant`. 
iv. In the Create Issues row, click `Remove`. 
v. Select `Application access - Any logged in user` and click `Remove`. 
* **Note**: You would also want to update other permissions such as Edit 
Issues, Assign Issues, Resolve Issues, etc. to fully protect the issues in 
this project. For this exercise, we'll just change Create Issues.  
4. Associate new permission scheme with the project: 
a. Return to the `Permission schemes` page. 
b. Click `Planets App` under the Projects column to return to the project. 
c. In the Project settings sidebar click `Permissions`. 
d. Click the `Actions` drop-down and select `Use a different scheme`. 
e. Select the `Dev Permission Scheme` and click `Associate`. 
f. Confirm the name of the scheme is now `Dev Permission Scheme`. 
5. Verify permissions: 
a. At the top of the Dev Permission Scheme page, click `Permission helper`. 
* **Note**: The Permission helper is very useful for verifying permissions or troubleshooting permission issues. You can also get to it by navigating to the `Permission helper` administration page (under System). 
b. Check the permission for a user who is not a member of the Planets App project: 
i. User: `Max Taylor`
ii. Issue: Choose one of your Planets App test issues 
iii. Permission: `Create Issues`
iv. Click `Submit` and confirm he doesn't have the permission. 
v. Check the Create Issues permission for a Planets App project member, `Luis Beck`. 
* **Note**: Just change the name and click `Submit`. 
* **Note**: He has the permission because he's a member of the Development group. 
vi. Close the Permission helper dialog. 

