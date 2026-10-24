# Customer Feedback Dashboard

This repository currently contains configuration and deployment-related files for a planned customer-feedback dashboard. The frontend and backend source folders described in the previous README are not present in the current repository snapshot.

## Files currently included

- `.env.example` — environment-variable template
- `ci.yml` — CI workflow configuration
- `docker-compose.prod.yml` — production Compose configuration
- `README.md` — project notes

## Intended technology direction

The previous project description referenced React with TypeScript, NestJS, TypeORM, PostgreSQL, Redis, Docker, and monitoring tools. These should be treated as planned components until the corresponding application code and working configuration are committed here.

## Current status

The application is not reproducible from this repository alone because the source code and some referenced configuration files are missing. Local startup, automated tests, container builds, and production deployment instructions cannot be verified from the current contents.

## Before presenting this as a runnable project

1. Add the frontend and backend source code.
2. Confirm that Compose file paths, ports, and environment variables match the actual services.
3. Add reproducible setup instructions and tests.
4. Run the documented commands and update this README with verified results.

This README intentionally describes the repository as it exists today rather than claiming unverified functionality.
