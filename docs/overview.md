# PlusPagos — Overview

Este sitio muestra la documentación de las APIs usando ReDoc.

## Cómo navegar
- En la barra izquierda elegí **Pagos API** o **Cliente API** para ver la referencia OpenAPI.
- Este archivo es Markdown simple; podés agregar arquitectura, seguridad, quickstart, etc.

## Quickstart
```bash
curl -ik "https://localhost:8243/pluspagosapi/v1.44.0/health" \
  -H "Authorization: Bearer <API_KEY>" \
  -H "correlationId: <uuid>"
