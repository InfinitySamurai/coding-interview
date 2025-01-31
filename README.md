# Technical Challenge
This repository is the starting point of a full-stack developer technical challenge.  You'll need to have Node (v20.9.0), NPM (v10.1.0), and Docker installed on your machine.  If you need to install any of these, here are some helpful links:

- [Node and NPM](https://nodejs.org)
- [Docker Desktop](https://docs.docker.com/desktop)

With those installed, this monorepo contains everything needed to run the entire application by supporting the following actions:

- Installing dependencies, launching, and initializing a containerized (Docker) Postgres database using the `docker-compose up` command after navigating to the root of the repository.
- Installing dependencies and launching a backend API (Nest, Node, TypeScript) using the `npm install` and `npm start` commands after navigating to the `/server` directory.
- Installing dependencies and launching a frontend UI (React, JavaScript) using the `npm install` and `npm start` commands after navigating to the `/client` directory.

As is, the application has a Home page and a Contacts page.  The Contacts page supports viewing a list of all existing contacts and creating new contacts.

