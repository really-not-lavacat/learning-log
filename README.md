# Learning Log

My college project we have to publish please ignore it

## Deploy

You can deploy Learning Log using Docker Compose with following steps:

1. Copy `.env.example` to `.env`
2. Fill it
3. Run `docker compose up -d`
4. Verify if it works with `docker compose ps` and
   `docker compose logs --tail=100 web`

If it works, you're done, else you should debug it on your own
