# PMTP Agency Commission Dashboard

**Point Me to Paradise Travel — Internal Use Only**

This is the agency-wide commission tracking dashboard for Christina Garcia, owner of Point Me to Paradise Travel. It aggregates commission data from all agents into a single searchable, filterable view.

## Access

- Owner access only — login required
- URL: (add your deployed URL here)
- Credentials managed via Supabase Authentication

## What It Does

- Displays all agent commission payments and pending commissions in one place
- Filters by agent, client, booking reference, supplier, year, amount, and status
- Global search across all fields
- Per-agent subtotals and agency grand totals
- Export filtered results to CSV

## Data Source

Commission data is mirrored from each agent's individual dashboard into the agency Supabase database automatically when agents save commission records.

**Agency Supabase:** `voowpwzpilymtaeskmom.supabase.co`

## Tables

- `agency_payments` — received commissions from all agents
- `agency_pending` — pending/expected commissions from all agents

## Tech Stack

- HTML / React (CDN) — no build process required
- Supabase — authentication and database
- GitHub Pages / Vercel — hosting

## Agent Dashboards

Each agent has their own individual dashboard that feeds into this agency view. Agent dashboards are managed separately under the PMTP Agent Operations Dashboard project.
