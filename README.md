# Java App CI/CD with Jenkins

This project sets up a CI/CD pipeline for a Java application using Jenkins.

## Features

- Automatic trigger via GitHub webhook (using ngrok to expose the jenkins instance url)
- Build and test with Maven
- Docker image creation
- Push to Docker Hub

## Pipeline Steps

1. Push to GitHub
2. Jenkins gets the code via webhook
3. Build and test the app
4. Build Docker image
5. Push image to Docker Hub

