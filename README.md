## Docker
```
docker build -f docker/Dockerfile -t your-image-name .

wsl --shutdown

taskkill /f /im "Docker Desktop.exe"
taskkill /f /im "com.docker.backend.exe"
taskkill /f /im "dockerd.exe"

docker compose up -d --build

```
