# Clase demostrativa UTEG — Modelado de procesos con BPMN 2.0

Sitio estático para GitHub Pages.

| Archivo | Para qué sirve |
| --- | --- |
| `index.html` | Página principal: visor de la presentación con pantalla completa (tecla F; Esc vuelve a la página), texto de cada lámina, miniaturas y accesos al laboratorio y a Mentimeter. |
| `recurso.html` | Recurso didáctico: diagrama BPMN interactivo del caso de crédito, recorrido guiado con audio, reto de práctica y acceso a Mentimeter con QR. |
| `slides/` | Láminas exportadas como imagen (las usa el visor). |
| `Clase_BPMN_UTEG.pptx` / `.pdf` | Presentación original en formato UTEG. |

## Publicar en GitHub Pages
1. Cree un repositorio público (por ejemplo `clase-bpmn-uteg`) y suba **todo el contenido de esta carpeta** a la raíz.
2. En el repositorio: *Settings → Pages → Build and deployment → Source: Deploy from a branch*, rama `main`, carpeta `/ (root)`. Guarde.
3. En 1–2 minutos el sitio queda en `https://SU-USUARIO.github.io/clase-bpmn-uteg/`.

## Conectar Mentimeter
Abra `index.html` y `recurso.html`, busque `const MENTI_URL = "";` y pegue el enlace de votación de su presentación de Mentimeter, por ejemplo `const MENTI_URL = "https://www.menti.com/al1b2c3d4e";`. Si lo deja vacío, el botón abre menti.com para escribir el código.

## Si modifica el PowerPoint
Exporte cada lámina como imagen JPG (PowerPoint: *Archivo → Exportar → Cambiar tipo de archivo → JPEG*) y renómbrelas `lamina-1.jpg`, `lamina-2.jpg`, … dentro de `slides/`. Si agrega o quita láminas, actualice la lista `LAMINAS` en `index.html`.
