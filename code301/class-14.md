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

## Things I want to know more about
