# 01b · Estado del arte (SOTA) de mi proyecto

> **Plantilla.** En **H1 (26-nov-2026)** entregas una **versión breve** (2-3 páginas: apartados **1, 2 y 5**), junto al `01-analisis.md`. Los apartados 3, 4, 6, 7 y 8 se completan en **H2 (21-ene-2027)** hasta las **4-6 páginas** del documento final. Aquí estudias qué soluciones, **modelos de negocio** y **herramientas** existen ya para el problema que has elegido, y justificas tus decisiones con ello. Cada apartado indica el criterio de evaluación (CE) que alimenta. Borra los bloques «Guía» al rellenar.

## 1. Problema y preguntas de búsqueda (CE 1c)

**Problema:** No existe un punto único donde centralizar y seguir de forma activa las fuentes de información sobre el desarrollo de un videojuego o sobre qué está desarrollando un desarrollador independiente, por lo que resulta difícil enterarse a tiempo real de su evolución o del inicio de un nuevo proyecto.

| # | Pregunta | Dónde busqué | Fecha |
|---|---|---|---|
| P1 | ¿Qué soluciones existen actualmente para centralizar fuentes sobre videojuegos en desarrollo? | Buscadores, repositorios GitHub y plataformas de feeds (Steam, itch.io, IndieDB) | 17-nov-2026 |
| P2 | ¿Cómo monetizan las plataformas y servicios de seguimiento de videojuegos? | Documentación oficial (Steamworks), información sectorial (IndieDB) | 17-nov-2026 |
| P3 | ¿Qué modelos de fuente y notificación usan las soluciones existentes para informar sobre desarrollo de videojuegos? | itch.io updates, Steamworks, IndieDB | 17-nov-2026 |
| P4 | ¿Existen proyectos de código abierto que ya intenten resolver este problema? | GitHub (gamedev-exodus), itch.io | 17-nov-2026 |
| P5 | ¿Existen alternativas no digitales (hojas de cálculo, listas manuales) para este seguimiento? | Reddit / r/gamedev | 17-nov-2026 |

## 2. Soluciones existentes (CE 1a, 1c, 2a)

| Solución | Para quién | Qué hace | Modelo de precio | Enlace y fecha de acceso | Estado (`leído` / `sin leer`) |
|---|---|---|---|---|---|
| Steam News | Videojuegos lanzados en Steam | Anuncios de devs, RSS por juego | Gratuito (una vez publicado el juego en Steam) | https://store.steampowered.com/news (15/11/2026) | Leído |
| IndieDB | Estudios independientes | Recopilación de recursos y proyectos de y para desarrolladores (similar a un foro) | Gratuito | https://www.indiedb.com (15/11/2026) | Leído |
| itch.io | Desarrolladores independientes | Publicación de todo relacionado con videojuegos y desarrollo independiente (assets, juegos, noticias, etc.) | Gratuito | https://itch.io (15/11/2026) | Leído |
| X | Usuarios | Multiusos. Algunos desarrolladores lo usan para publicar noticias sobre sus proyectos | Gratuito | https://x.com (15/11/2026) | Leído |
| Reddit | Desarrolladores y usuarios | Foro multiusos que algunos usuarios y desarrolladores utilizan para compartir publicaciones sobre sus videojuegos | Gratuito | https://www.reddit.com (15/11/2026) | Leído |
| Discord | Usuarios | Comunicación directa. Algunos desarrolladores publican actualizaciones sobre sus proyectos en comunidades propias. | Gratuito | https://discord.com (15/11/2026) | Leído |

## 3. Modelos de negocio (CE 1d, 1e)

*Qué **patrones** se repiten en las soluciones del apartado 2 (suscripción, *freemium*, comisión por operación, licencia, publicidad, servicio gratuito o público) y por qué. Describe con un **Business Model Canvas** (opcional; el profesor te da el material) **2-3 casos**. Termina con el modelo que seguiría **tu** proyecto, o qué ahorra o mejora si no es un negocio.*

| Patrón | Soluciones que lo usan | Ventaja | Riesgo |
|---|---|---|---|
| [RELLENAR] | | | |

## 4. Herramientas y tecnologías (CE 2a, 2b)

*Para cada decisión técnica importante (lenguaje y *framework*, base de datos, despliegue, autenticación…), compara **2-3 opciones con los mismos criterios**. Marca la que eliges.*

| Decisión | Opción | Madurez | Licencia | Coste | Curva de aprendizaje | Encaje con el ciclo | Elegida |
|---|---|---|---|---|---|---|---|
| [RELLENAR: p. ej. base de datos] | | | | | | | |

*Cada decisión importante se convierte en una decisión registrada en [`decisiones/`](decisiones/0000-plantilla.md).*

## 5. Hueco y diferenciación (CE 1e)

Las soluciones estudiadas abordan el problema con parcialidad: Steam centraliza anuncios de sus juegos y ofrece RSS; IndieDB e itch.io ofrecen perfiles y devlogs a desarrolladores indie; Reddit, Twitter/X y Discord suministran contenido, aunque de forma dispersa. Ninguna de ellas ofrece, un punto único donde un usuario pueda seguir y gestionar de forma personalizada un conjunto de fuentes sobre los juegos o desarrolladores que le interesan, ni siquiera para desarrolladores que publican en canales no centralizados (X/Twitter, newsletters, blogs propios).

GameFeeds aporta esa capa: centralizar fuentes heterogéneas sobre desarrollo de videojuegos, con seguimiento por intereses del usuario y gestión de fuentes por juego y desarrollador. Para usuarios con intereses muy específicos, otras soluciones pueden ser ya suficientemente buenas.


## 6. Decisiones derivadas (CE 1e, 1f, 2b)

*Qué consecuencias tiene este estudio en tu proyecto.*

- **Tipo de proyecto elegido** (enlaza con el apartado 3 de [`01-analisis.md`](01-analisis.md)): [RELLENAR]
- **Requisitos que salen del estudio** (con su ID del apartado 4 de `01-analisis.md`): [RELLENAR]
- **Decisiones técnicas** (enlace a cada archivo de `decisiones/`): [RELLENAR]

## 7. Fuentes y calidad (CE 2a)

*Al menos **2 fuentes independientes** (no dos páginas de la misma empresa). Datos oficiales o primarios antes que blogs.*

| # | Fuente (enlace) | Tipo | Fecha de acceso | Fiabilidad (alta / media / baja) y por qué |
|---|---|---|---|---|
| F1 | [RELLENAR] | | | |

## 8. Límites

*Qué **no pudiste comprobar** y qué datos son estimaciones. Una lista corta y honesta es mejor que fingir certeza.*

- [RELLENAR]

---

## Criterios de evaluación que alimenta este documento (texto literal)

- **1a)** Se han clasificado las empresas del sector por sus características organizativas y el tipo de producto o servicio que ofrecen.
- **1c)** Se han identificado las necesidades más demandadas a las empresas.
- **1d)** Se han valorado las oportunidades de negocio previsibles en el sector.
- **1e)** Se ha identificado el tipo de proyecto requerido para dar respuesta a las demandas previstas.
- **1f)** Se han determinado las características específicas requeridas al proyecto.
- **2a)** Se ha recopilado información relativa a los aspectos que van a ser tratados en el proyecto.
- **2b)** Se ha realizado el estudio de viabilidad técnica del mismo.

> El SOTA **no añade criterios de evaluación**: reúne en un solo sitio lo que 1a-1f y 2a-2b ya piden. La evaluación sigue las listas de cotejo de H1 y H2.
