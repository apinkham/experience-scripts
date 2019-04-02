In the AppNeta Performance Manager, there exist two options for authenticating within Experience scripting. 

![Image of HTTP Auth vs Standard Variables](https://github.com/appneta/experience-scripts/blob/master/Images/HTTP%20Auth%20vs%20Standard%20Variables.png)

### **WHEN TO USE HTTP AUTH**

Use HTTP Auth when your application server challenges for authentication using Basic, Digest, NTLM or Negotiated Authentication methods. An example of the pop-up typically indicative of these types of authentication methods in use is below:
![Image of Example for HTTP Auth](https://github.com/appneta/experience-scripts/blob/master/Images/Example%20for%20HTTP%20Auth.png)


### **WHEN TO USE STANDARD VARIABLES**

Use Standard Variables anytime that you are logging in with application specific credentials rather than a centralized authentication method. 
