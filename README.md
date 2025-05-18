# n8n en la nube

Este repositorio contiene una configuración lista para desplegar n8n usando Docker, ya sea localmente o en servicios como Render, Railway, u Oracle Cloud.

## Requisitos

- Docker
- Docker Compose (para uso local)

## Uso

### Local

\\\ash
docker-compose up -d
\\\

Luego abre http://localhost:5678

### Nube (Render / Railway)

- Usa el Dockerfile.
- Agrega las variables de entorno de .env.

---
