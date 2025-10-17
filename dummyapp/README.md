# Dummy App for Azure DevOps Pipeline Testing

This is a minimal Flask app used to test Azure DevOps build & push pipelines with code sourced from GitHub.

## Run locally
```bash
docker build -t dummy-app .
docker run -p 8080:8080 dummy-app
