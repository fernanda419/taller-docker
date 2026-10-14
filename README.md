# Gestor de tareas contenerizado

## Integrantes
- [Nombre completo 1]
- [Nombre completo 2]

## Servicios
| Servicio | Tecnología | Función |
|---|---|---|
| frontend | nginx | Página web, puerto 8080 |
| api | Python 3.12 + Flask | API de tareas |
| bd | MySQL 8.4 | Base de datos con volumen |

## Requisitos
- Docker Desktop abierto (Engine running)
- Git

## Cómo ejecutarlo
1. git clone [enlace de este repositorio]
2. cd [nombre de la carpeta]
3. Copy-Item .env.example .env
4. docker compose up -d --build
5. Abrir http://localhost:8080

## Cómo detenerlo
docker compose down