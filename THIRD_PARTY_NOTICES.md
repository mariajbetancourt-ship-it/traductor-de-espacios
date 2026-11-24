# Avisos de terceros

Este proyecto usa material de otras personas. Esto es lo que usa, de dónde viene y bajo qué licencia lo declaran sus autores.

## 1. WebAudioFont (el reproductor de instrumentos)

- Autor: surikov — https://github.com/surikov/webaudiofont
- Licencia: **GNU GPL v3**. Su archivo `LICENSE.md` es el texto completo de esa licencia. El autor también escribe en su README que se le puede contactar si se necesita otra licencia.
- Cómo se usa aquí: la página **no incluye** el código de WebAudioFont. Lo carga desde
  `https://surikov.github.io/webaudiofont/npm/dist/WebAudioFontPlayer.js` cuando se abre la página.
- Por eso este repositorio se publica con licencia GPL-3.0 (ver `LICENSE`): es la opción prudente al enlazar con un reproductor GPL.

## 2. Datos de los instrumentos (webaudiofontdata)

- Repositorio: https://github.com/surikov/webaudiofontdata
- Licencia: **MIT**. Texto de la licencia, tal como está en el repositorio del autor:

```
MIT License

Copyright (c) 2017 Srgy Surkv

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

- Cómo se usa aquí: la página descarga 10 instrumentos desde
  `https://surikov.github.io/webaudiofontdata/sound/` (versión "FluidR3_GM"): violín, chelo, contrabajo,
  cuerdas, pizzicato, arpa, timbal, flauta, clarinete y corno.

## 3. Los sonidos originales (soundfont FluidR3)

- Los instrumentos de WebAudioFont vienen de bancos de sonido libres. Los que usa esta página son de **FluidR3**.
- El autor de WebAudioFont enlaza la licencia de FluidR3 en su README:
  https://github.com/musescore/MuseScore/blob/master/share/sound/FluidR3Mono_License.md
- **Pendiente de revisar:** al preparar este archivo, ese enlace no abrió (error 404), así que no pude leer el texto de la licencia directamente. Antes de publicar, ábrelo o busca la licencia vigente de FluidR3 y confirma que lo que dice coincide con este aviso.

## 4. Tipografías

- Fraunces e Inter, cargadas desde Google Fonts (https://fonts.google.com). Ambas son tipografías de código abierto.

## 5. Clima (opcional)

- Si se abre la página con `?clima=latitud,longitud`, consulta Open-Meteo (https://open-meteo.com). Sin ese parámetro, no se hace ninguna consulta.
