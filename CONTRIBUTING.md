# Cómo colaborar

¡Gracias por querer mejorar la guía! Cualquier aportación ayuda: una estafa nueva, un enlace oficial mejor, un dato que ha cambiado, una frase que no se entiende o un problema de accesibilidad.

## Sin saber programar

Abre un [issue](https://github.com/jamm87/antifraude/issues/new) y cuéntanos:

- Qué hay que cambiar y en qué paso.
- La **fuente oficial** que lo respalda (BOE, Banco de España, INCIBE, AEPD, la web del organismo…).

## Editando el texto (lo más fácil)

Todo el contenido de la guía está en Markdown en [`guia.md`](guia.md). Puedes editarlo desde la propia web de GitHub (icono del lápiz): GitHub crea el fork y el pull request por ti.

1. Abre [`guia.md`](guia.md) y pulsa el lápiz.
2. Haz el cambio y, en la descripción, enlaza la fuente oficial.
3. Pulsa **Propose changes** y luego **Create pull request**.

Quien mantiene el proyecto trasladará el cambio a la web (`index.html`) y, si aplica, a la hoja imprimible.

## Cambios en la web

1. Haz un fork y edita `index.html` (guía) o `imprimir.html` (hoja para imprimir). Los estilos están en `styles.css`.
2. Si cambias el texto, actualiza también `guia.md` para que ambos digan lo mismo.
3. Prueba en local con `python3 -m http.server` y comprueba la vista de impresión del navegador (A4).
4. Abre el pull request explicando el cambio y enlazando la fuente.

## Criterios

- **Enlaces solo a fuentes oficiales** o de los propios servicios. Nada de enlaces de afiliados ni servicios de pago.
- **Lenguaje claro**, pensado para cualquier persona, también para nuestros mayores.
- **Accesible**: buen contraste, textos de enlace descriptivos, que funcione sin JavaScript y con lector de pantalla.
- **Privacidad**: la web no debe recoger ningún dato. Nada de cookies, analítica, formularios ni recursos de terceros.
- Si un cambio afecta a la guía, revisa si también hay que tocar la hoja imprimible, y que siga ocupando 4 páginas A4 (la última, de notas).

Nunca publiques en un issue datos personales, capturas con números de cuenta ni detalles de una estafa que te afecte directamente.
