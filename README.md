# Playground

Play with mobile UI on the fly.

## Getting Started

```bash
./gradelew assemble && docker-compose up -d --build
```

```bash
curl -X POST -H 'Content-Type: application/json' http://localhost:8080/api/render -d '{"options":{"debug":true}}'
```

## The underlying - Sandbox

This playground is based on the [Sandbox](https://github.com/johnsonlee/sandbox) project
