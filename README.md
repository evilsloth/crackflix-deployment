# Crackflix deployment

Each directory contains configuration for specific deployment type:
- master - deploys latest images from master branches
- release - deploys last release images (with latest tag)

## Configuration

All Debrid agent and api key must be provided:
```
export CRACKFLIX_ALL_DEBRID_AGENT=agent
export CRACKFLIX_ALL_DEBRID_API_KEY=api_key
```

# Run

```
cd release
docker-compose up -d
```