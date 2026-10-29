# Infra project

Учебный инфраструктурный репозиторий курса 

Change via Web UI
## Запуск в Docker
```bash
docker build -t infra-web:1.0 docker/
docker run -d --name infra-web -p 8000:80 infra-web:1.0
