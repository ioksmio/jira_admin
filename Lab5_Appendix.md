## Further Reading
|Reference         |URL|
|--|--|
|Using AppLinks to link to other applications | go.atlassian.com/cloudapplinks |
|Auditing in Jira applications | go.atlassian.com/cloudauditing |
|Configuring time tracking | go.atlassian.com/cloudtimetrack |

## Best Practices
| Pitfall  | Example Use Case | Best Practice |
|---|---|---| 
| Users can't read menus. | You have some users who are visually impaired. After updating the sidebar colors, they are complaining they cannot read the Jira menus. | Ensure you keep accessibility in mind when changing the colors, especially the contrast between the sidebar and the text/icon colors. Go to webaim.org/resources/ contrastchecker/to check you're meeting accessibility standards.|
| You lost needed auditing records.|You set the auditing retention period to1 month, but the company policy is 6 months. A configuration change was made 6 weeks ago that negatively affected the installation but now you have no record of who did it.|Before changing the auditing retention period ensure you are following your company retention policies.|