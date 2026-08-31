# Cartera Bladi — versión pública segura

Esta carpeta **sí** se puede subir a un repositorio público de GitHub Pages.

## Qué queda público
La interfaz y datos de demostración ficticios. No contiene tus posiciones, cantidades, costos, historial, dividendos ni watchlist real.

## Qué NO debes subir
`MIS_DATOS_PRIVADOS_NO_SUBIR.json` contiene tus datos reales. Guárdalo fuera de GitHub.

## Publicar
1. Sube únicamente los archivos de este ZIP al repositorio.
2. Luego puedes cambiar el repositorio a Public.
3. Settings → Pages → Deploy from a branch → `main` → `/(root)`.
4. Abre la URL de GitHub Pages en tu teléfono e instala la PWA.

## Cargar tus datos reales una sola vez
1. Lleva `MIS_DATOS_PRIVADOS_NO_SUBIR.json` a tu teléfono por un medio privado.
2. Abre el JSON, selecciona y copia todo el contenido.
3. En la app entra a **Datos**.
4. Pega el texto en el campo de respaldo/importación y pulsa **Aplicar/Cargar respaldo**.
5. La app guardará esos datos en `localStorage` de ese dispositivo. GitHub no recibe esos datos.

Importante: si borras los datos de la app/navegador o cambias de teléfono, necesitarás volver a importar el respaldo privado.
