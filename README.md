# Embedded Apps using Azure DevOps Integration in Microsoft PowerApps
The following embedded web apps will pull data via the Azure DevOps integration.

## Apps overview
**Dependencies:**
- Microsoft Service Health API data.
- Azure DevOps API data. This is run via a run-only user account, handled by the Flow in Microsoft Power Automate.
- PowerApps license.
- Access to SharePoint site.

<hr>

### Interation / Sprint Dates Countdown
![Screenshot showing embedded Azure DevOps current sprint countdown app built in Microsoft PowerApps](https://github.com/morganmcl99/azure-devops-powerapps/blob/f28399f51f94d4d85e0316ce54972684c25adb87/Screenshots/countdown_sprint_release_date_app.jpg?raw=true)

<hr>

### Display Bug Tickets from Azure DevOps
![Displaying bug tickets as an embedded app built in Microsoft PowerApps](https://github.com/morganmcl99/azure-devops-powerapps/blob/fdbafbd3a6813734f001b28fdffcbd5c5a7ec5fa/Screenshots/bug_tickets_azure_devops_ss.jpg?raw=true)
Firstly, set up a new Shared Query by selecting Queries from the left side menu in Azure DevOps admin. Make sure it is a "Shared Query" - this will require you administrator access so you may have to contact your Azure DevOps administrator for this.

As per following screenshot, set the criteria for which tickets to display to the user. These are basically the filters that allow us to tell the API only to pull tickets of a certain type (User Story vs Bug ticket), only with certain tags etc.

![Set up a custom Shared Query in Azure DevOps admin to pull the correct data](https://github.com/morganmcl99/azure-devops-powerapps/blob/1eb17121f136a854853cb82ad7db7a9c4e2b781b/Screenshots/bug_tickets_azure_devops.jpg?raw=true)

<hr>

### Get and display Sprint Goals

<hr>