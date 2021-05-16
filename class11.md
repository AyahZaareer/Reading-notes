## What is OAuth?
### OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential.

## The example of what using OAuth would look like:
### Netlify - Heroku

## How does OAuth work? What are the steps that it takes to authenticate the user?
###

## What is OpenID?
### OpenID Connect is an interoperable authentication protocol based on the OAuth 2.0 family of specifications. ... OpenID Connect allows for clients of all types, including browser-based JavaScript and native mobile apps, to launch sign-in flows and receive verifiable assertions about the identity of signed-in users.


## Authorization and Authentication flows:
### What Is Authentication?
### Authentication is the act of validating that users are whom they claim to be. This is the first step in any security process. Giving someone permission to download a particular file on a server or providing individual users with administrative access to an application are good examples of authentication.

## What Is Authorization?
### Authorization in a system security is the process of giving the user permission to access a specific resource or function. This term is often used interchangeably with access control or client privilege.                                                                                                                                                      In secure environments, authorization must always follow authentication. Users should first prove that their identities are genuine before an organization’s administrators grant them access to the requested resources.

## What is Authorization Code Flow?
### Because regular web apps are server-side apps where the source code is not publicly exposed, they can use the Authorization Code Flow (defined in OAuth 2.0 RFC 6749, section 4.1), which exchanges an Authorization Code for a token. Your app must be server-side because during this exchange, you must also pass along your application's Client Secret, which must always be kept secure, and you will have to store it in your client.

## What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
### During authentication, mobile and native applications can use the Authorization Code Flow, but they require additional security. Additionally, single-page apps have special challenges. To mitigate these, OAuth 2.0 provides a version of the Authorization Code Flow which makes use of a Proof Key for Code Exchange (PKCE).
