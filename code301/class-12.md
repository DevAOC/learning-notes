[Home Page](https://devaoc.github.io/reading-notes/)

# Class 12 Notes

## Status Codes Based On REST Methods

Status Codes:

100-199 are informational codes that tell the client about the request that has been recieved.

200-299 are success codes.

300-399 are a collection of redirection codes.

400-499 are client error codes.

500-599 are server error codes.

Status code 202 means that the request they made was valid and that the client should recieve a URL response.

Status code 308 means that the request was sent to a new URL and in other words redirected.

The code that would be returned when no content is returned to the client is status code 204.

The forbidden staus code is the no permissions code 403.

## Build A REST API With Node.js, Express, & MongoDB - Quick

You need to put the server string in your .env so that you can run the mongoose connection.

Middleware is software that is usually an aid between your client and server. For instance a third party API is considered middleware.

app.use(express.json()) recognizes that the incoming information is in JSON form.

/:id means that whatever is put there is a parameter.

Patch only updates the specific information linked to the parameter passed while PUT will put a new instance in the DB.

The 500 status code means that there was an error within the server.

Code 200 means that the request was successful and returned a response; 201 means that a resource was created.

## Things I want to know more about
