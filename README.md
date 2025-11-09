# SwiftGram (Monorepo)

Telegram-style messaging app.

- **server/** — Spring Boot backend (Java)
- **infra/** — Docker Compose: Postgres, Redis, NATS, MinIO
- **client/** — React (to be added)

## Run backend
1) docker compose -f infra/docker-compose.yml up -d
2) cd server
3) ./gradlew bootRun
4) Open http://localhost:8080/health
