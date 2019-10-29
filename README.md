# Multi-Container Example

I wanted to set up a small project that users multiple Docker containers.

Containers are set up for a React front-end, Express API, Express worker process, Redis cache, PostgreSQL database, and Nginx server.

The Nginx server routes requests for either the front-end or the API to the appropriate container.