# OAuth

1. What is OAuth?

OAuth is an open standard authorization framework or protocol that describes how servers and unrelated services can securely allow authenticated access to their assets without sharing the raw credentials relevant to a single login. In authentication parlance, this is known as secure authorization, third party, user agent, and delegated authorization.

2. Give an example of what using OAuth would look like.

The simplest example of OAuth is when you go to log in to a website and you provide one or more opportunities to log in using another website/service login. You then click the button associated with the other website, the other website authenticates you, and the website you were originally connecting to will then register you with the permission obtained from the second website.

3. How does OAuth work? What are the steps that it takes to authenticate the user?

Let's say the user is already signed in to one website or service (OAuth only works with HTTPS). The user then initiates a feature/transaction that needs to access another unrelated site or service.Yhis it the steps:
1. The first website connects to the second website on behalf of the user, using OAuth, providing a verified identity to the user.

2. The first website connects to the second website on behalf of the user, using OAuth, providing a verified identity to the user.

3. The first site gives this token and secret to the initiating user client program.

4. The client software submits the request token and secret to the authorization provider (which may or may not be the second signer).

5. If it is not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.

6. The user (or his software silently) consents to a particular type of transaction on the first site.

7. The user is given an authorized access token (note that it is no longer a request token).

8. The user gives the authorized access code to the first site.

9. The first website gives the access token to the second website as proof of authentication on behalf of the user.

10. The second site allows the first site to access its site on behalf of the user.

11. The user sees a successful completed transaction.

12. OAuth is not the first authentication/authorization system to operate in this way on behalf of the end user. In fact, many authentication systems, notably Kerberos, work similarly. What sets OAuth apart is its ability to work across the web and its widespread adoption. It worked with adoption rates where previous attempts had failed (for various reasons).

4. What is OpenID?

OpenID allows you to use an existing account to log into multiple websites, without having to create new passwords.

# Authorization and Authentication flows

1. What is the difference between authorization and authentication?

   * Authentication: Confirms that users are who they say they are. 

   * Authorization: These users give permission to access a resource

2. What is Authorization Code Flow?

      The authorization token flow is used to obtain an access token to authorize API requests. Access tokens can be renewed with a limited lifetime. The refresh token is valid indefinitely and provides the ability for your app to schedule tasks on behalf of the user without their interaction.

3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

   The Flow + PKCE authorization token is an OpenId Connect flow specifically designed for authenticating mobile or native application users. This flow is a best practice when using Single Page Apps (SPAs) or mobile apps. PKCE, pronounced "Pixie" is an acronym for Proof Key to Code Exchange.

4. What is Implicit Flow with Form Post?

   Implicit flow with post flow uses the OIDC form to implement web login which is very similar to how SAML and WS-Federation work. The web application requests and obtains tokens through the front channel, without the need for additional secrets or back calls.

5. What is Client Credentials Flow?

   A client credential flow is a server-to-server flow. There is no user authentication involved in the process.This flow is useful for systems that need to perform API operations when no user is present. They can be night processes, or other processes that involve calling protected OAuth APIs.

6. What is Device Authorization Flow?

Device Authentication Grant OAuth 2.0 (formerly Device Flow) is an OAuth 2.0 extension that enables devices without a browser or limited input capability to obtain an access token. This most commonly appears on Apple TV apps, or devices such as hardware encoders that can stream video to a YouTube channel.

7. What is Resource Owner Password Flow?

The resource owner password credential flow allows the user's username and password to be exchanged for an access token and, optionally, a refresh token. The primary difference is that the user password can be accessed through the application.