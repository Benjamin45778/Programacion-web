
# PixelPlay Games — Actividad S1: Creando interfaz gráfica
- 1 página de **inicio** con el nombre de la PYME y **lista de 5 categorías** con imagen y enlace.
- 5 páginas de **categoría**; cada una lista **máximo 2 juegos** con **imagen, nombre, descripción y precio**.
- Navegación para volver al **inicio** y moverse entre categorías.
- **HTML + CSS** puro, sin frameworks.

## Cómo usarlo (VS Code + Live Server)

1. Abre la carpeta en **VS Code**.
2. Instala la extensión **Live Server** (Ritwick Dey).
3. Haz clic derecho sobre `index.html` → **Open with Live Server**. Se abrirá en tu navegador.
4. Edita textos, colores y precios directamente en los archivos `.html` y `styles.css`.

## Git (colaboración rápida)

```bash
git init
git add .
git commit -m "Inicio del proyecto (S1)"
git branch -M main
git remote add origin <URL_de_tu_repo>
git push -u origin main
```

Sugerencia de flujo en equipo: ramas por tarea (p. ej., `estilos/cabecera`, `contenido/categoria-accion`), y **Pull Requests** para revisar cambios antes de mezclar con `main`.

## Personalización

- Cambia `PixelPlay Games` por el nombre de su PYME.
- Reemplaza `assets/placeholder.svg` por imágenes reales.
- Ajusta colores desde las **CSS variables** en `styles.css`.
- Puedes duplicar una página de categoría para crear otras variaciones si lo necesitan.
