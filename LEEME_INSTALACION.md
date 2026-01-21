# Cómo instalar la App Intrachat

Sigue estos pasos para instalar Intrachat en tu dispositivo.

## Requisitos Previos

Necesitas un servidor web simple para ver la aplicación antes de instalarla. Si ya tienes uno, salta al paso **Instalación**.

Si no tienes uno, una forma fácil en Windows es usar Python (que suele venir instalado) o una extensión de VS Code como "Live Server".
- **Opción Python**: Abre una terminal en la carpeta `Intrachat` y escribe:
  ```bash
  python -m http.server
  ```
- **Opción VS Code**: Haz clic derecho en `index.html` y selecciona "Open with Live Server".

## Instalación

1.  **Abrir en el Navegador**:
    Ve a la dirección local donde se está ejecutando la app (por ejemplo `http://localhost:8000` o `http://127.0.0.1:5500`).

2.  **Instalar en PC (Chrome/Edge)**:
    - Mira a la derecha de la barra de direcciones (donde escribes la URL).
    - Verás un icono de instalación (un monitor con una flecha hacia abajo).
    - Haz clic en él y selecciona **"Instalar Intrachat"**.
    - La app se abrirá en su propia ventana.

3.  **Instalar en Móvil (Android/Chrome)**:
    - Abre la URL en Chrome.
    - Toca el menú de tres puntos (arriba a la derecha).
    - Selecciona **"Instalar aplicación"** o **"Añadir a pantalla de inicio"**.

¡Listo! Ahora tendrás un icono de "Intrachat" en tu escritorio o menú de aplicaciones que abrirá directamente el chat.

## Opción: Publicar en GitHub Pages (Gratis)

Si quieres instalarlo en tu móvil sin conectar cables ni usar servidores locales, usa GitHub:

1.  Crea un repositorio en GitHub y sube todos los archivos de esta carpeta.
2.  Ve a la pestaña **Settings** (Configuración) del repositorio.
3.  En el menú lateral, busca **Pages**.
4.  En "Build and deployment" > "Branch", selecciona **main** (o master) y dale a **Save**.
5.  Espera unos segundos y GitHub te dará una URL (ej: `https://tu-usuario.github.io/intrachat`).
6.  Abre esa URL en tu móvil e instálala como se indica arriba.

