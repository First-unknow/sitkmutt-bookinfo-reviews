# Bookinfo Rating Service

## How to run with Docker
```bash
# Build Docker Image for rating reviews
docker build -t reviews .

# Run reviews service on port 8082
docker run --name reviews -p 8082:9080 reviews
```

## How to run with Docker Compose

```bash
docker-compose up
```