# Cartera Bladi — PWA lista para GitHub Pages

Esta carpeta ya está preparada para instalar **Cartera Bladi** en el teléfono como una app independiente del navegador.

## 1. Subir a GitHub

1. Crea un repositorio nuevo, por ejemplo `cartera-bladi`.
2. Sube **todos los archivos de esta carpeta a la raíz del repositorio**.
3. En GitHub abre **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Selecciona la rama **main** y la carpeta **/(root)**, luego **Save**.
6. GitHub mostrará la URL de Pages cuando termine el despliegue.

## 2. Instalar en el celular

### iPhone
1. Abre la URL de GitHub Pages en **Safari** una sola vez.
2. Pulsa **Compartir**.
3. Selecciona **Añadir a pantalla de inicio**.
4. Abre **Cartera Bladi** desde su nuevo icono.

### Android
1. Abre la URL de GitHub Pages una sola vez en Chrome.
2. Menú **⋮ → Instalar aplicación** o **Agregar a pantalla principal**.
3. Luego ábrela desde el icono **Cartera Bladi**. Se ejecutará en modo `standalone`, sin la barra normal de Chrome.

## Qué se cambió

- Se fuerza la interfaz limpia de celular (`BareShell`).
- Se eliminan de la vista instalada el panel explicativo y el marco/simulador de teléfono.
- Se agregó `manifest.webmanifest`.
- Se agregó Service Worker para instalación y funcionamiento offline después de la primera carga.
- Se agregaron iconos 192, 512 y Apple Touch Icon.
- Los datos continúan guardándose en `localStorage`, igual que en tu versión original.

## Importante sobre tus datos

La aplicación guarda los cambios hechos desde el teléfono **en ese dispositivo/navegador**. Usa la opción de backup de la app antes de borrar datos del navegador, reinstalar o cambiar de teléfono.

Además, si publicas el repositorio y GitHub Pages de forma pública, el HTML y cualquier dato inicial incluido dentro de él pueden ser accesibles para otras personas que tengan la URL o encuentren el repositorio. Para información financiera personal, considera esto antes de hacerlo público.
