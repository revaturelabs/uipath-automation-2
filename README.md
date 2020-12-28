# GitHub Organization Automation

### Project Overview

This project is a UiPath implemented automation that creates a GitHub organization for a new batch of associates at Revature. This automation ensures that this process is handled efficiently and accurately.

#### FlowChart

![](Documentation/GithubOrganizations.png)

### Technologies Used

- UiPath Studio 2020.10.2
- UiPath Assistant
- UiPath Orchestrator

### Functionalities

- Creates a new GitHub organization for a new Batch of associates
- Uses preexisting Google Form responses to add members to the new organization

### Getting Started

In order to run project you will need the following environment(s):

- UiPath Robot or Assistant
- UiPath Orchestrator
- Microsoft Edge

Run the following git command to download the project locally:

```
git clone https://github.com/UiPath-Project3-1/uipath-automation-2.git
```

Connect machine to Orchestrator. _For further instructions see documentation link:_

- https://docs.uipath.com/orchestrator/docs/managing-robots-modern-folders.

In Orchestrator create an asset 'GithubCredential' and update with github username and password. _For further instructions see documentation link:_

- https://docs.uipath.com/orchestrator/docs/managing-assets-in-studio

For a fully unattened automation add a file at the following path:

```
~\Documents\RevatureAutomationFiles\BatchOrganization.txt
```

The file should contain the following information:

```
{
    "BatchName": "BatchName-111",
    "ContactEmail": "contactemail@gmail.com",
    "OrganizationBusiness": ""
}
```

- this file automatically generated if it does not exist on your machine via an attended form

### Usage

### Contributors

### License
