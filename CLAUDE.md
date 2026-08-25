# balas-countdown

## Qué es

Página estática de una sola pieza, humorística e interna: **"Operación Promesas"**, un
marcador con estética militar que seguía 4 promesas ("objetivos") de Manuel Lustres
(contexto MEGA). Nació como cuenta atrás (de ahí el nombre del repo) y hoy está en su
estado final de celebración: los 4 objetivos figuran como "asegurados" (misión cumplida,
confeti incluido).

## Stack

- HTML + CSS + JavaScript vanilla, todo dentro de `index.html`. Sin framework, sin
  build, sin `package.json`, sin dependencias.
- Google Fonts (Inter + Share Tech Mono) como único recurso externo.

## Estructura

- `index.html` — toda la página: estilos, contenido (hero, 4 tarjetas de objetivos,
  debrief, barra de progreso) y un script pequeño (barra al 100% + confeti).
- `img/` — `Manu.jpg` (avatar del hero) y `og-image.png` (imagen para redes sociales).
- `.gitignore` — solo ignora `.vercel`.
- `.claude/skills/ui-ux-pro-max/` — skill de diseño usada durante su creación; no forma
  parte de la web publicada.

## Comandos

No hay scripts ni proceso de build. Para verla en local basta abrir `index.html` en un
navegador (o servirla con cualquier servidor estático).

## Despliegue

Publicada en Vercel: los meta tags apuntan a `https://promesas-mega.vercel.app/`.
El despliegue va ligado al push a GitHub (`viiteer2708/balas-countdown`), como el resto
de repos de Victor: un push a `main` actualiza la web en producción.

## Avisos

- Es una broma interna terminada, no un proyecto en desarrollo: antes de cambiar el
  contenido (estado de las promesas, textos), confirmar con Victor.
- Si se edita el título/descripción, recordar que los meta OG/Twitter están duplicados
  en la cabecera de `index.html` y hay que cambiarlos en los dos sitios.
