# Office 365 SharePoint Development
SharePoint - Office 365

## Sandbox
[BudoApps Sandbox](https://budoappsdev.sharepoint.com/)

## SharePoint Limits
[SharePoint Limits](https://docs.microsoft.com/en-us/office365/servicedescriptions/sharepoint-online-service-description/sharepoint-online-limits?redirectSourcePath=%252fen-us%252farticle%252fSharePoint-Online-software-boundaries-and-limits-8F34FF47-B749-408B-ABC0-B605E1F6D498)

## Introduction to SharePoint information architecture
[Introduction to SharePoint information architecture](https://docs.microsoft.com/en-us/sharepoint/information-architecture-modern-experience)

## Use remote event receivers in SharePoint
[Use remote event receivers in SharePoint](https://docs.microsoft.com/en-us/sharepoint/dev/solution-guidance/use-remote-event-receivers-in-sharepoint)

## Create a hub site in SharePoint
[Create a hub site in SharePoint](https://docs.microsoft.com/en-us/sharepoint/create-hub-site)

## Power Automate
[Power Automate](https://docs.microsoft.com/en-us/learn/modules/introduction-power-automate/)

[Power Automate US Government feature limitations](https://docs.microsoft.com/en-us/power-automate/us-govt#power-automate-us-government-feature-limitations)

## SharePoint site design and site script overview
[SharePoint site design and site script overview](https://docs.microsoft.com/en-US/sharepoint/dev/declarative-customization/site-design-overview?branch=sitedesign)

## SharePoint Look Book
[SharePoint Lookbook](https://lookbook.microsoft.com/)

## SharePoint Designer
[Error "Your account is in bad state.Please sign-in to this account online to address the issue" while opening Sharepoint Online site in SharePoint Designer](https://answers.microsoft.com/en-us/msoffice/forum/all/error-your-account-is-in-bad-stateplease-sign-in/5bf8c178-8789-49b5-b162-8253f3171818)

1. Add the following commands to command line
2. reg add HKEY_CURRENT_USER\SOFTWARE\Microsoft\Office\15.0\Common\Identity /v EnableADAL /t REG_DWORD /d 1
3. reg add HKEY_CURRENT_USER\SOFTWARE\Microsoft\Office\15.0\Common\Identity /v Version /t REG_DWORD /d 1 
4. Verify EnableADAL in Registry at HKEY_CURRENT_USER\SOFTWARE\Microsoft\Office\15.0\Common\Identity


[Removing Deny permission on Add and customize pages](https://www.infowisesolutions.com/documentation/?ID=253)

## Add an App - 2013
[SharePoint Add an App Link](https://budoappsdev.sharepoint.com/sites/cico/_layouts/15/addanapp.aspx)

[[Solved] Connect-SPOService : Current site is not a tenant administration site error in SharePoint Online Office 365 Site](https://www.enjoysharepoint.com/connect-sposervice-current-site-is-not-a-tenant-administration-site/)

[Removing Deny permission on Add and customize pages](https://www.infowisesolutions.com/documentation/?ID=253)

[SharePoint O365 Permissions - Deny - Add And Customise Pages Issue](https://www.qdoscc.com/blog/sharepoint-o365-permissions-deny-add-and-customise-pages-issue)

## Migration Assessment Scan: Master Pages
[Migration Assessment Scan: Master Pages](https://docs.microsoft.com/en-us/sharepointmigration/migration-assessment-scan-master-pages)

## Migrate to Microsoft Office 365 or SharePoint with minimal business disruption.
[AvePoint](https://www.avepoint.com/products/hybrid/office-365-migration/sharepoint-migration?utm_source=google&utm_medium=cpc&utm_content=lp-form&utm_campaign=migrate-na&gclid=Cj0KCQjwxJqHB LinkhC4ARIsAChq4at4t5cvRKLdoLWGA46Hwl79HYeGQmFLhCjf0kpMTuigVjca_LWe_M4aAsNNEALw_wcB)

## Change the look of your SharePoint site
[Change the look of your SharePoint site](https://support.microsoft.com/en-us/office/change-the-look-of-your-sharepoint-site-06bbadc3-6b04-4a60-9d14-894f6a170818)

## Enable Content & Script Editor Webparts in SPO Classic
1. [Enable Scripting in Admin Center](https://docs.microsoft.com/en-us/sharepoint/allow-or-prevent-custom-script)
2. Open SharePoint Online Management Shell
2. Connect-PnPOnline -Url https://tenant-admin.sharepoint.com/sites/siteThatNeedsEnabled -UseWebLogin
3. Set-PnPSite -Url https://tenant-admin.sharepoint.com/sites/siteThatNeedsEnabled -NoScriptSite $false


## Sandbox Solutions In SharePoint Online
[How To Deploy Sandbox Solutions In SharePoint Online](https://www.c-sharpcorner.com/blogs/how-to-deploy-sandbox-solutions-in-sharepoint-online)

[Sync SharePoint files with VS Code](https://wiliammbr.com/sharepoint-sync-files-visual-studio-code/)

## Manage large lists and libraries
[Manage large lists and libraries](https://support.microsoft.com/en-us/office/manage-large-lists-and-libraries-b8588dae-9387-48c2-9248-c24122f07c59)

## Living Large with Large Lists and Large Libraries
[Living Large with Large Lists and Large Libraries](https://docs.microsoft.com/en-us/microsoft-365/community/large-lists-large-libraries-in-sharepoint)

## Content Organizer - Possible Archive Solution
[Content Organizer](https://support.microsoft.com/en-us/office/configure-the-content-organizer-to-route-documents-b0875658-69bc-4f48-addb-e3c5f01f2d9a?ui=en-us&rs=en-us&ad=us)

## 4 types of sites in SharePoint Online
[4 types of sites in SharePoint Online](https://sharepointmaven.com/4-types-of-sites-in-sharepoint-online/)

## Throttling
[Avoid getting throttled or blocked in SharePoint Online](https://docs.microsoft.com/en-us/sharepoint/dev/general-development/how-to-avoid-getting-throttled-or-blocked-in-sharepoint-online)

[SPGo Docs](https://www.chrishasz.com/spgo/)

[Troubleshoot mapped network drives that connect to SharePoint Online](https://docs.microsoft.com/en-us/sharepoint/troubleshoot/administration/troubleshoot-mapped-network-drives)


## Find out what is ERR_TOO_MANY_REDIRECTS and how to fix it
[Find out what is ERR_TOO_MANY_REDIRECTS and how to fix it](https://rockcontent.com/blog/err_too_many_redirects)

[How to Fix The ERR_TOO_MANY_REDIRECTS Error](https://kinsta.com/blog/err_too_many_redirects/)

[httpstatus](https://httpstatus.io/)

[SharePoint 2013 Workflow - Elevated Permission With App Step](https://www.c-sharpcorner.com/article/sharepoint-2013-workflow-elevated-permission-with-app-step/)

## Microsoft Graph
[Overview of Microsoft Graph](https://docs.microsoft.com/en-us/graph/overview)

## [Easier browser debugging with Developer Tools integration in Visual Studio Code](https://blogs.windows.com/msedgedev/2021/07/16/easier-debugging-developer-tools-in-visual-studio-code/)

## Office UI Fabric Icons
[Office UI Fabric Icons](https://uifabricicons.azurewebsites.net/)

## Sync SharePoint files with the OneDrive sync client (Groove.exe)
[Sync SharePoint files with the OneDrive sync client (Groove.exe)](https://support.microsoft.com/en-us/office/sync-sharepoint-files-with-the-onedrive-sync-client-groove-exe-59b1de2b-519e-4d3a-8f45-51647cf291cd)

## What do the OneDrive icons mean?
[What do the OneDrive icons mean?](https://support.microsoft.com/en-us/office/what-do-the-onedrive-icons-mean-11143026-8000-44f8-aaa9-67c985aa49b3)

## Excel functions (alphabetical)
[Excel functions (alphabetical)](https://support.microsoft.com/en-us/office/excel-functions-alphabetical-b3944572-255d-4efb-bb96-c6d90033e188#bm4)

## Publish a InfoPath form
[Publish a InfoPath form](https://support.microsoft.com/en-us/office/publish-a-form-bd6eb030-b26b-4774-b22b-7c80e0089403)

## Copy & Paste Actions In Microsoft Flow
[Copy & Paste Actions In Microsoft Flow](https://www.youtube.com/watch?v=8G9kO6QLCAc)

## Update File on SharePoint using Power Automate
[Update File on SharePoint using Power Automate](https://www.youtube.com/watch?v=3Yhx7dAGFAw)

## How to increase lookup column limit in SharePoint lists
[How to increase lookup column limit in SharePoint lists](https://natechamberlain.com/2018/09/04/how-to-increase-lookup-column-limit-in-sharepoint-lists/)

## FIND ID OF SHAREPOINT DOCUMENT BY FILE NAME IN POWER AUTOMATE
[FIND ID OF SHAREPOINT DOCUMENT BY FILE NAME IN POWER AUTOMATE](https://linnzawwin.blogspot.com/2020/11/find-id-of-sharepoint-document-by-file.html)

## QUICK TIP: FLOW CANNOT BE USED AS A CHILD FLOW
[QUICK TIP: FLOW CANNOT BE USED AS A CHILD FLOW](https://poszytek.eu/en/microsoft-en/office-365-en/powerautomate-en/quick-tip-flow-cannot-be-used-as-a-child-flow/)

## Set custom permissions on a list by using the REST interface
[Set custom permissions on a list by using the REST interface](https://docs.microsoft.com/en-us/sharepoint/dev/sp-add-ins/set-custom-permissions-on-a-list-by-using-the-rest-interface)

## Configure InfoPath At The SharePoint Admin Center On Office 365
[Configure InfoPath At The SharePoint Admin Center On Office 365](https://www.c-sharpcorner.com/article/configure-infopath-at-the-sharepoint-admin-center-on-office/)

## InfoPath developing views (Chapter 8)
[InfoPath developing views (Chapter 8)](https://www.youtube.com/watch?v=SWxbxd7dGO0)

## Tech Tip: Switch InfoPath Views On Form Open For A Better User Experience
[Tech Tip: Switch InfoPath Views On Form Open For A Better User Experienc](https://www.formotus.com/blog/switch-infopath-views-on-form-open-for-a-better-user-experience)

## How To Create A Form Using InfoPath 2013 for Sharepoint
[How To Create A Form Using InfoPath 2013 for Sharepoint](https://www.youtube.com/watch?v=HSyrqbgLdbs)

## Using repeating tables from the Course InfoPath 2013 Essential Training
[Using repeating tables from the Course InfoPath 2013 Essential Training](https://www.youtube.com/watch?v=yQfWVYMf9ro)

## how to update content type for a sharepoint list item using REST api in O365?
[how to update content type for a sharepoint list item using REST api in O365?](https://sharepoint.stackexchange.com/questions/200280/how-to-update-content-type-for-a-sharepoint-list-item-using-rest-api-in-o365)

## Display modal pop up in SharePoint Online/2013/2016
[Display modal pop up in SharePoint Online/2013/2016](https://www.enjoysharepoint.com/display-modal-pop-up-in-sharepoint/)

## PowerApps: How to Customize "Save" and "Cancel" Buttons
[PowerApps: How to Customize "Save" and "Cancel" Buttons](https://www.c5insight.com/Resources/Blog/tabid/148/entryid/885/powerapps-how-to-customize-save-and-cancel-buttons.aspx)

## How To Fetch Access Token Using Microsoft Graph AP
[How To Fetch Access Token Using Microsoft Graph AP](https://www.c-sharpcorner.com/article/getting-started-with-microsoft-graph-api/)

## Retrieve Files and Items from Sharepoint Using Microsoft Graph API
[Retrieve Files and Items from Sharepoint Using Microsoft Graph API](https://www.c-sharpcorner.com/article/retrieve-files-items-from-sharepoint-using-microsoft-graph-api/)

## Customizing "modern" lists and libraries
[Customizing "modern" lists and libraries](https://docs.microsoft.com/en-us/sharepoint/dev/solution-guidance/modern-experience-customizations-customize-lists-and-libraries)

## Use Power Automate to move Microsoft Lists items to another list
[Use Power Automate to move Microsoft Lists items to another list](https://normyoung.ca/2020/10/01/use-power-automate-to-move-microsoft-lists-items-to-another-list/)

## SharePoint modern view formatting with JSON – part 1 of 2
[SharePoint modern view formatting with JSON – part 1 of 2](https://collab365.com/sharepoint-modern-view-formatting-json-part-1-2/)

## Enable new list experience on document library programmatically
[Enable new list experience on document library programmatically](https://sharepoint.stackexchange.com/questions/188014/enable-new-list-experience-on-document-library-programmatically)

## SharePoint Limits
[SharePoint Limits](https://docs.microsoft.com/en-us/office365/servicedescriptions/sharepoint-online-service-description/sharepoint-online-limits?redirectSourcePath=%252fen-us%252farticle%252fSharePoint-Online-software-boundaries-and-limits-8F34FF47-B749-408B-ABC0-B605E1F6D498)

## DownDetector
[DownDetector](https://downdetector.com/status/wikipedia/)

## Office 365 Status
[Office 365 Status](https://status.office365.com/)

## Page Diagnostics
[Use the Page Diagnostics for SharePoint tool](https://docs.microsoft.com/en-us/microsoft-365/enterprise/page-diagnostics-for-spo?view=o365-worldwide)

## Resources
[SharePoint Important URLs](https://mstechtalk.com/sharepoint-important-urls/)

[Useful Famous SharePoint URLs & Locations (increase your productivity in SharePoint On-Premise and O365)](https://global-sharepoint.com/sharepoint-online/sharepoint-quick-reference-url/)

[Office365-SharePoint-Development](https://www.c-sharpcorner.com/article/how-to-deploy-power-app-list-form-from-one-tenant-to-another-tenant/)

[Creating an Aging Report Using a User-Selected Date in Power BI](https://www.credera.com/insights/creating-aging-report-using-a-user-selected-date-in-power-bi)

[Assign Licenses](https://docs.microsoft.com/en-us/power-platform/admin/assign-licenses#:~:text=You%20can%20add%20additional%20licenses,for%20each%20invitation%20you%20issue.)

[Announcing multi-stage retention in Microsoft Purview Data Lifecycle Management](https://techcommunity.microsoft.com/t5/security-compliance-and-identity/announcing-multi-stage-retention-in-microsoft-purview-data/ba-p/3282126)

[Azure Functions support for PowerShell 6 is ending on 30 September 2022](https://azure.microsoft.com/en-us/updates/azure-functions-support-for-powershell-6-is-ending-on-30-september-2022/)

## Create a canvas app with deep link to a specific screen
https://docs.microsoft.com/en-us/power-apps/maker/canvas-apps/how-to/deep-linking?cid=kerryherger#:~:text=Deep%20links%20are%20useful%20when,AppID%E2%80%94ID%20of%20the%20app.

## CoreIdentity
[CoreIdentity](https://coreidentity.microsoft.com/)

## How to Embed Your Instagram Feed On Your Website
[How to Embed Your Instagram Feed On Your Website](https://curator.io/blog/how-to-embed-your-instagram-feed-on-your-website)

## The Best Social Media Aggregators for 2022
[The Best Social Media Aggregators for 2022](https://curator.io/blog/the-best-social-media-aggregators)

## Create event
https://docs.microsoft.com/en-us/graph/api/calendar-post-events?view=graph-rest-1.0&tabs=http

<<<<<<< HEAD
## Announcing Microsoft Power Pages: Build secure, low-code websites
[Announcing Microsoft Power Pages: Build secure, low-code websites](https://powerpages.microsoft.com/en-us/blog/announcing-microsoft-power-pages-build-secure-low-code-websites/)

## SharePoint Online: How to Change Home Page using PowerShell?
[SharePoint Online: How to Change Home Page using PowerShell?](https://www.sharepointdiary.com/2017/02/sharepoint-online-change-home-page-using-powershell.html)
=======
## How to use "Office UI Fabric Icons" in PowerApps
[How to use "Office UI Fabric Icons" in PowerApps](https://www.youtube.com/watch?v=HygPiEgHJkQ)

## How to grant all employees access to a SharePoint site via Everyone except external users Group
[How to grant all employees access to a SharePoint site via Everyone except external users Group](https://sharepointmaven.com/grant-employees-access-sharepoint-site-via-everyone-except-external-users-group/)

## Learn about retention policies and retention labels
[Learn about retention policies and retention labels](https://docs.microsoft.com/en-us/microsoft-365/compliance/retention?view=o365-worldwide)

## KQL Cheat Sheet
[KQL Cheat Sheet](https://www.cqure.nl/en/knowledge-platform/kql-cheat-sheet)

## Create a map view for the Geolocation field in SharePoint
[Create a map view for the Geolocation field in SharePoint](https://learn.microsoft.com/en-us/sharepoint/dev/general-development/create-a-map-view-for-the-geolocation-field-in-sharepoint)

## Tips and tricks for Power BI map visualizations
[Tips and tricks for Power BI map visualizations](https://learn.microsoft.com/en-us/power-bi/visuals/power-bi-map-tips-and-tricks)

## Allow or restrict the ability to embed content on SharePoint pages
[Allow or restrict the ability to embed content on SharePoint pages](https://support.microsoft.com/en-us/office/allow-or-restrict-the-ability-to-embed-content-on-sharepoint-pages-e7baf83f-09d0-4bd1-9058-4aa483ee137b)

## Installing the Ultimate Forms Trial Version for O365
[Installing the Ultimate Forms Trial Version for O365](https://www.youtube.com/watch?v=FB_vqZP4E34)

## Infowise Connected Field
[Infowise Connected Field](https://www.youtube.com/watch?v=wDqh2Ais_04)

## Integration with Connected Field
[Integration with Connected Field](https://www.infowisesolutions.com/documentation/index/111)

## Removing Deny permission on Add and customize pages
[Removing Deny permission on Add and customize pages](https://www.infowisesolutions.com/documentation/?ID=253)

## Setting up multiple cascading lookup levels
[Setting up multiple cascading lookup levels](https://www.infowisesolutions.com/blog/setting-up-multiple-cascading-lookup-levels)

## Working with the Page Comments REST API in SharePoint Communication sites
[Working with the Page Comments REST API in SharePoint Communication sites](https://www.vrdmn.com/2017/07/working-with-page-comments-rest-api-in.html)

## Viva
[Microsoft Viva](https://www.microsoft.com/en-us/microsoft-viva#layout-container-uidc84f)

[Microsoft Viva](https://learn.microsoft.com/en-us/viva/)

[Microsoft Viva Dev Center](https://developer.microsoft.com/en-us/viva)

[Set Up Microsoft Viva](https://learn.microsoft.com/en-us/viva/setup-microsoft-viva)

[Overview of Viva Connections](https://learn.microsoft.com/en-us/viva/connections/viva-connections-overview)

[Authoring a Microsoft Viva Connections Dashboard](https://www.youtube.com/watch?v=-p09L3RRNQ8)

[A whole new way to deliver UI](https://adaptivecards.io/)

[Build your first SharePoint Adaptive Card Extension](https://learn.microsoft.com/en-us/sharepoint/dev/spfx/viva/get-started/build-first-sharepoint-adaptive-card-extension)

[Community Samples](https://github.com/pnp/sp-dev-fx-aces)

[Viva Dashboard | What is it. How to use it. How to make it your own.](https://www.youtube.com/watch?v=kRN7P8YudBE)

[Viva Engage](https://www.microsoft.com/en-us/microsoft-viva/engage)

[Excel to JSON Converter](https://beautifytools.com/excel-to-json-converter.php)

## Script Editor Webpart
[SharePoint online spfx script editor web part](https://www.enjoysharepoint.com/spfx-script-editor-web-part/)

## InfoPath
[InfoPath to SharePoint Fields](https://www.office-forums.com/threads/how-to-show-infopath-form-fields-on-a-sharepoint-library.100260)

## List Item Entity FullName
[List Item Entity FullName](https://sharepointeducation.wordpress.com/2020/02/16/list-item-entity-fullname/)

##  CamlJs: SharePoint JavaScript Caml Builder
[CamlJs: SharePoint JavaScript Caml Builder](https://ecmascript21.rssing.com/chan-9313638/all_p5.html)

## How to use fetch() with CORS and credentials
[How to use fetch() with CORS and credentials](https://byby.dev/js-fetch-cors-credentials)

## Scheduler - FullCalendar
[Full Calendar](https://fullcalendar.io/docs/premium)

## FullCalendar Scheduler Installation
[Docs Premium Plugins](https://fullcalendar.io/docs/premium)

## Full Calendar Scheduler Demo
[Full Calendar](https://fullcalendar.io/docs/timeline-standard-view-demo)

## CORS
[Fix for __REQUESTDIGEST value undefined issue- SharePoint Hosted App / Regular Page without Master Page](https://blog.josephvelliah.com/fix-for-requestdigest-value-undefined-issue-sharepoint-hosted-app-regular-page-without-master-page)

## Parse CSV File Using Power Automate
[Parse CSV File Using Power Automate](https://www.c-sharpcorner.com/article/parse-csv-file-using-power-automate/)

## Reference guide to workflow expression functions in Azure Logic Apps and Power Automate
[Reference guide to workflow expression functions in Azure Logic Apps and Power Automate](https://learn.microsoft.com/en-us/azure/logic-apps/workflow-definition-language-functions-reference)

## Tutorial: Embed a Power Apps visual in a Power BI report
[Tutorial: Embed a Power Apps visual in a Power BI report](https://learn.microsoft.com/en-us/power-bi/visuals/power-bi-visualization-powerapp)

## Analyze and visualize your Outlook/Exchange calendar in Power BI
[Analyze and visualize your Outlook/Exchange calendar in Power BI](https://www.youtube.com/watch?v=zXJphXou0TE)

## How To Create Outlook Calendar Events from A Power App via a Power Automate Flow
[How To Create Outlook Calendar Events from A Power App via a Power Automate Flow](https://www.youtube.com/watch?v=WQlvKxWuU7g)

## Microsoft 365 Outlook Actions: Get Calendars V2
[Microsoft 365 Outlook Actions: Get Calendars V2](https://www.youtube.com/watch?v=wYGKlgU5cvY)

## How to get data from other people's outlook calendar
[How to get data from other people's outlook calendar](https://powerusers.microsoft.com/t5/Building-Power-Apps/How-to-get-data-from-other-people-s-outlook-calendar/td-p/1482710)

## Power Apps Canvas- Office365Outlook.CalendarGetTablesV2() did not show the ESTEMS calendar
[Power Apps Canvas- Office365Outlook.CalendarGetTablesV2() did not show the ESTEMS calendar](https://powerusers.microsoft.com/t5/Building-Power-Apps/Power-Apps-Canvas-Office365Outlook-CalendarGetTablesV2-did-not/m-p/1366286#M355584)

## PowerApps Horizontal Navigation Menu Component With Submenu
[PowerApps Horizontal Navigation Menu Component With Submenu](https://www.c-sharpcorner.com/article/powerapps-horizontal-navigation-menu-component-with-submenu/)

## Upload Files and Metadata to SharePoint in PowerApps
[Upload Files and Metadata to SharePoint in PowerApps](https://www.c-sharpcorner.com/article/upload-files-and-metadata-to-sharepoint-in-powerapps/)

## Create a Calendar in PowerApps
[Create a Calendar in PowerApps](https://www.c-sharpcorner.com/article/create-a-calendar-in-powerapps2/)

## Formula reference - Power Apps
[Formula reference - Power Apps](https://learn.microsoft.com/en-us/power-platform/power-fx/formula-reference)

## Using PowerApps Filter Function for All SharePoint List Columns
[Using PowerApps Filter Function for All SharePoint List Columns](https://www.c-sharpcorner.com/article/using-powerapps-filter-function-for-all-sharepoint-list-columns/)

## Calendar-screen template in canvas apps
[Calendar-screen template in canvas apps](https://learn.microsoft.com/en-us/power-apps/maker/canvas-apps/screen-templates/calendar-screen-overview)

## Display SharePoint List Attachments in Power Apps | Viewer Component
[Display SharePoint List Attachments in Power Apps | Viewer Component](https://www.youtube.com/watch?v=3dNeMVLZDHo)

## Display SharePoint List Attachments in Power Apps | Viewer Component
[Display SharePoint List Attachments in Power Apps | Viewer Component](https://www.youtube.com/watch?v=3dNeMVLZDHo)

## Make A Calendar In Power Apps – Part 1
[Make A Calendar In Power Apps – Part 1](https://www.matthewdevaney.com/make-a-calendar-in-power-apps-part-1/)

## Make A Calendar In Power Apps – Part 2
[Make A Calendar In Power Apps – Part 2](https://www.matthewdevaney.com/make-a-calendar-in-power-apps-part-2/)

## Custom API in Microsoft Dataverse or Dynamics 365 Configuration and Demo | Postman call Custom API
[Custom API in Microsoft Dataverse or Dynamics 365 Configuration and Demo | Postman call Custom API](https://youtu.be/kEte_uYjFFE?si=-P5y72SIGO9FEBC4)

## All Power Apps Date & Time Functions (With Examples)
[All Power Apps Date & Time Functions (With Examples)](https://www.matthewdevaney.com/all-power-apps-date-time-functions-with-examples/)

## Power Apps Navigating Folders & Subfolders In A SharePoint Document Library
[Power Apps Navigating Folders & Subfolders In A SharePoint Document Library](https://www.matthewdevaney.com/power-apps-navigating-folders-subfolders-in-a-sharepoint-document-library/)

## Variables In PowerApps
[Variables In PowerApps](https://www.c-sharpcorner.com/article/variables-in-powerapps/)

## Power Apps: Customize A SharePoint List Form
[Power Apps: Customize A SharePoint List Form](https://www.matthewdevaney.com/power-apps-customize-a-sharepoint-list-form/)

## Combining Filter and Sort in Gallery
[Combining Filter and Sort in Gallery](https://www.matthewdevaney.com/power-apps-customize-a-sharepoint-list-form/](https://powerusers.microsoft.com/t5/Building-Power-Apps/Combining-Filter-and-Sort-in-Gallery/td-p/125923)https://powerusers.microsoft.com/t5/Building-Power-Apps/Combining-Filter-and-Sort-in-Gallery/td-p/125923)

## Power Apps People Picker Delegation Workaround
[Power Apps People Picker Delegation Workaround](https://www.matthewdevaney.com/power-apps-people-picker-delegation-workaround/)

## Power Apps Drag & Drop Kanban Tutorial
[Power Apps Drag & Drop Kanban Tutorial](https://www.matthewdevaney.com/power-apps-drag-drop-kanban-tutorial/)

## 5 Power Apps Gallery Design UX Tips
[5 Power Apps Gallery Design UX Tips](https://www.matthewdevaney.com/5-power-apps-gallery-design-ux-tips/)

## Power Apps Easiest Way To Upload Files To A SharePoint Document Library
[Power Apps Easiest Way To Upload Files To A SharePoint Document Library](https://www.matthewdevaney.com/power-apps-easiest-way-to-upload-files-to-a-sharepoint-document-library/)

## Power Apps- How Components access Global Variables, Controls and Screens
[Power Apps- How Components access Global Variables, Controls and Screens](https://automations365.com/power-apps-how-components-access-global-variables-controls-and-screens/)

## Power Apps Design: Make Your Power Apps Look Better With This 1 Tip
[Power Apps Design: Make Your Power Apps Look Better With This 1 Tip](https://www.youtube.com/watch?v=vh9X2cwmzAQ)

## Power Apps Navigating Folders & Subfolders In A SharePoint Document Library
[Power Apps Navigating Folders & Subfolders In A SharePoint Document Library](https://www.matthewdevaney.com/power-apps-navigating-folders-subfolders-in-a-sharepoint-document-library/)

## Power Apps Patch Function Examples For Every SharePoint Column Type - Update SharePoint Fields from PowerApps
[Power Apps Patch Function Examples For Every SharePoint Column Type](https://www.matthewdevaney.com/power-apps-patch-function-examples-for-every-sharepoint-column-type)

## How To Trigger A Power Automate Flow From PowerApps
[How To Trigger A Power Automate Flow From PowerApps](https://www.c-sharpcorner.com/article/how-to-trigger-a-power-automate-flow-from-powerapps/)

## Office 365 Outlook - Connector
[Office 365 Outlook](https://learn.microsoft.com/en-us/connectors/office365/#get-calendar-view-of-events-(v3))

## Dynamically add a new control (text input for example) after clicking a button
[Dynamically add a new control (text input for example) after clicking a button](https://powerusers.microsoft.com/t5/Building-Power-Apps/Dynamically-add-a-new-control-text-input-for-example-after/td-p/147483)

## JSON In PowerApps
[JSON In PowerApps](https://pankajsurti.com/2023/10/23/how-to-create-a-json-string-array-in-powerapps-2/)

## Help with formula using ForAll First and Split
[Help with formula using ForAll First and Split](https://powerusers.microsoft.com/t5/Building-Power-Apps/Help-with-formula-using-ForAll-First-and-Split/td-p/2064682)

## Group The Items In A Power Apps Gallery
[Group The Items In A Power Apps Gallery](https://www.matthewdevaney.com/group-the-items-in-a-power-apps-gallery/)

## Document Preview in Power Apps
[Document Preview in Power Apps](https://www.matthewdevaney.com/the-secret-way-to-view-word-excel-powerpoint-files-in-power-apps/)

## Text function
[Text function](https://learn.microsoft.com/en-us/power-platform/power-fx/reference/function-text)

## The Complete Power Apps Functions List
[The Complete Power Apps Functions List]([The Complete Power Apps Functions List](https://www.matthewdevaney.com/the-complete-power-apps-functions-list/))

## List of SharePoint Field Names
[https://blog.softartisans.com/2009/12/08/list-of-internal-names-for-sharepoint-fields/](https://blog.softartisans.com/2009/12/08/list-of-internal-names-for-sharepoint-fields/)

## Microsoft Graph API
[Microsoft Graph API](https://learn.microsoft.com/en-us/graph/api/driveitem-put-content?view=graph-rest-1.0&tabs=http)

## Power Automate - Break Inheritance And Set List Item-Level Permissions In SharePoint Online
[Power Automate - Break Inheritance And Set List Item-Level Permissions In SharePoint Online](https://www.c-sharpcorner.com/article/power-automate-break-inheritance-and-set-list-item-level-permissions-in-sharep/)

## Power Apps Business Days
[Power Apps Business Days](https://powerapps.microsoft.com/de-at/blog/excluding-weekends-and-holidays-in-date-differences-in-powerapps/)

## Power Apps Loading Spinners, Saving Spinners and Progress Bars
[Power Apps Loading Spinners, Saving Spinners and Progress Bars](https://www.matthewdevaney.com/power-apps-loading-spinners-saving-spinners-and-progress-bars/)

## EndPoint
/_api/lists/getbytitle('DocArchive')/items?$filter=productTypes%20eq%20%275x8%27

## KQL SharePoint Query EndPoint
[KQL SharePoint Query EndPoint](https://dod365.sharepoint-mil.us/teams/USSOUTHCOM-CAG-RFI/_api/search/query?querytext=%27Path:https://dod365.sharepoint-mil.us/teams/USSOUTHCOM-CAG-RFI/Lists/CMDR_Calendar_SharePoint%27&refinementfilters=%27(Title:Transition)%27)

## Keyword Query Language (KQL) syntax reference
[Keyword Query Language (KQL) syntax reference](https://learn.microsoft.com/en-us/sharepoint/dev/general-development/keyword-query-language-kql-syntax-reference)

## HTML Text Control
[HTML Text Control](https://svaghub.com/2019/09/25/powerapps-modern-minimalistic-design-tip-1-box-shadows/)

## Source code files for Canvas apps
[Source code files for Canvas apps](https://www.microsoft.com/en-us/power-platform/blog/power-apps/source-code-files-for-canvas-apps/)

## Power Apps Source Code Tool
[Power Apps Source Code Tool](https://www.matthewdevaney.com/power-apps-source-code-tool/)

## Power Apps Calculate Business Days Excluding Weekends & Holidays
[Power Apps Calculate Business Days Excluding Weekends & Holidays](https://www.matthewdevaney.com/power-apps-calculate-business-days-excluding-weekends-holidays/)

## External Users Accessing Power App
[External Users Accessing Power App](https://community.powerplatform.com/forums/thread/details/?threadid=dff2dc65-1b47-4af6-a252-cd18f3a24102)

## About Power Apps per app plans
[About Power Apps per app plans](https://learn.microsoft.com/en-us/power-platform/admin/about-powerapps-perapp)

## Web API Using Power Apps Custom Connector
[Web API Using Power Apps Custom Connector](https://www.c-sharpcorner.com/article/web-api-using-power-apps-custom-connector/)

## OpenAI API
[OpenAI API](https://platform.openai.com/docs/api-reference/introduction)

## Co-Pilot
[Microsoft Co-Pilot](https://copilot.microsoft.com/)

## event resource type
[event resource type](https://learn.microsoft.com/en-us/graph/api/resources/event?view=graph-rest-1.0)
