# Demo UI Generativa - Biometría

Este es un ejemplo autocontenido de UI Generativa que reacciona a expresiones faciales.

## 🔗 Live Demo
[Ver Proyecto Online](https://Raul-Marin.github.io/biometric-ui-demo/)

## Requisitos

- Un navegador moderno (Chrome, Firefox, Edge).
- Una webcam.
- **Importante**: Debido a restricciones de seguridad de los navegadores con la cámara, **no puedes abrir el archivo `index.html` directamente** (protocolo `file://`). Debes usar un servidor local.

## Cómo ejecutar

### Opción 1: Python (Mac/Linux/Windows)
Si tienes Python instalado, abre una terminal en esta carpeta y ejecuta:

```bash
python3 -m http.server
```

Luego abre tu navegador en `http://localhost:8000`.

### Opción 2: VS Code Live Server
Si usas VS Code, instala la extensión "Live Server", haz clic derecho en `index.html` y elige "Open with Live Server".

### Opción 3: Node.js (http-server)
Si tienes Node.js:

```bash
npx http-server .
```

## Uso

1. Al abrir la página, acepta el permiso de cámara.
2. Espera unos segundos a que carguen los modelos (verás el estado en pantalla).
3. Prueba las expresiones:
   - **Sonríe** 🙂 -> La tarjeta se vuelve verde.
   - **Ponte serio/neutral** 😐 -> La tarjeta se vuelve azul.
   - **Frunce el ceño/enfadado** 😟 -> La tarjeta se vuelve roja.
