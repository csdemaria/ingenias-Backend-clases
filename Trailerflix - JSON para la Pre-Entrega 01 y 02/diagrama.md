```mermaid
graph TD
  A[Inicio] --> B[Crear servidor Express]
  B --> C[Configurar puerto y middleware]
  C --> D[Leer archivo JSON]
  D --> E[Definir endpoint /catalogo]
  D --> F[Definir endpoint /titulo/:title]
  D --> G[Definir endpoint /categoria/:cat]
  D --> H[Definir endpoint /reparto/:act]
  D --> I[Definir endpoint /trailer/:id]
  E --> J[Retornar todo el contenido]
  F --> K[Aplicar filtro por título]
  G --> L[Aplicar filtro por categoría]
  H --> M[Aplicar filtro por reparto]
  I --> N[Retornar información del trailer]
  I --> O[Retornar mensaje si no hay trailer]