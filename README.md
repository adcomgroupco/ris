# RIS

Sitio de consulta de reportes, propuestas y plan de acción de Meta Ads para RIS.

## Contenido

- `index.html`: página principal.
- `reporte-semanal.html`: reporte semanal de Meta con filtro de fechas, frente a las metas del flow.
- `implementacion-google-search-2026-11-06.html`: implementación de la campaña de Google Search de solicitud de crédito (activada el 06/11/2026): ficha técnica, landing, anuncios, palabras clave, negativas y recursos.
- `ruta-750-desembolsos.html`: ruta a 750 desembolsos de noviembre 2026: cierre de octubre, cuello de botella en identidad, escenarios, Google y remarketing, compromisos ADCOM y RIS.
- `plan-de-choque.html`: plan de choque de octubre 2026: rendimientos decrecientes, prioridades con RIS y acciones en Meta.
- `funnel-desembolsos.html`: funnel de desembolsos octubre vs septiembre (días 1–13) y plan conjunto con RIS.
- `propuesta-medios-adicionales.html`: propuesta de medios adicionales (Google Search y TikTok): objetivo de CPA, flow de prueba y estado actual. La presentación original está en `propuesta-medios-presentacion.html`.
- `caso-exito-costo-desembolso-2026.html`: caso de éxito 2026, costo por desembolso con corte a noviembre y nuevos medios.
- `cierres/`: PDFs de cierre mensual del dashboard de Meta (julio, agosto y octubre de 2026).
- `flow-general.html`: propuesta del flow general de medios, octubre 2026 a junio 2027.
- `ris-meta-credit-action-plan.html`: informe y plan de acción.
- `data/ris_meta_daily.js`: datos diarios de Meta que lee el reporte semanal.
- `assets/`: recursos visuales y estilos del sitio.

## Uso local

Abre `index.html` en un navegador para acceder al informe.

## Convención de nombres

Los archivos de contenido usan `kebab-case`. Los documentos estándar de GitHub conservan sus nombres convencionales, por ejemplo `README.md`.

## Actualizar el reporte semanal

Los datos se generan desde el repositorio Meta-Ads-CLI:

```
.venv/bin/python scripts/clients/ris/build_ris_weekly.py --out ../GitHub/ris/data/ris_meta_daily.js
```
