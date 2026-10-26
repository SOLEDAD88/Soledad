# Canales faceless de Daihana

Cada canal tiene su propio formato, voz y reglas. No mezclar manuales: antes de trabajar en un canal, lee su `CLAUDE.md` en `channels/<canal>/` (resumen) y, si hace falta el detalle, su `manual-completo.md`. Cada canal tiene además una skill en `.claude/skills/`.

| Canal | Idioma | Tema | Carpeta | Skill |
|---|---|---|---|---|
| Onda lenta | Español neutro (Latinoamérica) | Psicología y neurociencia | `channels/onda-lenta/` | `onda-lenta-guion` |
| Before You Sail | Inglés | Consejos de cruceros | `channels/before-you-sail/` | `before-you-sail-guion` |
| Las cuentas de Sofía | Español de España | Finanzas con dibujos | `channels/las-cuentas-de-sofia/` | `las-cuentas-de-sofia-guion` |
| Penny Drops TV | Inglés (EE. UU.) | Historias de dinero | `channels/penny-drops/` | `penny-drops-guion` |
| Retail Requiem | Inglés (EE. UU.) | Auge y caída de marcas de EE. UU. | `channels/retail-requiem/` | `retail-requiem-guion` |

## Reglas comunes (valen para todos los canales)
- **Avisar del coste** (créditos de voz, imágenes o vídeo) antes de generar y esperar el visto bueno. **Nunca repetir una llamada de generación «para reintentar»**: se cobra dos veces.
- **No cambiar la voz oficial** de un canal.
- Datos solo de fuentes comprobadas (oficiales o primarias; nunca prensa ni Wikipedia como evidencia). Lo no verificado se marca o se quita; no se rellena de memoria.
- **Auditoría independiente antes y después de producir**, más pasada delta tras cualquier arreglo.
- Nada se sube, programa ni publica en YouTube Studio sin que Daihana participe.
- Textos largos (guiones, datos de YouTube, informes) siempre como archivo `.md`, nunca pegados en el chat. Lo que es para Daihana, también en español. Decir siempre la duración del vídeo.
- Trabajar en silencio y dar un mensaje final corto; no narrar los pasos de producción en el chat.
- Automatizar la producción, no el criterio: YouTube penaliza el contenido masivo y repetitivo.

## Diferencias que no hay que confundir
- **Contenido sintético en Studio:** «No» en Onda lenta, Las cuentas de Sofía, Penny Drops y Retail Requiem; **«Sí»** en Before You Sail (presentador y voz de IA).
- **Mención a IA en textos:** prohibida en Las cuentas de Sofía; obligatoria en Before You Sail y Retail Requiem (pie de descripción); mínima en Onda lenta.
- **Voz:** ElevenLabs en todos salvo Retail Requiem (Fish Audio).
- Cuentas: el canal Before You Sail está en `daihanar014@gmail.com`; la cuenta personal `soleday9@gmail.com` tiene otro canal («Sole Rivas»).

## Pendiente
- Penny Drops: actualizar banner, descripción y palabras clave (aún dicen «like you're 6»); confirmar handle y listas en Studio.
- Retail Requiem: registrar parámetros de la voz «Adrian», hexadecimales de color y descripción del canal.
- Onda lenta: cambiar el idioma de los vídeos anteriores a «Español (Latinoamérica)».
