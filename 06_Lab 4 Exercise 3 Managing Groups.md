## Lab 4 Exercise 3 Managing Groups
1. Create a group and add users:

> a. Navigate to your Atlassian startpage by clicking your saved bookmark `bookmark-startpage Atlassian`

> b. Click on the `Administration` button

> c. Click on the link `YourName01.atlassian.net` and Click on `Overview` in the top menu bar. Bookmark this page and save it as `bookmark-Atlassian Admin Overview`

> d. Click `Directory` in the top menu bar

2. Navigate to the `Groups` in the side bar.

> a. Check the number of licences the `jira-software-users-team` has been assigned

> b. Click `Create group`.

> i. For the name, enter `Development`.

> ii. Optionally for the description enter `Members of Development`. 

> iii. Select `Add members in the next step`

> iv. Select `Luis Beck` and `Sophie Nguyen`. 

> vi. Click `Create`.
* **Question**: On the Development group page, note the message on the right that says this group currently has no product access. Do you need to add product access for this group so Sophie and Luis can access the products on this site?
* **Answer**: No, you don't need to add product access for this group. Both members already have default access to all the products on this site through their membership in the default product groups. You only need to be in one group that has product access for you to get access toa product.
3. Explore administrators group access:
> a. Return to the `Groups` site administration page.

4. Set up the Jira administrator:
> a. Add Dakota Jones to the `jira-admins-team`:

> i. On the `Groups` page, open the `jira-admins-team` group. 

> ii. Click `Add members` and add `Dakota Jones`.

> iii. Click to open the `Dakota Jones` user.

> iv. Confirm the `jira-administrators` group is listed in the Groups section. Refresh the page if you don't see it.
* **Question**: What products does Dakota have access to and why?
* **Answer**: Dakota has access to all the products on the site -Jira Software. When we invited her,  she was added to the default product groups.
* **Note**: Being a Jira administrator means you have access to the Jira administration pages and can create company-managed projects. (Note company-managed projects were previously named classic projects).
But to view issues or work in projects you need to be in a group that has the appropriate product access. Teams In Space wants Jira administrators to have access to all products. This may not be the case for all organizations. Some may want to prevent Jira administrators from seeing the actual content and so prevent mistakes with the data. It's up to your organization and its policies whether or not to allow Jira administrators product access.
5. Test access as Dakota:
* **Note**: In these labs, you'll log in and out as various users. To lessen the amount of logging in and out, use different browser windows. However, you can't just open a new tab and log in as another user, as your original tab will be logged in as that user too. You have a few options:

> i. Open an incognito/private window in your current browser.

> ii. Open a separate browser if you have another one installed. For example, if you're using Google Chrome, open Firefox.

> iii. Log out as the current user by clicking their avatar at the bottom of the global sidebar. This method will require a lot of logging in and out!
6. To simplify the instructions, when you need to log in as another user, we'll tell you to use your incognito window, but use the method that works for you.

> a. Open an incognito window, go to your site bookmark, and log in as `Dakota Jones`. Make sure you click `Jira Software YourName01` - the site assigned to you.

> b. If you see onboarding screens, skip the questions or select whatever options you like.
c. If you get prompted to choose navigation, choose `Use improved navigation`.
i. In Jira, click the cog (gear) icon (Settings) in the menu to confirm she still has access to Jira administration.
ii. Click `Search` then enter return on your keyboard.
iii. Confirm Dakota can see some Jira issues, so she has Jira product access. 
iv. Log out as Dakota and minimize the window.