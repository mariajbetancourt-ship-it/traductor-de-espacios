# Traductor de espacios

Una página web que **escucha el sonido de un lugar con el micrófono y lo convierte en música de orquesta**, en vivo.

No reproduce los sonidos del lugar: los interpreta. Lo que se oye es música compuesta a partir de cómo suena el espacio.

> Proyecto universitario · Autoría: **[TU NOMBRE]** · **[Universidad / curso]**

## Cómo usarlo

1. Ábrelo en el navegador (Chrome o Edge funcionan bien) y presiona **empezar**.
2. Acepta el permiso del micrófono.
3. **Usa audífonos.** Así el micrófono no escucha a la propia orquesta.
4. Espera a que abajo diga que la orquesta está lista (los instrumentos se descargan la primera vez).
5. Haz sonidos, o simplemente deja que el lugar suene. Las notas pequeñas de abajo van explicando qué hace.
6. El botón **guardar canción** descarga solo la música generada, sin silencios.

## Qué hace

- **Escucha.** Aprende el ruido normal del lugar. Si hay silencio, solo queda una nota sostenida de fondo, la base.
- **Entiende.** Mide cada sonido (qué tan brillante es, si es limpio o ruidoso, cuánto dura). **No reconoce objetos ni acciones**: solo mide características del sonido.
- **Recuerda.** Guarda los tipos de sonido que oye, cuáles se repiten, cada cuánto y cuál suele seguir a cuál. Lo que se repite pesa más y lo que suena una sola vez se olvida.
- **Interpreta.** Calcula la energía, la regularidad, los cambios bruscos y la tendencia (si la actividad sube o baja).
- **Compone.** La tonalidad, el tempo y los instrumentos salen del carácter del lugar. La música se organiza en frases de 4 compases, con acordes que van de la tensión al reposo, motivos que nacen de lo que se repite y se transforman, y capas que entran y salen según la actividad.
- **Se ve.** La pantalla muestra la construcción de la pieza: las capas, la tensión, la memoria del lugar, el ritmo que se repite y el motivo que se desarrolla.

## Privacidad

El micrófono **solo se analiza dentro del navegador**: no se graba ni se envía a ningún servidor. Lo único que se puede descargar es la música que genera la página.

La página se conecta a internet solo para descargar las tipografías, los instrumentos de orquesta (WebAudioFont) y, si lo activas, el clima. Sin conexión, suenan instrumentos sintéticos de respaldo.

## Opciones

- `?hora=22` → cambia la hora que usa el color de la pantalla.
- `?clima=lat,lon` → el color de la pantalla puede reflejar el clima. **El clima y la hora nunca cambian el sonido.**

## Limitaciones conocidas

- Los umbrales (cuándo sube la tensión, cuántas capas entran) son valores propuestos que pueden necesitar ajuste con otro micrófono u otro espacio.
- Mientras suena la orquesta, la página es menos sensible para no oírse a sí misma. Con parlantes (sin audífonos) funciona peor.
- Un sonido continuo muy largo puede hacer que la música "respire" cada ~25 segundos.
- Si los instrumentos de orquesta no cargan, suenan los sintéticos.

## Publicarlo en GitHub Pages

1. Crea un repositorio público y sube estos archivos, con la página con el nombre `index.html`.
2. En **Settings → Pages**, elige "Deploy from a branch", la rama `main` y la carpeta `/ (root)`.
3. Espera 1 o 2 minutos. La dirección será `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

## Créditos y licencias

- Instrumentos: **[WebAudioFont](https://surikov.github.io/webaudiofont/)** (reproductor bajo GPL-3.0; datos de instrumentos bajo MIT) y soundfont **FluidR3**.
- Detalles y textos de licencia: ver [`THIRD_PARTY_NOTICES.md`](THIRD_PARTY_NOTICES.md).
- Este proyecto se publica bajo **GPL-3.0**: ver [`LICENSE`](LICENSE).
