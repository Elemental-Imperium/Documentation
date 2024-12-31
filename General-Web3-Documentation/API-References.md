# API References

This document provides detailed references for the APIs used across Elemental Imperium's Web3 projects.

## Authentication

### Endpoint: `/auth/login`
- **Method**: POST  
- **Description**: Authenticates a user and returns a JWT token.  
- **Request Body**:  
  ```json
  {
    "username": "string",
    "password": "string"
  }