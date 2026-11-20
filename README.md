# NetWatch — Network & IT Infrastructure Management System

A portfolio project designed around practical **D3 Computer Technology** skills: network operations, device inventory, IP address planning, troubleshooting workflows, preventive maintenance, and operational reporting.

## Project goals
- Practice network inventory and IP address management concepts.
- Visualize a small campus/office network topology.
- Document incident/ticket workflow from open to resolved.
- Organize preventive maintenance tasks.
- Produce CSV reports for operational records.

## Features
- Operations overview with simulated health and utilization indicators.
- Clickable network topology (core, distribution, access layer).
- Device inventory: search, filter, add device, inspect status.
- IP Address Manager: subnet/VLAN cards, utilization bars, assignments, add subnet, CSV export.
- Service ticket workflow: create, priority, search/filter, move to In Progress, resolve.
- Maintenance planner and preventive checklist.
- Operational report export.
- Browser localStorage persistence for devices and tickets.
- Responsive interface.

## Run locally
No installation is needed. Extract the ZIP and open `index.html` in a modern browser. For a better local development experience, use VS Code with Live Server.

## Important scope
This is a **front-end simulation**. It does not ping devices, read SNMP, connect to routers/switches, or collect live telemetry. Device health and metrics are demo data. This limitation is clearly stated in the application.

## Suggested future upgrades
1. Python Flask REST API.
2. SQLite or PostgreSQL database.
3. Login and role-based access (Admin, Technician, Viewer).
4. Real ICMP ping checks using a backend worker (only against authorized lab devices).
5. SNMP monitoring for authorized equipment.
6. Docker Compose for app + database.
7. Deployment to a cloud VM.
8. CI checks with GitHub Actions.

## Tech stack
HTML5 · CSS3 · Vanilla JavaScript · localStorage · SVG

## Portfolio learning outcomes
- Network topology and layered network design concepts.
- Device inventory and network address management.
- Incident handling and troubleshooting documentation.
- Preventive maintenance planning.
- CSV reporting and client-side state management.
- Responsive UI and practical documentation.

## Author
Dora Sianipar — D3 Computer Technology portfolio project.
