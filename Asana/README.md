For each script you'll need to define a target and variables. The required definitions are below:

Target:
- https://app.asana.com
  
Define Variables:
For all scripts these variables will need to be defined at the top of the workflow: 
- username - user name of login user
- password - password of login user

In the case of the Credential-based log in, the username and password variables will be the Asana username and password details. In the case of the Google-based log in, the username and password variables will be the Google Apps username and password details.

In the case of the Google-based log in, it is imperative that as part of an initial setup, the supplied user account has already authenticated at least once to the Asana application so that OAuth permissions have been allowed prior to the first run of the experience script. It is also imperative that MFA/2FA has been disabled for the Google Apps account in order for the AppNeta Monitoring Point to be able to log in appropriately.
