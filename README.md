# photo-spotter-user-service

## Table of Contents
- [Overview](#overview)
- [Planned Features](#planned-features)
- [Environment & Dependencies](#environment--dependencies)
- [API Endpoints](#api-endpoints)
- [Deployment & Usage](#deployment--usage)
- [Tasks](#tasks)

## Overview
Handles all user-related functionality, including account creation, authentication, subscription management, and profile data.

## Planned Features
- [ ] User Registration (JWT or OAuth2)
- [ ] Login/Logout & Session Handling
- [ ] Profile Updates & Subscription Status
- [ ] Password Recovery & Email Confirmations

## Environment & Dependencies
- [.NET 6+ or Go] for core service logic
- [Database] (SQL or NoSQL) for user data storage
- [Docker] for containerization

## API Endpoints
- [ ] `/auth/register` – Create new account
- [ ] `/auth/login` – User login
- [ ] `/users/me` – Fetch/update user profile

## Deployment & Usage
- [ ] Local run with `dotnet run` or `go run main.go` (depending on chosen language)
- [ ] Container build via `docker build -t photo-spotter-user-service .`
- [ ] Kubernetes deploy with minimal `deployment.yaml` and `service.yaml`

## Tasks
- [ ] Set up minimal service scaffold
- [ ] Implement endpoints & authentication
- [ ] Integrate with CI pipeline (build/tests)
- [ ] Provide `/health` endpoint for basic checks
