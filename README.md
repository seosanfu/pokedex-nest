<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Ejecutar en desarrollo

1. Clonar el repo
2. Ejecutar 
```
yarn install
```
3. Tener Nest CLI instalado
```
npm i -g @nestjs/cli
```
4. Levantar la base de datos
```
docker-compose up -d
```
5. Reconstruir la base de datos con la semilla
```
http://localhost:3005/api/seed
```
## Stack usado
* MongoDB
* Nest

# Notas
Heroku redeploy sin cambios:
```
git commit --allow-empty -m "Tigger heroku deploy"
git push heroku <master|main>
```