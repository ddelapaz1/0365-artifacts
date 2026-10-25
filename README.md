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
| Diagrama de radiació d’una antena isotròpica | https://ddelapaz1.github.io/0365-artifacts/diagrama-radiacio-antena-isotropica-ca.html |
| Diagrames de radiació d’antenes | https://ddelapaz1.github.io/0365-artifacts/diagrames-radiacio-antenes-ca.html |

El diplexor sigue las cotas de las vistas aportadas: carcasa de 199 × 199 × 48 mm, ancho total con soportes de 315 mm y altura montada de 66,25 mm. La posición y numeración de sus tres puertos siguen la vista superior. El corte muestra un interior didáctico, no una reproducción de la construcción interna del fabricante; los detalles exteriores no acotados también son aproximados.

El diagrama de radiación de la antena isotrópica es una esfera de radio proporcional a la ganancia lineal (G = 1, 0 dBi). Al pasar el cursor se lee la ganancia en cada dirección (θ, φ). No tiene despiece; sus parámetros propios son `?tall` (corte de un cuadrante: planos xz e yz), `?vectors` (vectores de Poynting) y `?dipol` (comparación con un dipolo λ/2 a la misma escala).

La aplicación de diagramas de radiación incluye antena isotrópica, dipolo λ/2, Yagi-Uda (3, 4, 6, 9, 12 y 15 elementos), panel sectorial 90° × 7° (17 dBi), parabólica de satélite (80 cm, Ku, 38 dBi) y de radioenlace tipo MINI-LINK (0,6 m, 23 GHz, 40 dBi), antena bilobular (bidireccional, ≈ 12 dBi por lóbulo) y bocina piramidal (20 dBi). La directividad, el ancho de haz a −3 dB y la relación delante/detrás se calculan numéricamente a partir de cada diagrama. Escala radial seleccionable (dBi absolutos, dB relativos o lineal). Parámetros propios: `?antena=` (`isotropica`, `dipol`, `yagi-3`, `yagi-4`, `yagi-6`, `yagi-9`, `yagi-12`, `yagi-15`, `sectorial`, `parabolica-satellit`, `parabolica-minilink`, `bilobular`, `botzina`), `?escala=` (`dbi`, `db`, `lin`), `?antena-visible` (diagrama translúcido con la antena dentro), `?tall` y `?sense-talls` (oculta los cortes 2D). Ejemplo: `?antena=yagi-9&escala=db`.

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
