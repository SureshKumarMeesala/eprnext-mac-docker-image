Everything about Frappe and ERPNext in containers.

Getting Started
To get started you need Docker, docker-compose, and git setup on your machine. For Docker basics and best practices refer to Docker's documentation.

Once completed, chose one of the following two sections for next steps.

Try in Play With Docker
To play in an already set up sandbox, in your browser, click the button below:

Try in PWD
Try on your Dev environment
First clone the repo:

git clone https://github.com/frappe/frappe_docker
cd frappe_docker
Then run: docker compose -f pwd.yml up -d

Final steps
Wait for 5 minutes for ERPNext site to be created or check create-site container logs before opening browser on port 8080. (username: Administrator, password: admin)

If you ran in a Dev Docker environment, to view container logs: docker compose -f pwd.yml -d. Don't worry about some of the initial error messages, some services take a while to become ready, and then they go away.

Documentation
Production
List of containers
Single Compose Setup
Environment Variables
Single Server Example
Setup Options
Site Operations
Backup and Push Cron Job
Port Based Multi Tenancy
Migrate from multi-image setup
running on linux/mac
Custom Images
Custom Apps
Build Version 10 Images
Development
Development using containers
Bench Console and VSCode Debugger
Connect to localhost services
Troubleshoot
Contributing
If you want to contribute to this repo refer to CONTRIBUTING.md

This repository is only for container related stuff. You also might want to contribute to:

Frappe framework,
ERPNext,
Frappe Bench.
