# .NET Core Microservices Project
This repository contains two microservices, CommandsService and PlatformService, along with Kubernetes configurations for deployment. Below, you will find an overview of the project structure, features, and setup instructions.
# Overview
This project demonstrates a microservices architecture built using .NET Core. It consists of two services: <br />
- CommandsService: Handles commands and related data. 
- PlatformService: Manages platform-related data and synchronization.

The services communicate via HTTP and support scalability and deployment using Kubernetes.
# Project Architecture
## PlatformService
## CommandsService

# Services
## CommandsService
CommandsService is a .NET Core Web API responsible for managing commands.
## Structure
- Controllers: Handles incoming HTTP requests.
- Data: Contains data access logic.
- Dtos: Defines Data Transfer Objects.
- Models: Represents domain models.
- Profiles: Contains AutoMapper configurations.
- Properties: Configuration files like launchSettings.json.
## Key Files
- CommandsService.csproj: Project file for the service.
- Dockerfile: Docker configuration for containerizing the service.
- appsettings.*.json: Configuration files for different environments.
- CommandsService.http: HTTP client configuration for testing API endpoints
