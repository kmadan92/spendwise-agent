# Spendwise Agent

Spendwise Agent is organized as a monorepo with a Next.js frontend and a
FastAPI backend.

## Repository layout

```text
backend/   FastAPI service
frontend/  Next.js application
```

## Local setup

### Prerequisites

- Node.js and npm
- Python

### Configure environment

From the repository root, copy the example files and provide local values:

```text
frontend/.env.example -> frontend/.env.local
backend/.env.example  -> backend/.env
```

Do not commit local environment files. The example files contain placeholders
only.

The frontend and backend directories are scaffolding at this stage; their
dependency manifests and application start commands will be added with the
service implementation.
