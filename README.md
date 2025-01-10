# photo-spotter-user-service

## Table of Contents
- [Overview](#overview)
- [Planned Features](#planned-features)
- [Environment and Dependencies](#environment-and-dependencies)
- [API Endpoints](#api-endpoints)
- [Deployment and Usage](#deployment-and-usage)
- [Tasks](#tasks)

## Overview
This service manages user-related functionality such as account creation, authentication, subscription management, and user profiles.

## Planned Features
- User registration and authentication (JWT or OAuth2)
- Login/Logout and session handling
- Profile updates and subscription status
- Password recovery and email confirmations

## Environment and Dependencies
- .NET 6+ or Go for core service logic
- A relational or NoSQL database for user data storage
- Containerization using Docker

## API Endpoints
- `/auth/register` for new account creation
- `/auth/login` for user login
- `/users/me` to fetch or update user profile

## Deployment and Usage
- Build locally with `dotnet run` or `go run main.go` (language-dependent)
- Containerize using `docker build -t photo-spotter-user-service .`
- Deploy to Kubernetes with minimal `deployment.yaml` and `service.yaml`

## Tasks
- Set up basic service scaffold
- Implement endpoints and authentication flow
- Integrate with continuous integration pipeline
- Provide a `/health` endpoint for status checks
