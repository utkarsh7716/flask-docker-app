# Flask Docker App

A Flask app deployed to AWS EC2 using Docker and GitHub Actions.

## Features
- Flask web app
- Dockerized container
- CI/CD using GitHub Actions

## Deployment

On every push to `main`, the app is:
- Pulled to EC2
- Docker image rebuilt
- Old container removed
- New one deployed on port 5000
