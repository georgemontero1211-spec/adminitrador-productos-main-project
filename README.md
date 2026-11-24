# Administrador de Productos

Repositorio principal del proyecto **Administrador de Productos**, una aplicación full stack para gestionar un catálogo de productos. Junta el backend y el frontend como submódulos de Git.

| Submódulo | Descripción |
| --------- | ----------- |
| [`REST-API-Node-TypeScript`](https://github.com/georgemontero1211-spec/REST-API-Node-TypeScript) | API REST con Express, TypeScript, Sequelize y PostgreSQL, con Swagger y pruebas con Jest |
| [`administrador-productos-client`](https://github.com/georgemontero1211-spec/administrador-productos-client) | Frontend con React, TypeScript, React Router (loaders y actions) y Tailwind CSS |

## Clonar el proyecto

```bash
git clone --recurse-submodules https://github.com/georgemontero1211-spec/adminitrador-productos-main-project.git
```

Si ya lo clonaste sin los submódulos:

```bash
git submodule update --init --recursive
```

## Cómo ejecutarlo

1. **Backend**: entra en `REST-API-Node-TypeScript`, crea el `.env` (`DATABASE_URL`, `FRONTEND_URL`, `PORT`) y ejecuta `npm install && npm run dev`.
2. **Frontend**: entra en `administrador-productos-client`, crea el `.env` con `VITE_API_URL` apuntando al backend y ejecuta `npm install && npm run dev`.

El README de cada submódulo tiene los detalles.
