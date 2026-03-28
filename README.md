# Organizational-Structure

This repository maintains the organizational structure of Segura Intelligence Holdings Group and its affiliated entities.

## Company Entities

The company entities are stored in [`companies.json`](./companies.json).

### Structure

- **Segura Intelligence Holdings Group LP** *(Parent Holding Company)*
  - **IT Specialties, LP** *(Subsidiary)*
  - **Segura Mgmt LLC** *(Management Company)*
  - **BPS Industries LLC** *(Subsidiary)*

## Data Format

Each entity in `companies.json` includes:

| Field | Description |
|-------|-------------|
| `id` | Unique identifier |
| `name` | Legal entity name |
| `type` | Entity type (e.g., Limited Partnership, LLC) |
| `role` | Role within the organizational structure |
| `parent_id` | ID of the parent entity (`null` for the top-level entity) |
| `subsidiaries` | List of IDs of direct subsidiaries |