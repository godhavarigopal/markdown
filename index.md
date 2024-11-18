# My GraphQL API Documentation

## Introduction
This document provides an overview of the GraphQL API endpoints and their usage.

## Endpoints
[API1 Documentation](./api1.md)
[API2 Documentation](./api2.md)
[API1 Documentation](api1.md)
[API2 Documentation](api2.md)

### Query: GetUser
Fetch user information by user ID.

**Endpoint:** `GetUser`

**Query:**
```graphql
{
  getUser(id: "USER_ID") {
    id
    name
    email
  }
}

