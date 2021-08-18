## Lab 4 Exercise 1 Exploring Product Access
1. Log in to your cloud site as the `site administrator`.
* **Note**: Remember to always log into the site assigned to you.
2. Click the cog icon (Settings) in the menu and select `User management`. 
3. Click `Product access` (under SITE SETTINGS).
4. Review the existing product access and answer the questions below.
* **Question**: What products do new users have access to by default?
* **Answer**: New users have access to Jira Service Management, Jira Software, and
Confluence by default. Note the green check for each product.
* **Question**: If a user joins your site and is given access to only Jira Software what
group will they be placed into by default?
* **Answer**: A new Jira Software user will be placed into the jira-software-users group
by default. Note the DEFAULT ACCESS GROUP indicator by the product.
* **Question**: Which groups have access to all products on this site?
* **Answer**: The administrators and site-admins groups have access to all products on
this site.
5. Make the administrators group the default group for Confluence by clicking Options (...) next to that group and selecting `Make this group default`.
* **Question**: Were you successful?
* **Answer**: No. You cannot make a group with administration access a default access
group for a product. If you could, that would mean that any new users that were given access to Confluence would automatically be administrators for Confluence and Jira too!
6. Remove the `jira-software-users` group from Jira Software product access by clicking Options (...) next to that group and selecting `Remove group`.
* **Question**: Were you successful?
* **Answer**: No. You cannot remove a default access group. Each product needs at least
one default group to assign users to when they are given product access.
* **Question**: How many licenses are used for Jira Software?
* **Answer**: Look at the numbers next to the Jira Software product name. Make a note
of this number.
* **Question**: What product will users land in when they log into your site?
* **Answer**: When users log in to your site they'll land in Jira. See the note in the What
you need to know box on the right. Optionally, click `Change this setting`. View the
dropdown but don't change the setting. 
7. In the sidebar, click `Access requests`.
* **Note**: Here you can grant or deny product access requests from users. A teammate may have sent them the product URL but your site settings don't allow them to self- signup. In that case, they'll see a button to request access when they try to access your site.