# Docker Static Website Project

This is a lightweight Docker container for serving static websites using Apache HTTP Server.

## Project Structure
- `Dockerfile` - Alpine-based Apache container configuration
- `httpd.conf` - Apache configuration file
- `index.html` - Default static file
- `compose.yaml` - Docker Compose configuration
- `LICENSE` - MIT License
- `README.md` - Project documentation

## Key Features
- Uses Alpine Linux 3.22.1 with BusyBox 1.37.0
- Apache HTTP Server for serving static content
- Minimal container size
- Designed for static website deployment

## Usage
```bash
docker-compose up -d
```

The server will be available at http://localhost:8080