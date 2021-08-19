##  Lab 8 Exercise 4 Updating Fields & Screens in a Project 
#### View fields:
1. Navigate back to the `Planets App` project settings pages and view the `Fields` page. 
* **Note**: Field configurations define how fields behave, for example, whether they are required or optional, hidden or visible, etc. This field configuration is the system default field configuration (it applies to all the company-managed projects in Jira) and shows all the fields configured, their properties, and where they are used. 
* **Note**: If you edit this system default field configuration, it will apply to all companymanaged projects by default! 
* **Question**: How many screens is the Assignee field used on? 
* **Answer**: You'll see the number of screens listed on the right. Click the link to see all the screens it's used on. 
2. Scroll down and view the `Summary` field. 
* **Question**: ls Summary a required field? 
* **Answer**: The Summary field has a `Yes` in the Required column, so it is required. 
3. Leave the fields at their default configuration. 
#### Edit a screen:
We're going to: 
* Edit the Create Issue screen for bugs 
* Remove a field 
* Move a field to a new location on the screen 
But before we edit the screen, let's look at the default Create Issue screen. 
1. Click `Back to project` at the top of the sidebar. 
a. Create an issue in the `Planets App` project: 
i. Select `Bug` issue type. 
ii. View all the fields that make up this screen. 
iii. Click `Create` before entering anything. 
* **Question**: What happened? 
* **Answer**: You got a message that you must specify a summary of the issue because this is a required field. Note the asterisk, which means it's required. 
iv. For Summary, enter `Test 2`. 
v. Scroll down and notice the `Labels` field (which we'll remove). 
* **Note**: It's a good idea to remove unused fields to simplify the screens and make them easier to use. Labels are useful, but we'll remove the labels field in this exercise as an example. 
vi. Click `Create`. 
b. Navigate to the project settings `Screens` page.
* **Note**: The Screens page shows you the Issue Type Screen Scheme for this project. It lists the two screens used for the issue types in this project. Note that the Bug issue type uses a different screen than the other issue types. 
c. Click the `> icon` beside each screen scheme to expand them. 
* Note that in each screen scheme, all operations (create, edit, view) use the 
same screen (`PA: Kanban Bug Screen` for Bug issue types and `PA: Kanban 
Default Issue Screen` for all other issue types). 
d. Click `PA: Kanban Bug Screen`. 
* **Note**: This took you to the Configure Screen page in Jira administration. 
e. Hover over the `Labels` row and click `Remove`. 
f. Test your screen changes by creating a new issue: 
i. Start to create a Bug in the `Planets App` project. 
ii. Confirm the `Labels` field is no longer there. 
iii. Change the issue type to `Story`. 
iv. Confirm you see the `Labels` field. 
v. For Summary, enter `Test 3`, then click `Create`.
#### Configure fields via issue layout:
1. View the `Test 3` issue you created in the previous step. 
2. Click the `Configure cog icon` in the bottom right of the issue. 
* **Note**: Users with the Administrate Jira global permission or the administer projects project permission can move and hide fields via the issue layout page. The issue layout page is accessed from the `Configure cog icon` in an issue or the `Issue layout` link in the `Project settings sidebar`. 
* **Note**: The instructions asked you to create `Test 3` as a Story. This means you are now editing the `PA: Kanban Default Issue Screen` that is used by `Story issue types`. 
3. In the issue layout page, drag the `Priority field` from the `HIDE WHEN EMPTY` section, so it sits directly under the `Description field` in the `Description fields` section of the issue layout page. 
4. Click `Save changes`.
#### Confirm the **Priority field** is under the **Description field**:
* **Note**: When you move a field using the issue layout page, this impacts the Edit/View issue operations. The changes do not impact the Create issue operation. To confirm that changes made using the issue layout page have taken place, you must view an issue that has already been created. 
1. Create a Story in the `Planets App` project. 
2. For Summary, enter `Test 4`, then click `Create`. 
3. Go to the board in the `Planets App’s project`. 
4. Click `Test 4` (or any other Story you have created) to view the issue. 
5. Confirm that the `Priority field` is under the `Description field`. 
