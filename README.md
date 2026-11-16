# Mezze & Tapeo

Recetario personal en una sola página (`index.html`), pensado para usarlo en el iPhone anclado a la pantalla de inicio.

## Qué incluye esta versión

- Las 57 recetas de siempre, cada una con una pestaña nueva **Robot**: la versión para el Monsieur Cuisine Compact, con cantidades ajustadas al vaso de 1,5 L y los pasos con tiempo, temperatura y velocidad.
- 51 recetas nuevas hechas para el robot, en dos categorías nuevas: **Cocina con robot** (35) y **Postres** (16).

## Publicarla en GitHub Pages

1. En github.com, crea un repositorio nuevo llamado `mezze` (público: GitHub Pages gratis solo funciona con repositorios públicos).
2. Pulsa **Add file → Upload files**, arrastra `index.html` y este `README.md` y confirma con **Commit changes**.
3. Ve a **Settings → Pages**. En **Build and deployment**, elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`, y guarda.
4. En uno o dos minutos GitHub te muestra arriba la dirección de la web, del tipo `usuario.github.io/mezze`.
5. En el iPhone, ábrela en Safari → **Compartir → Añadir a pantalla de inicio**.

Para actualizarla más adelante, sube el nuevo `index.html` encima del anterior (Add file → Upload files). La web se actualiza sola en un par de minutos.

## Antes de dejar Netlify

Tus favoritos, recetas propias, lista de la compra y clave de Gemini se guardan en el propio navegador, ligados a la dirección de la web. Al cambiar a GitHub empezarás con la app vacía de esos datos:

1. En la versión de Netlify, exporta la copia de tus recetas propias.
2. En la nueva versión de GitHub, impórtala y vuelve a pegar tu clave de Gemini.

La clave de Gemini no está dentro del archivo: se guarda solo en tu móvil, así que el repositorio público no la expone.
