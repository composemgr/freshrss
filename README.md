# Freshrss

A self-hosted application for managing freshrss.

## Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/freshrss/main/docker-compose.yaml" | docker compose -f - up -d
```

### Option 2: Git Clone
```bash
git clone "https://github.com/composemgr/freshrss" ~/.local/srv/docker/freshrss
cd ~/.local/srv/docker/freshrss
docker compose up -d
```

### Option 3: Using composemgr
```bash
composemgr install freshrss
```

## Configuration

See docker-compose.yaml for environment variables and configuration options.

## Documentation

Check the official project documentation for detailed setup and usage information.
