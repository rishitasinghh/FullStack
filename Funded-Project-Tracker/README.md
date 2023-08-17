# Funded-Project-Tracker System

A centralized online platform, with a web-application interface, to manage internally and externally funded **research projects**.

> Deployed as an internal web-application on the intra-network of the college. Currently under use at the Department of Computer Science for managing research project proposals, status, and outcomes.

It handles the following key aspects:
- Resource management, tracking, and repurposing for internally funded projects.
- Project status, updates, and outcomes repository for all projects in the past and present.
- Filterable and customized summary statistics of faculty and student projects, organized by domain and tech stack.
- Resource inventory and project deliverable/outcome report generation for all projects.


## Procedure to Execute

### Common Dependencies

- nodejs 16.15.0 LTS (preferably, with nvm)

### Frontend
- Navigate to ./FPTrack-frontend
- Install local dependencies using `npm install` from current context
- Run `npm run dev` to get the frontend service going

### Backend
- Navigate to ./FPTrack-backend
- Ensure that all `global installs` are done
- Install local dependencies using `npm install` from current context
- Run `npm run serverstart` to get the development server going

