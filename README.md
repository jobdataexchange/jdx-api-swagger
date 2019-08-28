
# How to interface with JDX

We have our API documented with Swagger and recommend using client generation tools to create your API client and then follow along with our python end-to-end client to learn the sequencing of API interactions.

[What is swagger?](https://swagger.io/docs/specification/2-0/what-is-swagger/)

## Getting the swagger file
The swagger file is located in two places, Here on github and at swaggerhub. They should both have the most up to date versions. Swaggerhub will allow you explore previous versions easily.

https://app.swaggerhub.com/apis/loganripplinger/JDX-reference-backend-application-real

https://github.com/brighthive/jdx-api-swagger

## Getting a client
### Generating your own
1. Get the swagger spec
2. Install and run the openapi-generator tool on the swagger spec https://github.com/OpenAPITools/openapi-generator

### Using a provided client
Here are the two client libraries we have currently,

Python: https://github.com/brighthive/jdx-client-api-python

Typescript: (you will have to generate this one locally) https://github.com/jobdataexchange/reference-app-ui/tree/master/packages/jdx-reference-application-api-client

## Implement the client
Now you have the library to interact with the JDX API. What may be unclear is how to go about interacting with the API and what steps you should take.

For now please refer to our python end-to-end client and reach out to us if you have any questions.

Python end-to-end client: https://github.com/brighthive/jdx-e2e-client-py
