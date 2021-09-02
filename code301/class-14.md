[Home Page](https://devaoc.github.io/reading-notes/)

# Class 14 Notes

## What is OAuth

OAuth is an authentication protocol that allows the user to sent client information to be authenticated without using the original logon credentials.

A good example of an OAuth use is when trying to log on to a Google or Facebook account when on a third-party website.

OAuth works by:

- Connecting the user to a third-party site
- The third-party generates a one-time token and a secret that is unique and available only to the parties involved
- The site sends the token and secrect to the client software
- The client software sends the token and secret to the authentication provider (If not already auhtenticated the client may be asked to authenticate)
- After authentication the client is asked to approve the authentication transaction to the third-party site
- The user approves the authentication
- The user is given an approved access token
- User gives the token to the first site
- The first site gives the approved token to the third-party as proof of authentication
- The first site is given access to the third-party
- The third-party gives the user access to their site

OpenID is a way to use one sign in for all sites.

## Authorization and Authentication flows

The difference between authorization and authentication is that authorization gives the user access by requesting a third source to verify the user's identity and authentication is a way for users to log in without the third-party source.

Authorization Code Flow is the steps in which authorization progresses.

Authorization Code Flow with Proof Key for Code Exchange (PKCE) is a way of authorizing access using code verifiers and challenges.

Implicit Flow with Form Post is the use of POST instead of URL fragments for connection.

Client Credentials Flow is authorization using user ID and a unique secret token.

Device Authorization Flow is authorization using a device that recieves an authorization code. An authorized device makes a request for logging that the browser marks as authorized and returns an access token.

Resource Owner Password Flow is when users log in with their log in information, and that info is then stored in the backend.

## Things I want to know more about
