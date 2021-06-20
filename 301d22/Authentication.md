# Authentication

## OAuth

**What is OAuth?**  
> Open-standard authorization protocol or framework.

**Give an example of what using OAuth would look like.**  
> using google to log into multiple different websites.

**How does OAuth work? What are the steps that it takes toauthenticate the user?**

   > The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.  
   > The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.  
   > The first site gives this token and secret to the initiating user’s client software.  
   > The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).  
   > If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.  
   > The user approves (or their software silently approves) a particular transaction type at the first website.The user is given an approved access token (notice it’s no longer a request token).  
   > The user gives the approved access token to the first website.  
   > The first website gives the access token to the second website as proof of authentication on behalf of the user.  
   > second website lets the first website access their site on behalf of the user.   
   > The user sees a successfully completed transaction occurring.  

**What is OpenID?**  
> OpenID is a way for humans to log into machines. OpenID is an authenticator and not a authorizor.

## Authorization and Authentication flows


**What is the difference between authorization and authentication?**   
> authentication is the process of verifying who a user is, while authorization is the process of verifying what they have access to.

**What is Authorization Code Flow?**   
 > exchanges an Authorization Code for a token

**What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?**   
> Proof Key for Code Exchange - an additional layer for mobile apps, mainly single page apps.

**What is Implicit Flow with Form Post?**  
> Implicit Flow is an alternative method for fetching the required tokens for access. This method will prevent the need to worry about "securely storing client secrets."

**What is Client Credentials Flow?**  
> (M2M) - machine to machine. This authorizes an app instead of the user.

**What is Device Authorization Flow?**  
> It is where the device asks the user to go to a link on their computer or smartphone and authorize the device.

**What is Resource Owner Password Flow?**  
> sharing information. Recommended only for re-direct flows.