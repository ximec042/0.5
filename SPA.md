
```mermaid
sequenceDiagram
Usuario->> Navegador: Abre la página notas SPA
Navegador->> Servidor: Envia una solicitud HTTP
Servidor->> Navegador: Obtiene el HTML
Servidor->> Navegador: Ejecuta el contenido JS
Servidor->>Navegador: no solicita una redirección, se permanece en la misma página y no envía más solicitudes HTTP.
