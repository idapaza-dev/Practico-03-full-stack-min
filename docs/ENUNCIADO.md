# DES421 · Práctica de Repaso (135 min) — Ultra-minimal
**Tema sugerido:** Recetas (`name`, `category`). Puedes cambiar de tema si lo prefieres.

## Objetivo
Implementar un flujo full-stack mínimo desde cero (sin boilerplate funcional):
1) API REST con Express (GET/POST y validación).
2) Persistencia con MongoDB + Mongoose (PUT/DELETE).
3) Frontend React que consuma la API (listar/crear con validación de cliente).
4) Auth mock: `/api/login` → `{ token: "demo-jwt" }`; proteger POST/PUT/DELETE.

## Reglas
- No se entrega código funcional, solo esqueletos y TODOs.
- TODO debe ser implementado por el equipo.
- Entregable: carpetas `/backend` y `/frontend` funcionando en local con README breve.

## Sugerencia de tiempos
- 0–10’ Encadre y diseño del recurso
- 10–35’ API mínima (in-memory, GET/POST + validación)
- 35–60’ Mongo + PUT/DELETE
- 60–95’ Frontend (lista + crear + feedback)
- 95–120’ Auth mock + pruebas 401/201/204
- 120–135’ Demo corta + checklist
