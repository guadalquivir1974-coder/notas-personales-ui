# Notas Personales (UI dinámica)

App web para crear, ver, **editar** y eliminar notas.
Las notas se guardan en el navegador usando **localStorage** (no hay backend).

## Qué incluye esta versión
- Interfaz moderna (cards) y responsive
- **Modo claro/oscuro** (se recuerda)
- Animaciones suaves (crear/eliminar/reordenar)
- **Toasts** (guardado / eliminado / cambios guardados)
- **Edición con modal**
- Atajos:
  - En el formulario: **Enter** (en el título) guarda · **Ctrl/Cmd + Enter** (en el contenido) guarda
  - En el modal: **Esc** cierra · **Ctrl/Cmd + Enter** guarda cambios

## Ejecutar en GitHub Codespaces (recomendado)
1. Abre el repo en GitHub
2. Click **Code** → **Codespaces** → **Create codespace on main**
3. Cuando cargue, abre **Terminal**
4. Ejecuta:

```bash
npm install
npm run dev -- --host 0.0.0.0 --port 5173
```

5. Ve a la pestaña **PORTS** y abre el puerto **5173**.

## Ejecutar en local (opcional)
```bash
npm install
npm run dev
```

> Nota: si quieres sincronización entre dispositivos, el siguiente paso sería añadir backend + base de datos.
