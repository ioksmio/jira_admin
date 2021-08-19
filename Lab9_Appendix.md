## Further Reading
|Reference         |URL|
|--|--|
|Managing project permissions   | go.atlassian.com/cloudprojectperms  |

## Best Practices
| Pitfall  | Example Use Case | Best Practice |
|---|---|---| 
|Permissions are being changed for all Software projects to meet the needs of one project that has different requirements than most. | I have a Software project with very specific requirements that are totally different from all other Software projects. I've updated the Default software scheme for that project, but I just realized that a lot of other projects use the Default software scheme.  | The Default software scheme is used for any new Software project. So, any changes you make to this default scheme will be shared with all new Software projects that are created. If this is a change all Software projects will use, then you could edit the default scheme. However, if it's a change you think will only apply to this one project then you need to make a copy of the default scheme and edit the copy. Then associate the copy with the project and edit that.  |