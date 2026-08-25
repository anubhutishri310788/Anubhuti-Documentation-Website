---
layout: default
title: Sample API Reference
---

# Sample API Reference

## Introduction
This is a sample API reference for documentation purposes.

## Authentication
All requests require Bearer token:

Authorization: Bearer YOUR_TOKEN


## Endpoints

### GET /users
Retrieve all users.

**Response:**
```json
{
  "users": [
    {
      "id": "1",
      "name": "John Doe",
      "email": "john@example.com"
    }
  ]
}
```

### POST /users
Create a new user.

**Request:**
```json
{
  "name": "Jane Doe",
  "email": "jane@example.com"
}
```

## Error Handling

### 401 Unauthorized
Missing or invalid authentication token.

### 404 Not Found
Resource does not exist.