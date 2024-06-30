# Extracción de Publicaciones de Facebook

Este script utiliza Selenium para extraer información de publicaciones en la página de Facebook de El Corte Inglés.

## Descripción

El script realiza las siguientes tareas:

1. **Configuración del Navegador**: Inicia un navegador Chrome utilizando un agente de usuario específico.
2. **Acceso a la Página**: Navega a la página de Facebook de El Corte Inglés.
3. **Gestión de Diálogos**: Cierra el diálogo de cookies y el diálogo de inicio de sesión, si aparecen.
4. **Scrolling Suavizado**: Realiza un scrolling suave en la página para cargar más publicaciones.
5. **Extracción de Datos**: Obtiene información sobre las publicaciones, incluyendo:
   - Texto de la publicación
   - URL de la publicación
   - Número de reacciones
   - Número de comentarios
   - Número de veces compartido
6. **Límite de Extracción**: Continúa extrayendo hasta que se alcancen al menos 10 publicaciones o un máximo de 50 scrolls.

## Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tuusuario/FaceBook-extractor-comments.git
   cd facebook-scraper
