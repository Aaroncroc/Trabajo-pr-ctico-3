# FastAPI Docker Project

Este proyecto es una API sencilla hecha con FastAPI y Dockerizada.

## Comandos básicos

### Levantar el servidor
```bash
uvicorn app.main:app --reload
```

### Construir imagen Docker
```bash
docker build -t fastapi-app .
```

### Ejecutar contenedor Docker
```bash
docker run -d -p 8000:8000 fastapi-app
```
