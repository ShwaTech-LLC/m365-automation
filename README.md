# Microsoft 365 Automation by ShwaTech LLC
Welcome to the M365 Automation repo by ShwaTech LLC.
This repo contains simple, useful examples of tools which can help make your work life easier.

## Monitor Email for Important Contacts
* Power Automate Flow

Features:
1. Monitors your mailbox for incoming email
2. Notifies a target mailbox based on From email domain
3. Allows you to specify exclusions before processing
4. Includes the original email body in the notification
5. Composes a custom HTML email body header for the notification recipient

|Download Location|Type|
|-|-|
|[/flow/MonitorEmailForImportantContacts.zip](https://github.com/ShwaTech-LLC/m365-automation/blob/main/flow/MonitorEmailForImportantContacts.zip)|Power Automate Flow|

Import this Power Automate Flow into your environment to monitor your inbox for important emails from high-priority senders.
This Flow will show you how to monitor a mailbox, read the From domain, and compose an email for a Ticketing system or manager containing the original email itself and a header with information about the notification.

#### _Deployment Note_

You should unzip the export file from the link above onto your computer somewhere, change the appropriate parameters of the Flow definition to match your tenant, zip the package back up then import it into your Power Automate environment.

## SharePoint Events Notifier
* Power Automate Flow

Features:
1. Connects to your native Events list on your SharePoint site, like the one on your tenant's homepage
2. Sends you email reminders for upcoming events
3. Configurable to any number of days in the future
4. Can pull from any SharePoint events list (based on the Calendar list template)
5. Email format is a simple, styled HTML table rendered using easily modifiable variables

|Download Location|Type|
|-|-|
|[/flow/SharePointEventsNotifier.zip](https://github.com/ShwaTech-LLC/m365-automation/blob/main/flow/SharePointEventsNotifier.zip)|Power Automate Flow|

Import this Power Automate Flow into your environment to monitor your Events list on any SharePoint site for upcoming events and receive an email alert when upcoming events are scheduled within the configurable number of days (defaults to 30).

#### _Deployment Note_

You should unzip the export file from the link above onto your computer somewhere, change the appropriate parameters of the Flow definition to match your tenant, zip the package back up then import it into your Power Automate environment.

# Licensing
The software in this repository is provided free of charge under the [MIT license](https://github.com/ShwaTech-LLC/m365-automation/blob/main/LICENSE.md).