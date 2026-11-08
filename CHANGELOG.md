# Registro de Uso de IA

## Plantilla

* **Fecha:** [AAAA-MM-DD]
* **Modelo / Herramienta:** [Nombre de la herramienta o modelo utilizado]
* **Motivo del uso:** [Qué necesidad concreta se busca resolver con la consulta]
* **Prompt:**
```text
"[Texto exacto de la consulta o instrucción realizada]"
```
* **Adjuntos:** [Opcional: archivos, capturas o enlaces enviados]
* **Qué devolvió:** [Resumen de la propuesta generada]
* **Qué conservé:** [Elementos aceptados y motivo]
* **Qué cambié o descarté:** [Modificaciones aplicadas o elementos rechazados y motivo]

---

## Órbita 1 — Investigación y Wireframes

### Primer uso
* **Fecha:** 2026-10-18
* **Modelo / Herramienta:** Gemini 3.8 Flash - Razonamiento Medio
* **Motivo del uso:** Generar una plantilla correcta y de calidad para registrar el uso de IA.
* **Prompt:**
```text
"Crea una plantilla para un changelog.md donde registrare uso de ia, con modelo, prompt y motivo del uso"
```
* **Qué devolvió:** Una estructura en Markdown con los tres campos solicitados (`Modelo`, `Motivo del uso` y `Prompt`).
* **Qué conservé:** La estructura base de los tres apartados para arrancar el historial del repositorio.
* **Qué cambié o descarté:** En la Órbita 2 se amplió la plantilla para añadir `Fecha`, `Qué devolvió`, `Qué conservé` y `Qué cambié o descarté`, según pide la rúbrica.

### Segundo uso
* **Fecha:** 2026-10-18
* **Modelo / Herramienta:** Gemini 3.8 Flash - Razonamiento Medio
* **Motivo del uso:** Cambiar el formato de las respuestas de la encuesta de CSV a XLSX para mejor calidad.
* **Prompt:**
```text
"Añade formato a este documento para que todo pueda verse correctamente."
```
* **Adjuntos:** <img width="1919" height="969" alt="Screenshot 2026-10-18 14 04 15" src="https://github.com/user-attachments/assets/300b9429-5f25-4554-8e8e-bcb2ec3c0943" />

* **Qué devolvió:** Tabla formateada en XLSX.
* **Qué conservé:** Los datos originales.
* **Qué cambié o descarté:** Nada.

---

## Órbita 2 — Sistema visual

### 2026-11-08 · Exploración inicial de paleta de color (Coolors)
* **Modelo / Herramienta:** Coolors
* **Motivo del uso:** Buscar una paleta base en tonos azules y neutros para la aplicación de seguimiento de logros y runs.
* **Prompt / Acción:** Búsqueda y filtrado de paletas hasta encontrar una gama fría/sobria orientada a lectura en PC y con buen margen de contraste entre tonos.
* **Qué devolvió:** Cinco códigos hexadecimales: `#2F6690` (Baltic Blue), `#3A7CA5` (Steel Blue), `#D9DCD6` (Dust Grey), `#16425B` (Yale Blue) y `#81C3D7` (Sky Blue Light).
* **Qué conservé:** Los cinco tonos como paleta candidata inicial para evaluar en el sistema de color.
* **Qué cambié o descarté:** Por ahora nada.

### 2026-11-08 · Revisión de rúbrica, estructura de Figma y herramientas de contraste
* **Modelo / Herramienta:** Gemini 3.8 Flash - Razonamiento Alto
* **Motivo del uso:** Identificar los elementos existentes en los wireframes, localizar herramientas recomendadas para comprobar el contraste de color y auditar el estado del archivo frente a la rúbrica de la Órbita 2.
* **Prompt:**
```text
1. "analiza el video para saber todo lo que hay y como se llama en la aplicacion. Te he adjuntado la paleta que quiero usar, el profesor nos recomendo una pagina para ver el contraste como de correcto era segun el color pero no me acuerdo, sabes cual es?"
2. "Analiza todo con profundidad, es importante." (junto con el BRIEF.md, capturas de FigJam y la rúbrica completa de Órbita 2)
```
* **Adjuntos:** Vídeos de Figma (`Wireframes - Desktop` y `Wireframes - Mobile`), captura de Coolors, `BRIEF.md`, capturas de FigJam (`Personas`, `MVP`, `SiteMap` y `Diagrama de flujo`) y texto completo de la rúbrica de Órbita 2.
* **Qué devolvió:**
  - Las opciones recomendadas para comprobar contraste (WebAIM Contrast Checker, Coolors Contrast Checker y el plugin Stark en Figma).
  - Un análisis preliminar del comportamiento en contraste de los 5 colores de Coolors.
  - La lista de ajustes respecto a la rúbrica (reorganizar el archivo de Figma en 5 páginas, priorizar Escritorio por el perfil de Abraham y Alejandro, ampliar objetivos táctiles en móvil a 44 x 44 px y añadir los campos obligatorios en el `CHANGELOG.md`).
* **Qué conservé:** La organización del archivo en 5 páginas (`PORTADA`, `GUIA DE ESTILOS`, `COMPONENTES`, `WIREFRAMES`, `MOCKUPS`), la agrupación de los wireframes originales en `WIREFRAMES ORBITA 1` y la actualización de la plantilla de `CHANGELOG.md`.
* **Qué cambié o descarté:** En `PORTADA` eliminé los bloques inferiores de estado de la plantilla para simplificarla; la elección definitiva de colores, tipografía y correcciones de jerarquía se aplazan a los Pasos 2, 3 y 4. 
