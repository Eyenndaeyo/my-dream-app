## CI/CD Pipeline

This project uses GitHub Actions for automated Docker builds and deployments:

- Triggers on pushes/PRs to `main` or `dev`
- Builds Docker images for frontend and backend
- Pushes images to Docker Hub using commit SHA tags
- Uses secrets for authentication
