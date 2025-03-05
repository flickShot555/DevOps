# Dockerized Flask Web Page

Welcome to the **Dockerized Flask Web Page** project. This repository contains a Flask web application that has been containerized using Docker and orchestrated with Docker Compose. The project demonstrates how to deploy a simple static web page using industry-standard DevOps practices.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Docker Usage](#docker-usage)
  - [Building the Docker Image](#building-the-docker-image)
  - [Running the Docker Container](#running-the-docker-container)
  - [Using Docker Compose](#using-docker-compose)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project serves as a practical example of containerizing a Flask web application. It guides you through setting up the application, building a Docker image, running the container, and managing the deployment with Docker Compose. This project is ideal for students and developers interested in DevOps and containerization best practices.

## Features

- **Simple Flask Application:** A static web page built with Flask.
- **Containerization:** Dockerfile included to containerize the application.
- **Docker Compose:** Easy orchestration with a `docker-compose.yml` file.
- **Step-by-Step Guide:** Instructions provided for building, running, and troubleshooting the application.

## Prerequisites

Before you begin, ensure you have the following installed on your system:

- [Docker Desktop](https://www.docker.com/products/docker-desktop)
- [Docker Compose](https://docs.docker.com/compose/)
- Python 3.8 or higher (if running locally)
- Git (optional, for cloning the repository)

## Project Structure

```plaintext
.
├── Dockerfile
├── docker-compose.yml
├── requirements.txt
├── src
│   ├── webapp.py       # Main Flask application file
│   └── ...             # Other source files and assets
└── templates
    └── index.html      # HTML template for the static web page
