# MAES26 - Control y Planeación (Export)

Este repositorio contiene la versión exportada del archivo HTML que proporcionaste.
Está pensado para **subir directamente a GitHub** como un repo estático o para
abrir `index.html` localmente en el navegador.

## Contenido
- `index.html` — Archivo principal (React + Tailwind + Firebase en CDNs).  
  El proyecto está como un único archivo HTML que monta la app usando React UMD + Babel (inline).
- `.gitignore` — Recomendado para repositorios.
- `NOTICE.txt` — Información breve sobre credenciales sensibles encontradas.

## Cómo usar
Opciones rápidas:
1. **Abrir localmente**: abrir `index.html` en tu navegador (funciona, pero algunas APIs de Firebase requieren https/origen).
2. **Servir con un servidor estático (recomendado)**:
   - `npx serve` en la carpeta del repo (requiere Node.js).
   - O usar GitHub Pages (subir repo y activar Pages).
3. **Convertir a proyecto React moderno**: si quieres, puedo convertir esto a un proyecto con Vite + React y estructura de componentes (dímelo).

## Advertencias y pasos a seguir
- El archivo contiene una configuración de Firebase **embebida** (`apiKey`, `projectId`, etc). 
  Estos valores están en el HTML; si el repo será público, **elimina o mueve la configuración** a variables de entorno.
- Si vas a poner el repo en GitHub público y no quieres exponer el proyecto Firebase, cámbialo primero.
- Recomiendo mover el JavaScript a archivos `.jsx` y crear un build con Vite para mantenimiento a futuro.

## Próximo paso
Si quieres que:
- **Organice y convierta** a Vite + React (componentes, Tailwind config, .env) — lo hago.
- **Suba el repo a tu GitHub** (necesito un token con permiso de repo, si quieres hacerlo por mí).
- **Refactorice** el código en componentes y carpetas — lo hago y te doy instrucciones para desplegar.

Dime qué prefieres y lo continúo.
