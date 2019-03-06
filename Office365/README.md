For each script you'll need to define a target and variables. The required definitions are below:

Target:
- OneDrive Direct - https://[tenantname]-my.sharepoint.com
- Sharepoint Direct - https://[tenantname].sharepoint.com
- Teams Direct - https://teams.microsoft.com
- Outlook Direct - https://outlook.office.com
- Main Office365 Portal - https://login.microsoftonline.com (used for any of the scripts called "O365 <App Name> - Via App Launcher" as well as basic login scripts)
  
Define Variables:
For all scripts these variables will need to be defined at the top of the workflow: 
- username - user name of login user
- password - password of login user

All Office365 scripts are broken into two categories, if you desire to test via the main portal select the files named "O365 <App Name> - Via App Launcher" and use the Main Office365 Portal target. If you desire to test each app directly (i.e. opening your browser straight to OneDrive or Teams), select the files named "O365 <App Name> - Direct Access" and use the direct target listed above.

There are two basic log in scripts available as well (both via the main portal). The Office365 Log In - Standard Flow file is used when organizations don't have a custom branded log in page. The Office365 Log In - Organizational Landing Page file is used when a user is redirected to a company branded log in page after submitting their email address in the main Microsoft login portal. Note that there are differences in element names for password inputs in each. All steps after the log in will be the same for both flows.
