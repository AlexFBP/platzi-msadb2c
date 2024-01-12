# Concept proof of MSAD B2C + MSAL

The goal is to build a multi-language/framework and mini-infrastructure (docker-compose based) composed of:

- A frontend
- A CRUD API
- A MID API

With the following overall stages:

- [x] 1. Create base projects and working infrastructure
- [ ] 2. Integrate project:
     - [ ] front --> mid
     - [ ] front --> crud
     - [ ] mid --> crud
- [ ] 3. Integrate with [MSAL](https://learn.microsoft.com/en-us/entra/identity-platform/sample-v2-code)

## Requirements

- Docker
- `docker compose` (No need to install, included in last versions of Docker)

## Run demo

### Interactive

- Start: `docker compose up`
- To exit: <kbd>Ctrl</kbd> + <kbd>C</kbd>

### Background

- Start: `docker compose up -d`

### Stop & Clean

`docker compose down`

## Additional references:

- [GitHub - Azure AD B2C Community](https://github.com/azure-ad-b2c)
