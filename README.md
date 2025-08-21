# 🛠️ DevOps Fundamentals 

Repositorio educativo para aprender los fundamentos de DevOps mediante la implementación de un sitio estático Docker y Zola 



# 🚀 Despliegue local

### Requisitos
- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)
- Git

### Pasos para clonar y ejecutar
```bash
# 1. Clona el repositorio
git clone --recursive https://github.com/RenzoMedina/devops-fundamentals.git
cd devops-fundamentals

# 2. Construye la imagen del sitio Hugo
docker build -t zola_demo .
o 
docker-compose up

# 3. Levanta los servicios con Dockerfile.dev
docker compose watch
```

