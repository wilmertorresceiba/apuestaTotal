# Entregables para Apuesta Total

Sitio estático (sin servidor ni compilación) con tres entregas de Ceiba Software para Apuesta Total.

| Carpeta | Contenido |
|---|---|
| `gobierno-ia/` | Guías de gobierno de IA: proceso de implementación de punta a punta y diagramas de los 4 dominios |
| `ciclo-comercial-agentico/` | Entrega técnica de arquitectura del Ciclo Comercial Agéntico |
| `whatsapp-teleservicios/` | Entrega técnica de arquitectura del Agente IA Supervisor de Teleservicios (WhatsApp) |

Cada carpeta tiene un `index.html` autocontenido (los diagramas y las imágenes van incrustados). La página `index.html` de la raíz enlaza a las tres.

## Ver en local

Abra `index.html` con el navegador. No requiere instalar nada.

## Publicar en GitHub Pages

1. Cree un repositorio **privado** y suba el contenido de esta carpeta a la raíz.
2. En *Settings > Pages*, elija la rama (`main`) y la carpeta `/ (root)`.
3. El sitio queda en `https://<usuario>.github.io/<repositorio>/`.

Aviso: los documentos son confidenciales. En un repositorio público, cualquier persona puede verlos. GitHub Pages desde un repositorio privado solo está disponible en planes de pago (por ejemplo, GitHub Enterprise Cloud con acceso restringido). Las páginas llevan `noindex` para que los buscadores no las indexen, pero eso no impide el acceso por enlace.

El archivo `.nojekyll` evita que GitHub procese los archivos con Jekyll.
