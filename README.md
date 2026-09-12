AI Agent Token Exchange

This is a student project about token exchange and least privilege for AI agents.

I use Keycloak and Docker to test how an AI agent can exchange a broad access token for a more limited token.

So far I have:

set up Keycloak with Docker
created a test user and clients
created a customer-read role
tested token exchange with curl
verified that the new token is limited to customer-api

Next I will build the customer-api with Spring Boot and test if it accepts the correct token.