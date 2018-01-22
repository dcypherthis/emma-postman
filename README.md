# Emma Postman


A Postman Collection repository for all Emma API Endpoints. 

- Official API Docs: http://api.myemma.com/
- Published Postman Collection Docs: https://documenter.getpostman.com/view/278059/emma-api/6fTzk3m#e2b74818-a0ce-7652-d3be-018ee519a3a8 

## How to use?

The Postman Collection file is a JSON containing all information about each request.
This Collection is using Postman Environment Variables, so all you have to do is create an Environment in your local Postman Installation and register the Postman variables, which are:

- account_id
- public_api_key
- private_api_key

To learn more about Postman variables: https://www.getpostman.com/docs/environments

Once you register the required variables for your emma account, you will be able to use the whole Collection.

## Where are my API Credentials?

In order to retrieve or create your private API Credentials, log in to your Emma account and navigate to https://app.e2ma.net/app2/billing/settings/

**Note: Private keys are only displayed when initially generated, so please make sure to record both your public and private keys when you generate them. All subsequent visits to this page will display the private key masked. If you lose your private key, you can regenerate new a public/private key pair by clicking the "Regenerate key" button below. Regenerating or deleting an existing key will immediately disable it, and you will have to replace any instances of that key in your application with the new public/private pair.**

## Basic Auth

The Emma API requires basic auth for all requests. 

## OAuth

Emma does have an Oauth service for integration partners. Please contact integrations@myemma.com for access and additional documentation. 

## Collaboration

Feel free to contribute if you believe there is something missing.

# Authors

Josh Cypher ([@dcypherthis](https://github.com/dcypherthis))
