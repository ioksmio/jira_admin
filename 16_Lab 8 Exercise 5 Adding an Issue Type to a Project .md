##  Lab 8 Exercise 5 Adding an Issue Type to a Project 
1. Return to the `Planets App` project. 
* **Note**: A quick way to get there is to click `Your work` and select Planets App. 
2. Go to the project settings `Issue types` page. 
* **Note**: Here you see the issue types that come with the Kanban project template. You also see the workflow, field configuration, and screen scheme associated with each issue type. One of the team's responsibilities is to update the documentation when they make a change to the app. We'll create a new issue type for that. 
3. Click `Actions - Edit issue types`. 
* **Note**: This takes you to the Modify Issue Type Scheme page for the project in Jira administration. 
4. Click `+ Add issue type`: 
> a. Name: `Document` 

> b. Description (optional): `An update to the documentation` 

> c. Type: `Standard Issue Type` 

> d. Click `Add` 

5. Click `Save`. 

6. Confirm your new Document issue type is now listed in the current 
scheme for the Planets App project. 


This new Document issue type is associated with the: 
a. `Software Simplified Workflow for Project PA` - any new issues created using this 
issue type in this project will follow this workflow. This is the one you edited earlier. 
b. `Default Field Configuration` - any new issues created using this issue type in this project will use the settings in this field configuration. 
c. `PA: Kanban Default Screen Scheme` - any new issues created using this issue type 
in this project will use the screens defined in this scheme. 
* **Note**: You can change the icon shown for an issue type by editing the issue type on the Issue types Jira administration page (under Issues). 

7. Test the new issue type: 
> a. Create a new issue for Planets App and select `Document` for the Issue Type. 
> * **Question**: Why don't you see the Priority field above Description? 
> * **Answer**: Because the changes you made earlier were only for the Bug issue type. This issue type is using the default screen scheme for all other issues in this project. 

> b. Enter a Summary e.g. `Test 5` and click `Create`.