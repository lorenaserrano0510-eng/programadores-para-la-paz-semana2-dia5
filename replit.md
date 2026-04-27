# Programadores para la Paz – Semana 2 Día 5

## Overview
Static HTML/CSS site for an academic activity: a community participation form ("Formulario Participa") with accessibility checklist and responsible-verification reflection.

## Project Structure
- `semana2/` — site root (served as the web app)
  - `index.html` — form page
  - `styles.css` — page styles
  - `checklist-accesibilidad.txt` — accessibility checklist
  - `reflexion-verificacion.txt` — verification reflection
- `instrucciones/` — activity instructions
- `README.md` — assignment instructions

## Replit Setup
- **Runtime**: Python 3.11 (used only to serve static files in development)
- **Dev workflow**: `Start application` runs `python -m http.server 5000 --bind 0.0.0.0 --directory semana2` on port 5000.
- **Deployment**: Configured as `static` with `publicDir = semana2` (no build step).
