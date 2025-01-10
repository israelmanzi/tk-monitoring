# How to Run the Application

## Step 1: Build and Start the Docker Containers

Run the following command to build the application and start all services in detached mode:

```bash
docker compose up --build -d
```

## Step 2: Configure the Faro Client

In your Faro client configuration, set the collector URL to:

```json
"collectorUrl": "http://localhost:8027/collect"
```
