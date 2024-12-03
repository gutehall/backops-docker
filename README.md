# BackOps Docker

This repository contains the source code and configuration for the BackOps application.

## Prerequisites

- Docker
- AWS CLI

## Setup

1. Clone the repository:
    ```sh
    git clone https://github.com/gutehall/backops.git
    cd backops
    ```

2. Build and run the Docker container:
    ```sh
    docker build -t backops-app .
    docker run -p 3000:3000 backops-app
    ```

3. Access the application at `http://localhost:3000`.

## Deployment

This repository is configured to be deployed using AWS CodePipeline and CodeBuild.