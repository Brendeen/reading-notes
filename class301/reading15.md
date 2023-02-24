# Class 15

[Back to home page](../README.md)

## What is OAuth?

Q. What is OAuth?

- OAuth is a framework that allows access to services without sharing the credential.

Q. Give an example of what using OAuth would look like.

- One example is how you can sign into netlify through your github, or offering multiple ways to login to a service.

Q. How does OAuth work? What are the steps that it takes to authenticate the user?

- OAuth works by pretty much using one website to access another, or by one website requesting a one time request token to the other site. Apon approval, they website will send this back to the first one saying its approved, and the user gets access to the website/service.

Q. What is OpenID?

- The most simple way to describe the difference between the two is openID is used when a human logs onto a machine, and OAuth is used when a machine is accessing another machine via human control.

## Authorization and Authentication flows

Q. What is the difference between authorization and authentication?

- Authorization determines a user access rights, while authorizzation determines the users identity.

Q. What is Authorization Code Flow?

- Pretty much the flow that enables a user to access protected resources such as apis.

Q. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

- PKCE is a different flow from authorization code flow, only difference being that the user is not required to provide any sort of client_secret. Client_secret is something only the app and server will know, almost like a password.

Q. What is Implicit Flow with Form Post?

- In todays world not best practice, is a flow that is best used for public clients that cannot securely store their client secrets.

Q. What is Client Credentials Flow?

- This is a different flow that is authorized and authenticated by the app instead of the user.

Q. What is Device Authorization Flow?

- This flow asks the user to connect/access a link to authorize their device, such as setting up a gaming console through their app on a phone.

Q. What is Resource Owner Password Flow?

- A very simple flow, used primarily in a form method with a username and password system.

## Bookmark

- [Auth0 for single page apps](https://auth0.com/docs/libraries/auth0-react)

## Things I want to know more about

How deep does the idea of OAuth go? how many machines can a person access through another machine?
