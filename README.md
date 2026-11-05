# Legacy-Pay — Rediseño topológico con maniobra inversa de Conway

Presentación interactiva sobre el rediseño de Legacy-Pay con Team Topologies: equipos stream-aligned por flujo de valor, Platform Team desde los 10 SysAdmins y un Complicated-Subsystem Team para el núcleo transaccional, con los modos de interacción Colaboración, Facilitación y X-as-a-Service. Elaborada para Arquitectura de Plataformas (ARTI-4219), Universidad de los Andes.

[Ver la presentación interactiva](https://rubiod1.github.io/legacy-pay/)

## Archivo de entrega y revisión local

`index.html` contiene el documento completo, con los cinco autores, estilos, scripts y diagrama SVG integrados. Es el archivo único de entrega. Las fuentes web tienen alternativas locales, por lo que el contenido también se puede consultar sin conexión. `legacy-pay.html` es únicamente un acceso mediante iframe y necesita `index.html` a su lado.

Para revisar la rama descargada, abre `index.html` en un navegador o ejecuta `python3 -m http.server 8765` desde el repositorio y visita <http://localhost:8765/>. El enlace público de arriba muestra la versión publicada en GitHub Pages.

La vista inicial muestra una síntesis por bloque. Los apartados desplegables conservan el diagnóstico, los mandatos, los contratos y el análisis de transición. En «Contenido», el botón «Mostrar análisis completo» abre todos los apartados. Los enlaces directos a una sección detallada abren su apartado automáticamente. El diseño aprovecha el ancho disponible hasta 1800 píxeles y se adapta a pantallas pequeñas.

## Correspondencia con la rúbrica

| Criterio | Evidencia en el documento |
| --- | --- |
| Diagnóstico de Conway y cuellos de botella | Bloque I: tres traspasos, consecuencias sobre el flujo y cadena causal hacia datos y liberaciones acoplados. Se distinguen hechos e inferencias. |
| Rediseño topológico y maniobra inversa | Bloque II: reparto de las 150 personas, mandatos, propiedad de servicios y datos, autoservicio y carga cognitiva. |
| Interacciones y evolución | Bloque III: piloto Discover-to-Establish, contratos R1–R10, criterios de salida y transferencia temporal de capacidades. |
| Estructura y rigor conceptual | Resumen ejecutivo, diagrama vinculado con la matriz, hoja de ruta, métricas, riesgos, supuestos y referencias. |

El diagrama editable está en `diagramas/tobe-legacy-pay.drawio`. Sus relaciones R1–R10 corresponden al SVG incorporado en `index.html` y a la matriz 3.3; cualquier cambio debe conservar esa correspondencia.
