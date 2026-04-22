# Orion CSS

Estructura recomendada del proyecto:

- `scss/`: archivos fuente en Sass (`.scss` y parciales con `_`).
- `css/`: archivos compilados que usa la documentación o las páginas de prueba.
- `docs/test/`: ejemplos HTML para probar estilos y componentes.

Comandos útiles:

```bash
npm run sass
```

Si usas VS Code con la extensión Live Sass Compiler:

- El proyecto ya incluye `.vscode/settings.json` para que solo compile `scss/estilos.scss` y `scss/componentes.scss`.
- La salida queda forzada hacia `css/`.
- Si tenías la extensión corriendo antes, detén `Watch Sass` y vuelve a iniciarlo para que tome la nueva configuración.

