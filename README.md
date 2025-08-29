<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

# Ejecutar en desarrollo (dev)

1. Clonar el repositorio
2. Ejecutar comando
```
npm install
```
3. Tener Nest CLI instalado
```
npm i -g @nestjs/cli
```
4. Levantar la base de datos
```
docker-compose up -d
```

5. Reconstruir la base de datos con la semilla (datos de prueba para dev)
```
http://localhost:3000/api/v1/seed
```

## Stack Usado
* MongoDB
* NestJS