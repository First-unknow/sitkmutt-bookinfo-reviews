# Bookinfo Rating Service

## How to run with Docker
```bash
# Build Docker Image for rating reviews
docker build -t reviews .

# Run reviews service on port 8080
docker run --name reviews -p 8082:9080 reviews
```
