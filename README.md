# bun-elysia-demo

A minimal [Elysia](https://elysiajs.com) server for [Bun](https://bun.sh).

[![Open in runbun](https://runbun.dev/badge.svg)](https://runbun.dev/?repo=oddcelot/bun-elysia-demo)

    bun install
    bun index.ts

Routes: `GET /`, `GET /json`, `GET /user/:id`, `POST /echo` (body `{ "name": string }`, else 422).
