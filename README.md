#Tasks For FOSSCell Dev Team Inductions

##Task 1  

###Open Source Web Development Task  

The goal is to build an  **end-to-end open source web application**, fully self-hosted, that uses an **open source database**, is **containerized**, and is structured in a way that you can **contribute parts of it back to open source** (docs, tooling, integrations, or fixes).

You should design, build, deploy, and document the system like a real open-source maintainer.

Build a **Lightweight Issue & Task Tracking Platform** (think: a minimal GitHub Issues / Jira clone) with:

- A REST API backend
- A frontend web UI
- An open source database
- Authentication 
- Analytics (basic)
- Full containerized deployment
- Public documentation

The idea suggested is optional. You can implement whatever idea you have or problem you want to solve but it should contain all the above mentioned points. Minimal importance is given to frontend(but if it is creative, that will also be considered). However deployment is a must.  
Extra points will be given if an in-memory database is used to cache/queue.  
Similarly if services are decoupled and loosely connected i.e microservice architecture with kafka or rabbitMQ would be impressive.  

For Hosting it is recommended that you self host your services. You may use any containerization platform of your choice(however we may ask you why you chose the specific platform).  

###Do document all the steps.  

As for containerization, you **must**
- Write a `Dockerfile` for backend
- Write a `Dockerfile` for frontend
- Use **Docker Compose** to run:
  - Backend
  - Frontend
  - Database
  - Redis (if used)

Use industry best practices for environment and configuration

- Use `.env` files
- No secrets hardcoded
- Configurable DB host, port, credentials  


As for documentation, you must write:
- `README.md`
- `SETUP.md`
- `ARCHITECTURE.md`(Optional)
- `CONTRIBUTING.md`

Documentation should include:
- Local setup
- Deployment steps
- API overview
- DB schema explanation

Bonus (Optional but Impressive)
- GitHub Actions CI
- Rate limiting
- Role-based access
- Prometheus + Grafana
- Helm chart
- Kubernetes (later phase)


