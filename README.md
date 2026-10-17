# nfc-tools

Paquete de herramientas compartidas que puede usar el proyecto.

Forma parte del proyecto **neofile-citizen** (`nfc`) — Ingeniería para el Desarrollo Móvil (posgrado) · CORHUILA 2026-B.

| | |
|---|---|
| Rol | Paquete de herramientas |
| Contenerizado | Sí: se entrega con su `Dockerfile`. |
| Gobierno y documentación | [`nfc-docs`](https://github.com/code-corhuila/nfc-docs) |
| Backlog | GitHub Project `nfc-backlog` |

## Ramas

| Rama | Uso |
|---|---|
| `develop` | Integración (rama por defecto) |
| `qa` | Pruebas |
| `main` | Producción |

**Todo cambio a `develop`, `qa` o `main` entra por pull request.** Ninguna de las tres admite
commits directos, force-push ni borrado (tampoco para administradores).

1. Trabajo diario: rama `feat/<tema>` o `fix/<tema>` desde `develop` → PR a `develop`.
2. Promoción: PR `develop` → `qa` y PR `qa` → `main`.
3. El PR a `main` necesita la aprobación del docente. La rama de trabajo se borra al fusionar.

## Repositorios del proyecto

| Repositorio | Rol |
|---|---|
| [`nfc-docs`](https://github.com/code-corhuila/nfc-docs) | Gobierno único del proyecto |
| [`nfc-api`](https://github.com/code-corhuila/nfc-api) | Core de negocio (API) |
| [`nfc-app`](https://github.com/code-corhuila/nfc-app) | Aplicación móvil |
| [`nfc-portal`](https://github.com/code-corhuila/nfc-portal) | Portal web |
| [`nfc-db`](https://github.com/code-corhuila/nfc-db) | Migraciones de base de datos |
| [`nfc-infra`](https://github.com/code-corhuila/nfc-infra) | Infraestructura y orquestación |
| [`nfc-tools`](https://github.com/code-corhuila/nfc-tools) | Paquete de herramientas |
