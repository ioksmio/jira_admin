## Further Reading
|Reference         |URL|
|--|--|
|Managing global permissions | go.atlassian.com/cloudglobalperms |

## Best Practices
| Pitfall  | Example Use Case | Best Practice |
|---|---|---| 
| Unknown public users can perform operations only Jira non-public users should be able to perform. | The Public group was assigned the Browse users and groups global permission by mistake. A malicious person was able to find out all the names of internal users at the company without even logging in. | You should be careful about using Public with Global Permissions, especially for public or production instances. The Public group grants the permission you've chosen to non-logged-in users|