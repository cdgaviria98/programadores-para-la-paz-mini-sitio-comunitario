# Programadores para la Paz – Mini-sitio comunitario

## Proyecto único de Semana 5

Este repositorio se trabaja desde la Clase 21 hasta la Clase 25.

## Propósito del proyecto

Construir progresivamente un mini-sitio comunitario que consuma una API propia para mostrar mensajes, calendario editorial y elementos de seguimiento comunitario.

El proyecto combina tecnología y comunicación responsable para apoyar la difusión de información clara, verificable y orientada a la participación ciudadana.

## Enfoque ciudadano

Este proyecto trabaja:

- Difusión responsable
- Calendario editorial
- Revisión de fuentes
- Consistencia comunicativa
- Moderación editorial básica
- Accesibilidad mínima
- Minimización de datos visibles
- Lenguaje responsable y no estigmatizante
- Transferencia tecnológica
- Documentación como transparencia

## Tecnologías utilizadas

- Node.js
- Express
- HTML
- CSS
- JavaScript
- JSON
- Git
- GitHub

## Estructura del proyecto

```text
.
├── server.js
├── package.json
├── data/
│   ├── mensajes.json
│   └── calendario-editorial.json
├── public/
│   ├── index.html
│   ├── app.js
│   └── styles.css
├── semana5/
└── instrucciones/
Instalación
Clonar el repositorio:
git clone URL_DEL_REPOSITORIO
Entrar al proyecto:
cd programadores-para-la-paz-mini-sitio-comunitario
Crear rama personal:
git checkout -b nombres_apellidos
Instalar dependencias:
npm install
Ejecutar el proyecto:
npm run sitio
Abrir en el navegador:
http://localhost:3000
Rutas de la API
GET /api/mensajes
Entrega los mensajes comunitarios.
GET /api/calendario
Entrega las piezas del calendario editorial.
GET /api/resumen
Entrega un resumen básico del proyecto.
POST /api/login
Ruta pedagógica de login.
Importante:
Esta ruta es solo para aprendizaje. No representa autenticación real ni debe usarse en producción.
Credenciales de demostración:
usuario: docente
clave: demo
Flujo de trabajo con Git
La rama main es actualizada por docentes.
Cada estudiante trabaja en su rama personal:
git checkout nombres_apellidos

Al iniciar cada clase:
git checkout main
git pull --ff-only origin main
git checkout nombres_apellidos
git merge main

Al terminar cada clase:
git status
git add .
git commit -m "Mensaje claro y descriptivo del avance realizado"
git push origin nombres_apellidos

Uso responsable de IA

La IA puede ayudar a mejorar redacción, organizar pasos y aclarar errores.


Uso Responsable de Inteligencia Artificial
La IA es un copiloto valioso para optimizar código, refinar redacciones técnicas y aclarar errores de sintaxis, bajo las siguientes pautas éticas:

Prohibido publicar: Nunca compartas en prompts de IA ni dejes escritos en el código: credenciales reales, tokens de acceso, datos personales o información sensible de la comunidad.

No automatizar contenido sin verificar: No utilices IA para publicar comunicados u opiniones comunitarias sin que hayan pasado por un riguroso proceso de validación humana de fuentes.

Revisión obligatoria: Toda sugerencia técnica o lógica proporcionada por una IA debe ser leída, comprendida y probada exhaustivamente por ti antes de ser aceptada.

Toda sugerencia de IA debe revisarse y probarse antes de aceptarse.
Evidencia

Único medio válido: Tu progreso se registrará y evaluará exclusivamente mediante el historial de confirmaciones (push) reflejado en tu rama personal dentro de GitHub.

Restricciones estrictas: No se aceptarán capturas de pantalla, archivos comprimidos ni enlaces externos enviados por Moodle. Si el avance no se encuentra respaldado en GitHub, no será contabilizado.