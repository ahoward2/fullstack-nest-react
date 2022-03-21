# Fullstack react + nest js

> Basic single page react application with an http backend server built with nest js.

## How to run

**Fullstack development**

Concurrently runs the react client with hot reloading and the go server. Requests from the client in development are proxied to the server port.

- `Client port`: 3002
- `Nest server port`: 8080

```bash
yarn dev:fullstack
```

**Build the client react app**

```bash
yarn build:client
```

**Build the server nest app**

```bash
yarn build:server
```

**Start production server nest app**

```bash
yarn start:prodserver
```

- GET `8080/` route returns hello world json payload
