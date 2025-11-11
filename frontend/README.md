# Frontend (ultra-minimal)
Debes crear la app React desde cero (Vite recomendado).

## Sugerido
```bash
npm create vite@latest . -- --template react
npm install
npm run dev
```

Implementa:
- Página que consuma `GET /api/<recurso>` y liste elementos.
- Formulario para crear (POST), con validación en cliente y feedback de errores.
- Botón "Login demo" que pida `/api/login` y guarde el token en `localStorage`.
- Enviar `Authorization: Bearer demo-jwt` en POST/PUT/DELETE cuando haya token.
