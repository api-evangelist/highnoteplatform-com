---
name: highnoteplatform-com-graphql-execute
description: Execute a GraphQL request against the Highnote Platform API.
api: openapi/_ae-authored/highnoteplatform-com-openapi-generated.yml
operations:
- get_graphql
- post_graphql
generated: '2026-10-22'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/_ae-authored/highnoteplatform-com-openapi-generated.yml ; every operationId checked against the contract
---

# highnoteplatform-com-graphql-execute

Execute a GraphQL request against the Highnote Platform API.

## Steps

1. 1. Use `get_graphql` to send a GET request to `/graphql` with the required `Authorization` header (Basic auth).
2. 2. Use `post_graphql` to send a POST request to `/graphql` with the required `Authorization` header (Basic auth) and the GraphQL payload in the request body.

## Rules

- Authentication: Include an `Authorization` header with Basic credentials for every request.
- Rate limiting: The API allows 200 requests per 10 seconds; exceeding this returns HTTP 429.
