# Dockerized Apache Web Server

## Overview

This project demonstrates how to set up an Apache web server using Docker with an Ubuntu base image. It provides a simple and efficient way to deploy and manage a web server in a containerized environment.

## Features

- **Lightweight**: Built on the latest Ubuntu image.
- **Easy Setup**: Quick to build and run with Docker.
- **Customizable**: Easily modify configurations and add content.
- **Port Exposure**: Serves content on port 80.

## Prerequisites

- [Docker](https://www.docker.com/get-started) installed on your machine.
- Basic knowledge of the command line and Docker.

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/yourusername/docker-apache-server.git
cd docker-apache-server

# Build the Docker Image

docker build -t my-apache-server.

# Run the Docker Container

docker run -d -p 80:80 my-apache-server

### Access the Server

Open your web browser and navigate to [http://localhost](http://localhost) to see your Apache server running.

![Docker Project2 Output](https://github.com/user-attachments/assets/26e5b88b-67b3-4782-9a5d-f7f501031a06)

![apache](https://github.com/user-attachments/assets/8b43609b-f18a-4221-b40a-ac75ff399247)


