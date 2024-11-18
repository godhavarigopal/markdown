
# My GraphQL API Documentation

## Introduction
This document provides an overview of the GraphQL API endpoints and their usage.

## Endpoints

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
