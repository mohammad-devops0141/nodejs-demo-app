# Node.js Demo App

## Project Description
A Node.js application demonstrating automated CI/CD deployment using GitHub Actions and Docker.

## Technologies Used
- Node.js
- GitHub
- GitHub Actions
- Docker
- Docker Hub

## CI/CD Pipeline
The pipeline automatically runs when code is pushed to the `main` branch.

### Pipeline Steps
1. Checkout source code
2. Set up Node.js
3. Install dependencies
4. Run tests
5. Build Docker image
6. Push Docker image to Docker Hub

## Docker
The application is containerized using Docker. The Docker image is automatically built and pushed to Docker Hub through GitHub Actions.

## Local Setup

```bash
npm install
npm test
npm start

## Workflow

The GitHub Actions workflow is located at:

`.github/workflows/main.yml`

Docker Hub credentials are stored securely using GitHub Actions Secrets.
