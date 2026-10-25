# 0365-artifacts

Modelos 3D interactivos (HTML + Three.js) para incrustar en los apuntes.
Publicados con GitHub Pages: https://ddelapaz1.github.io/0365-artifacts/

## Modelos

Los modelos están en catalán.

| Modelo | Enlace para incrustar |
|---|---|
| Descarregador RF HUBER+SUHNER 3409.41.0081 | https://ddelapaz1.github.io/0365-artifacts/descarregador-rf-huber-suhner-3409.41.0081-ca.html |
| Acoblador híbrid 3 dB KATHREIN 793554 | https://ddelapaz1.github.io/0365-artifacts/acoblador-hibrid-kathrein-793554-ca.html |
| Diplexor KATHREIN 78210620 | https://ddelapaz1.github.io/0365-artifacts/diplexor-kathrein-78210620-ca.html |

El diplexor sigue las cotas de las vistas aportadas: carcasa de 199 × 199 × 48 mm, ancho total con soportes de 315 mm y altura montada de 66,25 mm. La posición y numeración de sus tres puertos siguen la vista superior. El corte muestra un interior didáctico, no una reproducción de la construcción interna del fabricante; los detalles exteriores no acotados también son aproximados.

## Cómo incrustar en Notion

1. En la página de Notion escribe `/embed` (o pega el enlace y elige **Crear incrustación**).
2. Usa el enlace de la tabla.

Vistas iniciales opcionales añadiendo parámetros al final del enlace:

- `?especejament` — abre en despiece
- `?tall` — abre en corte
- `?etiquetes` — abre con las etiquetas visibles (por defecto están ocultas)
- `?especejament&tall` — ambos

Los parámetros se pueden combinar con `&`, por ejemplo `?especejament&etiquetes`.

Cada `git push` a `main` vuelve a publicar los modelos (tarda uno o dos minutos).
