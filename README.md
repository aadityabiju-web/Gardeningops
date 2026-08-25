# GardenOps

GardenOps is a web application for managing landscaping Annual Maintenance Contracts (AMC).

## Current scope

- Client and property management
- Site sections / garden zones
- Maintenance tasks and schedules
- Maintenance calendar
- Workforce instructions and updates
- Issues, inventory and reporting modules
- Supabase backend integration

## Development status

The application is currently being built in stages. The temporary email-login screen has been removed so the operational interface can be reviewed without setting up an email provider.

Authentication and role-based access will be enabled before production use. Backend security and client data isolation remain part of the production setup.

## Deployment

The `main` branch is connected to the GardenOps Vercel deployment.

## Environment variables

The Vite frontend expects:

- `VITE_SUPABASE_URL`
- `VITE_SUPABASE_ANON_KEY`

Do not commit private Supabase service-role credentials to the repository.
