# Workshop micromanga NodeJS

## Instalación

Por favor ingrese a: https://www.consul.io/downloads.html busque su sistema operativo y descargue la aplicación

```bash
consul agent -dev
```

## Ejecución

Para ejecutar los servicios por favor ingrese los siguientes comandos

```bash
npm start ./src/services/auth/login.js -- --listen tcp://localhost:3001
npm start ./src/services/auth/register.js -- --listen tcp://localhost:3002
npm start ./src/gateway.js
```

Verifique el estado de ejecución en la siguiente URL:
http://localhost:8500/
