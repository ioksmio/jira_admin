## Further Reading
|Reference         |URL|
|--|--|
|Managing project roles | go.atlassian.com/cloudprojectroles   |

## Best Practices
| Pitfall  | Example Use Case | Best Practice |
|---|---|---| 
|Issues are getting assigned to the wrong person and aren't being seen by the project team.  | The default assignee for the Pluto app project was set up as the Project Lead. However, the person who was the Project Lead left the team and is working on another project. However, the Project Lead was never changed so issues are still being automatically assigned to her.   | It’s important to set both the Project Lead and Default Assignee correctly for your project. The Default Assignee controls who is tasked with a new issue when it's created.  |
|Assigning users or groups to permission or notification schemes means you need more schemes, which incurs more administrative overhead and possible performance degradation. |I've created copies of the Default Notification Scheme for each of my new projects and I've updated each scheme adding just the users for each of the projects. But it's a lot of work to do this and keep them all maintained. And I've noticed performance is not as good as it was. |Use roles in permission and notification schemes. While you could assign permissions and notifications to users and groups directly, roles are more flexible and sustainable. Also, when you use roles you can delegate some administrative tasks to the project administrator - they can add their users to their project roles. |