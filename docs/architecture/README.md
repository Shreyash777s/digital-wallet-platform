# Architecture

## Overview

The Digital Wallet Platform is a full-stack application
with separate customer and operations portals.

## Backend Architecture

- DigitalWallet.Api: Customer-facing API
- DigitalWallet.Admin.Api: Operations API
- DigitalWallet.Services: Business logic
- DigitalWallet.Repositories: Data access implementations
- DigitalWallet.Data: Entity Framework Core and database configuration
- DigitalWallet.Entities: Domain entities
- DigitalWallet.Contracts: DTOs and interfaces
- DigitalWallet.Common: Shared utilities and exceptions
- DigitalWallet.Integrations: External service integrations
- DigitalWallet.Jobs: Background processing

## Frontend Architecture

- Customer Portal: Angular application for customers
- Operations Portal: Angular application for operations staff

## Database

SQL Server will be used as the primary relational database.

Entity Framework Core will handle object-relational mapping and migrations.

## Development Approach

The application will be developed incrementally through sprints.
Each sprint will include backend development, frontend integration,
testing, and deployment.