# ENTREGA 2 – Desarrollo Web (CoderHouse)

Este paquete cumple con los requisitos solicitados:

## Estructura
- **3 HTML mínimos** con **estructura semántica** (`header`, `main`, `section`, `article`, `footer`) y **menú de navegación** en todos.
  - `index.html`: **100% Bootstrap** (navbar, grid, cards, botones). (**Opción a** del enunciado).
  - `about.html`: CSS propio + **alert** de Bootstrap (**Opción b**).
  - `gallery.html`: **CSS Grid + Media Queries** + **badge** de Bootstrap (**Opción b**) con layout mobile/desktop.
- **Alt completo** en todas las imágenes.
- **Box Model** demostrados con la clase `.box-example` en cada HTML.
- **Flex/Grid/Media Queries** usados en `gallery.html` (y flex helpers en `about.html`).

## CSS Avanzado
- `assets/css/styles.css` con:
  - Variables de color (misma gama violeta/dark del proyecto 1).
  - Gradientes, sombras, helpers de layout, utilidades.
  - `overflow-x` controlado para evitar desbordes.
  - Media queries para mobile/desktop.
  - Comentarios en cada sección explicando su propósito.

## Bootstrap
- Se incluyen los **CDN** de CSS/JS donde corresponde.
- `index.html` usa **Bootstrap completo** (grids, navbar, cards, botones, responsive).
- En páginas restantes se integra al menos **1 componente de Bootstrap**.

## Git/GitHub (sugerencia de flujo)
1. Inicializar repo:
   ```bash
   git init
   git add .
   git commit -m "Preentrega 2 - Estructura inicial"
   ```
2. Crear rama para estilos avanzados:
   ```bash
   git checkout -b feature/estilos-avanzados
   # editar, probar
   git commit -am "Estilos avanzados y MQ"
   git checkout main
   git merge feature/estilos-avanzados
   ```
3. Publicar en GitHub:
   ```bash
   git branch -M main
   git remote add origin https://github.com/USUARIO/REPO.git
   git push -u origin main
   ```
4. **GitHub Pages**:
   - Settings → Pages → Deploy from `main` → root.
   - URL pública: `https://USUARIO.github.io/REPO/`

## Recomendaciones de performance
- Optimiza imágenes antes de subirlas.
- Usa descripciones/meta correctas y títulos únicos.
- Verifica en navegadores (Chrome/Firefox/Edge).

---

**Nota:** Las imágenes incluidas son *placeholders* (violeta). Puedes reemplazarlas manteniendo el mismo nombre o actualizando las rutas.