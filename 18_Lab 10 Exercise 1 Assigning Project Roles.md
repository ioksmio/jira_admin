## Lab 10 Exercise 1 Assigning Project Roles 
> For the Planets App project, the project administrator will be the project lead. We've already assigned Sophie Nguyen as the project lead. Note that Jira administrators can always administer projects.
1. Set the project administrator: 

> a. Log in to your cloud site as the Jira administrator, `Dakota Jones`. 

> b. Navigate to the `Planets App` project settings `People` page. 

> c. Click `Add people`. 

> i. Start typing `sophie` and select `Sophie Nguyen`. 

> ii. Click the role dropdown and select `Administrators`. 

> iii. Click `Add`. 
* **Note**:As a project administrator, Sophie can now update this project's details (name, description, avatar, and URL). She can also edit the project lead and project role memberships, change the project type, and define components and versions. She cannot however edit the project's schemes. Only the Jira administrator can do that. Managing project role membership is the most important responsibility of a project administrator. 

2. Set the Default Assignee: 

> a. Using your incognito window, go to your site bookmark and log in as `Sophie 
Nguyen`, the new project administrator. 
* **Note**: If you see onboarding screens, skip the questions or select whatever options you like. 
* **Note**: If you see a large blue sidebar and no top menu, click Sophie's avatar. Click `Try the new navigation` if you see this option. If you don't continue with the existing navigation. 

> b. Navigate to the `Planets App` project settings. 

> c. On the `Details` page, view the Default Assignee is Unassigned. 
* **Note**: When a new issue is created, if the assignee is not specified, the project's Default Assignee is used. You can either choose Project Lead or leave it as Unassigned. The Unassigned option is only available if the `Allow Unassigned Issues` setting in Jira’s General configuration is set to ON (this is the default). Additionally, settings in the Component section of the project's configuration may override the Default Assignee for any issues that have the Component field set. 

> d. For Default Assignee, select `Project Lead` and click `Save details`. 

> e. Navigate to the `Summary` project settings page. 
* **Note**: You can also view who's the Project lead and the Default Assignee in the Roles section of the Summary page.

> 3. Optionally, verify the default assignee for the project: 

> a. Log out as Sophie and log back in as `Luis Beck`, a member of the Development group. 

> i. If you see onboarding screens, skip the questions or select whatever options you like. 

> ii. If you see a large blue sidebar and no top menu, click Luis's avatar. Click `Try the new navigation` if you see this option. If you don't continue with the existing navigation. 

> iii. Create an issue for the `Planets App` project e.g. Test 6. 

> iv. Open the issue and verify the assignee is `Sophie Nguyen`. 

> v. Log out as Luis. 