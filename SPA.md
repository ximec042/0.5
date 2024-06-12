
```mermaid
sequenceDiagram
Usuario->> Navegador: Abre la página notas SPA
Navegador->> Servidor: Obtiene el HTML
Servidor->> Navegador: Ejecuta el contenido JS
