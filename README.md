#Product Microservice

##dev

1. CLonar el repositorio
2. Instalar dependencias
3.Crear archivo `.env` basado en el `.env.template`
4. Ejecutar Micracion de prisma `npx prisma migrate dev`
5. Levantar servidor de Nats
```
docker run -d --name nats-server -p 4222:4222 -p 8222:8222 nats
```
6. Ejecutar `npm run start:dev`