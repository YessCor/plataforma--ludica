## Estado actual
Repositorio publicado en GitHub con el CI en verde.
Página de inicio, /salud y /docs funcionando en https://plataforma-ludica-
abcd.onrender.com.
Hoy se agregó GET /api/version. Devuelve {"version": proyecto.VERSION}; su prueba verifica el código 200 y que la versión coincida con la constante del proyecto. Las 7 pruebas pasan.
## Decisiones
| Fecha | Decisión | Motivo |
| --- | --- | --- |
| AAAA-MM-DD | Usar la plantilla del curso con FastAPI | Es el stack definido para el proyecto |
| 2026-11-10 | Exponer la versión mediante GET /api/version y tomarla de proyecto.VERSION | Mantener una única fuente de versión y comprobar la respuesta con una prueba automatizada |
## Siguiente paso
Definir la siguiente funcionalidad prioritaria del MVP y sus criterios de aceptación antes de implementarla.