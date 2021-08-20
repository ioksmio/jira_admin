##  Lab 5 Exercise 3 Configuring Auditing
1. Navigate to the `Audit Log` administration page (under System).
* **Note**: Here you see the key configuration changes in Jira. Auditing is a tool to aid you in troubleshooting or for security purposes.
2. Click `Show more` for one of the changes and view the operation details.
3. Update the retention period:
> a. Click `Actions` then `Audit Log Settings`.

> b. Click the Retention period dropdown and select `6 months`.
* **Note**: Before changing this setting at your site ensure you are following your company retention policies.
* **Note**: You can also hide events triggered by your external user directory from appearing in the audit log.

> c. Leave Hide external user directory unchecked and click `Save`. 
4. Search for log entries:
> a. To find all the configuration changes related to project roles in the past day: 

> i. In the Contains text box, enter `Project role`.

> ii. Click Time and select `Within the last 1 days`. 
 
> iii. Click `Update`.
5. If no entries are returned, change the search.
6. Optionally, click `Export` then `Export` again to export the audit log to a .csv file.
* **Note**: You can't sort the audit log. But you can export the data to .csv and open it in a spreadsheet application to manipulate the data. When you export the audit log, all the events are included in the export, even if you currently have filtered the audit log results in the page.