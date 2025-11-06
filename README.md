# Dockerized Application Deployment

Cloud cost optimization through containerization and efficient resource management. Migrated legacy applications to Docker containers with Kubernetes orchestration.

## Features

- **Multi-Stage Builds**: Optimized Docker images
- **Docker Compose**: Local development and testing
- **Health Checks**: Container health monitoring
- **Resource Limits**: CPU and memory constraints
- **Production Ready**: Security best practices

## Quick Start

### Build and run

```bash
docker-compose up -d
```

### Build image

```bash
docker build -t app:latest .
```

### Run container

```bash
docker run -p 3000:3000 app:latest
```

## Architecture

- **Application**: Node.js application
- **Database**: PostgreSQL
- **Cache**: Redis
- **Reverse Proxy**: Nginx

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

MIT License

## Author

**Dmytro Bazeliuk**
- Portfolio: https://devsecops.cv
- GitHub: [@dmytrobazeliuk-devops](https://github.com/dmytrobazeliuk-devops)
