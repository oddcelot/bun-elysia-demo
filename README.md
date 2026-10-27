# bun-elysia-demo

A minimal [Elysia](https://elysiajs.com) server for [Bun](https://bun.sh).

    bun install
    bun index.ts

Routes: `GET /`, `GET /json`, `GET /user/:id`, `POST /echo` (body `{ "name": string }`, else 422).
