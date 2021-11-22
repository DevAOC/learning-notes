[Home Page](https://devaoc.github.io/reading-notes/)

# Class 27 Notes

## Review, Research, and Discussion

1. The similarities between AWS Gateway + Lambda functions and an Express.js server is that they both use REST and have similar routing.
2. They have multiple database offerings some are NoSQL and some are SQL.
3. A FIFO queue will make sure that the data is sent in one after the other and has to be handled one before the other. A standard queue doesnt require the first queue object to be read first.
4. You can use SQS to make sure that the message was delivered and you can also use promises.

## Terms

- Serverless API: They are not truly serverless because they have code behind the scenes but they dont require manual maintenance and are offered by service providers.
- Triggers: Triggers are actions that activate another section of code. For instance Lambda functions require triggers to start.
- Dynamo vs Mongo: Dynamo is a NoSQL just like Mongo but Dynamo is offered by AWS.
- Dynamoose vs Mongoose: Dynamoose is the package that allows you to use DynamoDB and Mongoose is the package that allows you to use MongoDB.
