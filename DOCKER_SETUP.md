# 🚀 Cómo ejecutar este proyecto

## ¿Qué necesitas?

- Docker instalado en tu computadora
- Nada más

## ¿Tienes Docker instalado?

```bash
docker --version
```

Si no tienes Docker, descárgalo desde: https://www.docker.com/get-started

## Pasos súper simples

### 1. Descargar el proyecto

```bash
git clone <URL_DEL_REPO>
cd <NOMBRE_DEL_PROYECTO>
```

### 2. Construir la aplicación

```bash
docker build -t flask-docker-app .
```

### 3. Ejecutar la aplicación

```bash
docker run -p 5000:5000 flask-docker-app
```

¡Eso es todo! 🎉

## ¿Dónde veo mi aplicación?

Abre tu navegador y ve a: **http://localhost:5000**

## Comandos básicos

```bash
# Construir la aplicación
docker build -t flask-docker-app .

# Ejecutar en segundo plano
docker run -p 5000:5000 flask-docker-app

# Ver qué está corriendo
docker ps

# Parar la aplicación
docker stop mi-app-corriendo
```
