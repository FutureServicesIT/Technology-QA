---
title: What is Microsoft Flow and what can we do with it?
---

Workflow is a general term describing the actions to achieve a specific outcome.

When using Office 365, Microsoft have provided an automation tool called "Microsoft Flow" that will let you make Office 365 itself take actions on your behalf.

## How Flows can be triggered

* Automatically in a SharePoint list or document library (which is a special type of list)
* Manually using a button in the Microsoft Flow app (mobile or web)
* Automatically or manually from Microsoft PowerApps
* Integration with Office 365 apps:
    * Users
    * SharePoint
    * Teams
    * Exchange email
    * OneDrive for Business
    * OneNote
    * Power BI
    * Project Online
    * Skype for Business
    * Yammer
* Integration with other applications - see the [connector list on the Microsoft Docs site](https://docs.microsoft.com/en-us/connectors) for details.

## Strengths

* Uses Azure Connectors to link to 3rd party cloud applications
* Has a mobile app for editing, monitoring and triggering
* Enables cross-site SharePoint workflows
* Enables cross-application workflows
* Has specific approvals function
* Can lookup user profiles
* Has manual trigger buttons
* Can create shareable flows and templates

## Limitations

* Some actions may be blocked by enterprise settings
* Has limitations depending on the license available
* Cannot directly start another flow from a flow
* Cannot copy/paste steps
* Cannot reorder steps
* Everything is user specific (uses user or flow author accounts)

## What about Microsoft PowerApps

PowerApps are mainly designed for mobile use. While they have a web interface as well, the app will show at the same size as the chosen mobile size.

There is a special mode however, available if you chose "Customize Forms" from the PowerApps menu.
WARNING: To delete or reset the customised form, you have to go into *List Settings > Form Settings*. There you can delete the custom form and start again.

Layouts for customized forms for SharePoint are fairly poor at the time of writing. Especially the horizontal layout which sets the field labels too wide and doesn't let you reduce the height of the field containers because of the "error message" label associated with each field. In vertical mode, the error message label overlaps the input field.

## Examples

### Add a new user to Azure Active directory

Use PowerApps to capture the details, use the Azure AD connector to add the user, assign groups, manager, etc.

### Use a button to run an Azure Automation job

### Add/Update/Delete data in an Azure Data Lake
