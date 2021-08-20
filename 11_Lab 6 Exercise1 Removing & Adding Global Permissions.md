## Lab 6 Exercise1 Removing & Adding Global Permissions
1. View global permissions:
> a. Log in to your cloud site as the Jira administrator, `Dakota Jones`.

> b. Navigate to the `Global permissions` Jira administration page (under System).
* **Note**: On the left, we see the list of permissions. On the right, you can view the users/groups that have the associated global permission.
> * **Question**: Which global permission is available only to members of the various administrators groups?
> * **Answer**: The Administer Jira global permission is only available to members of the various administrators groups.
* **Note**: The View Users link for each group shows what users are in each group but only site administrators can configure users and groups so Dakota, who's a Jira administrator, can't see this information.
Jira also adds the system-administrators and atlassian-addons-admin groups to each permission. These are internal groups managed by Jira.

2. Remove global permissions from groups:
> a. Scroll down and view the `Make bulk changes` permission.
* **Note**: Teams In Space has decided that only administrators, trusted users, and members of the Development group should have the ability to modify a collection of issues in one step.

> b. In the `Make bulk changes` row, click `Delete` for the default group `jira-software-users`. Click `Delete` again to confirm.

> c. Repeat this step to remove the `jira-servicedesk-users` group from Make bulk changes.
**Note**: Because this site was updated from Jira Service Desk to Jira Service Management, the default group is still called jira-servicedesk-users. If it was a brand new site, the default group name would be jira-servicemanagement- users.
3. Add global permissions to groups:
> a. Scroll down to the `Grant Permission` section. 

> b. Select the `Make bulk changes` permission.

> c. Click the Group dropdown.

> * **Question**: What do you think the Public option means here?

> * **Answer**: The Public group grants the permission you've chosen to anyone including non-logged-in users.
* **Note**: Typically, you should avoid using Public with most global permissions, especially for public or production instances. Public includes non-registered and anonymous users. Instead, you should use project permissions to control the access of anonymous users. We'll discuss that in more detail in a later module.

> d. For Group, select `Development` and click `Add`.

> e. Now you should see the Development group listed but noneof the default product access groups.
* **Note**: New groups are not given any global permissions unless you explicitly add them.

> f. In the Grant permission section, view the permissions you can grant.
* **Question**: Which global permission is missing and why?
* **Answer**: The Administer Jira global permission is missing. The only way to assign groups this global permission is through the Product access site administration page. The site administrator can give another group administration access to Jira on the Administration access tab of the Product access page. Then that group will automatically appear in the list of groups for the Administer Jira global permission on this page.

4. Optionally, verify global permission change:

> a. Click `Search` and press `Return` on your keyboard.

> b. On the issue navigator, click the three dots on the top right of the page. You should see an option for `Bulk change`. This confirms Jira administrators have the ability to perform bulk change operations.

> c. Using your incognito window, go to your site bookmark and log in as 
`Max Taylor`. Max is not an administrator and he's not in the Development group.
* **Note**: If you cannot log in to Jira as Max, you may not have completed an earlier lab. As the site administrator, navigate to his user page. Under Access, click the four buttons to give him access to the site and all the products on the site.

> d. If you see onboarding screens, skip the questions or select whatever options you e. like.

> e. Click `Search` and press `Return`.

> f. On the issue navigator, click the three dots on the top left of the page. You should not see an option for `Bulk change`. This confirms that Max does not have the ability to perform bulk change operations.

> g. Log out as Max. 
Congratulations on completing the lab!