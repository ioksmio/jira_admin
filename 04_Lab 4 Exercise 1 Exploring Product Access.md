## Lab 4 Exercise 1 Exploring Product Access
1. Log in to your cloud site with your  `Jira Login`.
> * **Note**: Remember to always log into the site assigned to you.
2. Click on your `jira site name` under `Organisation`
3. Click `...` on the right side of the table beside the enumurated users and choose `Manage product acces` in the depicted menu.
4. Review the existing product access and answer the questions below.
> * **Question**: What products do new users have access to by default?
> * **Answer**: New users have access to Jira Service Management by default. Note the green check.
> * **Question**: If a user joins your site and is given access to only Jira Software what
group will they be placed into by default?
> * **Answer**: A new Jira Software user will be placed into the jira-software-users group
by default. Note the DEFAULT ACCESS GROUP indicator by the product.

5. Remove the `jira-software-users` group from Jira Software product access by clicking Options (...) next to that group and selecting `Remove group`.
> * **Question**: Were you successful?
> * **Answer**: No. You cannot remove a default access group. Each product needs at least one default group to assign users to when they are given product access.
> * **Question**: How many licenses are used for Jira Software?
> * **Answer**: Look at the numbers next to the Jira Software product name. Make a note
of this number.
> When users log in to your site they'll land in Jira. See the note in the What
you need to know box on the right. Optionally, click `Change this setting`. View the
dropdown but don't change the setting. 
6. To grant or deny product access requests 
>* a. Click `Your Site Name` in the Side Bar `Access requests`.

>* b. Click `Site Access`
* **Note**: Here you can grant or deny product access requests from users. A teammate may have sent them the product URL but your site settings don't allow them to self- signup. In that case, they'll see a button to request access when they try to access your site.