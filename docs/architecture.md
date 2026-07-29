# Architecture

## Goals

Gramps Web should run on Render without Docker Compose.

## Principles

- Stateless application containers
- Managed PostgreSQL
- Managed Redis
- External object storage
- Immutable deployments
- Automatic health checks
- Automatic deployments

## Components

Web Service
Worker
PostgreSQL
Redis
Cloudflare R2
