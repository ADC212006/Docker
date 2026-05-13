# Docker

## Docker install vecedile (VICIdial) for VOIP calling system

This repository now includes a minimal Docker Compose setup to run a vecedile/VICIdial VOIP environment.

### Prerequisites
- Docker Engine
- Docker Compose plugin (`docker compose`)

### Start
```bash
docker compose up -d
```

### Stop
```bash
docker compose down
```

### Access
After startup, open:
- `http://localhost` for the VICIdial web interface

SIP/RTP ports are also exposed for softphone and VOIP traffic.
