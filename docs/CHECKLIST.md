# Checklist de Logro
## API y Validación
- [ ] `GET /api/<recurso>` devuelve lista (**200**).
- [ ] `POST /api/<recurso>` inválido → **400** con detalles.
- [ ] `POST /api/<recurso>` válido → **201** con el objeto creado.
- [ ] (Mongo) Persistencia OK (reinicio no pierde datos).
- [ ] `PUT /api/<recurso>/:id` → **404** si no existe; **200** si actualiza.
- [ ] `DELETE /api/<recurso>/:id` → **204** al eliminar.

## Frontend
- [ ] Lista inicial desde `/api/<recurso>`.
- [ ] Botón crear **deshabilitado** si form inválido.
- [ ] Mensaje claro ante **400** del backend.
- [ ] (Auth) Sin token → **401** en POST/PUT/DELETE y la UI lo explica.
- [ ] (Auth) Con token demo → operaciones protegidas funcionan.

## Auth mock
- [ ] Existe `/api/login` que devuelve `{ token: "demo-jwt" }`.
- [ ] Middleware `requireAuth` protege POST/PUT/DELETE.

## Códigos HTTP
- [ ] 200 (lecturas), 201 (creación), 204 (borrado), 400 (validación), 401 (sin token), 404 (inexistente).
