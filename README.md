# Products Microservice

## Dev

1. Clone repository
2. Install dependencies
3. Create `.env` file based on `.env.template`
4. Start NATS server

```
docker run -d --name nats-main -p 4222:4222 -p 6222:6222 -p 8222:8222 nats
```

5. Execute prisma migration `npx prisma migrate dev`
6. Execute `npm run start:dev`
