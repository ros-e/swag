## Swag

Clean elysia backend

### Stack

[Bun](https://bun.com/)
[Drizzle](https://orm.drizzle.team/)
[PostgreSQL](https://www.postgresql.org/)
[Redis](https://redis.io/)
[Biome](https://biomejs.dev)

### Setup

```bash
bun install && cp .env.example .env
```

After configuring `DATABASE_URL` in `.env`, generate/apply the migrations

```bash
bun run db:generate
bun run db:migrate
```
