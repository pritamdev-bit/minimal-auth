# Ninshō - Minimal Auth

Ninshō is a minimal authentication project that provides sign up, sign in, and dashboard functionalities.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [License](#license)

## Features

- Sign up with email, username, and password.
- Sign in with username and password.
- Dashboard with user profile information.

## Installation

1. Clone the repository.

## Usage
- Navigate to http://localhost:3000 in your browser.
- Sign up or sign in with your credentials.
- Access the dashboard to view your profile information.

## API Endpoints

### Sign Up
- Method: POST
- Endpoint: https://api.freeapi.app/api/v1/users/register
- Request Body:

```json
{
  "username": "string",
  "email": "string",
  "password": "string",
  "role": "string"
}
```

### Sign In
- Method: POST
- Endpoint: https://api.freeapi.app/api/v1/users/login
- Request Body:

```json
{
  "username": "string",
  "password": "string"
}
```
## License
Ninshō is licensed under the MIT License.