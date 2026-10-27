# Penny Drops TV — manual resumido

Detalle completo: `manual-completo.md` (v1.1, 27 oct 2026; incluye voces, catálogo de vídeos y un guion de ejemplo en los anexos). Vídeos en **inglés (EE. UU.)**; todo para Daihana, en español.

## Identidad
- Nombre siempre **Penny Drops TV**. ID `UCZoVpT4I5NZMt2jlEdIk43A`. Handle **@PennyDropsTV** (confirmado el 27 oct 2026).
- Tema: grandes historias de dinero reales (estafas, quiebras, crisis, burbujas, magnates), paso a paso y en lenguaje sencillo.
- Fórmula vigente desde el 3 oct 2026: **«(Explained Simply)»** (no «like you're 6»). La frase de marca se dice **una sola vez**, en la apertura.
- Narradora **Penny** (chica con rizos cobrizos y peto verde). Estilo: palitos dibujados, faceless, sin imágenes reales.
- Público EE. UU.: **todo en dólares**. Calendario: **domingo, martes y jueves 15:00 hora de Nueva York** (las horas de prueba son a propósito: no «corregirlas»).
- Canal hermano: Las cuentas de Sofía (reutiliza su formato, método de imágenes, música y efectos). **Nunca repetir una historia de Sofía.**

## Tono
- Inglés llano, frases cortas, una idea por frase; los términos técnicos se definen en la misma frase.
- Ejemplos pequeños (limonada, hucha) siempre con el rótulo **IMAGINED EXAMPLE**.
- Atribuye cada afirmación («prosecutors say…», «a court found…»). Fechas dentro de la frase; nada de «today» o «still» sin fecha.
- Humor puntual y sobrio; nunca se burla de las víctimas.
- Cierre: **Penny's Playbook** (3 lecciones) + «None of this is financial advice. It's a way to ask better questions.» + adelanto del siguiente.

## Formato
- **≈15 min** (mejor más largo que corto), ≈12 000–12 800 caracteres de voz; 0,0745 s por carácter. 1920×1080, 30 fps, H.264 CRF 20, AAC.
- Un plano cada ≈6 s; planos por bloque = max(1, round((duración + 0,45)/6)).
- Esquema: cold open (20–40 s, sin logo ni saludo, termina con «This is the story of… And I'm going to explain it simply») → cortinilla de título → 4 actos → **Penny's Playbook** → CTA2 → adelanto.
- CTA1 (inicio del acto 3): «If Penny is helping you understand money, subscribe. Now, <siguiente acto>.» CTA2: «Subscribe and comment!» con flecha roja hacia abajo. Pantalla final ≈11 s.
- Los rótulos salen del guion y cuadran con la voz; nunca sobre la cara de Penny.

## Exactitud (resumen)
- **Solo fuentes oficiales** (tribunales, reguladores, gobiernos, documentos de la propia empresa, palabras de la persona). Nunca prensa ni Wikipedia como evidencia.
- Ningún guion se enseña a Daihana sin comprobar cada cifra, fecha, cita y atribución contra el texto literal de una fuente oficial; mínimo **dos pasadas independientes**.
- Escalera de lenguaje: acusación → «accused/alleged»; probado → «a court found»; acuerdo → «without admitting or denying»; conclusión propia → «in my ranking».
- Etiquetas obligatorias: **Dramatization** (solo dramatizadas, nunca citas literales), **IMAGINED EXAMPLE**, **Read from the … (voice is not his/theirs)**.
- Moneda: todo en USD; conversiones con tipo oficial (Fed H.10) anotadas en «Fuentes».
- Datos fechados y estables: «lo que se graba es lo que se va a publicar». Temas muy sensibles al tiempo van al final de la cola. Comprobación de frescura al entregar, con tres revisores.
- Vigilar los nueve fallos habituales: gancho más fuerte que el cuerpo, causa insinuada, omisiones, atribución floja, absolutos, cifras sin contexto, rótulos con glifos, cargo en presente, ejemplos sin etiqueta.

## Estilo visual
- Rótulos Permanent Marker 72 px: cifras en rojo `#e11d1d`, el resto verde `#19a63a`, borde blanco 3 px. Cortinillas: fondo negro, rojo `#ff2d2d` y amarillo `#ffd400`. Lienzo crema `#f4efe6`.
- Imágenes: gpt-image-2 en ElevenLabs, 1920×1080, una variación, **referencia oficial de Penny (opción C)** en cada prompt. Descripción de Penny y descriptor de estilo literales (manual §8.3). Sin texto, marcas ni caricaturas de personas reales.
- Constantes de personajes obligatorias en cada guion; personajes distintos entre sí en escenas seguidas.
- Zoom del 7 % alternando in/out con interpolación sub-píxel (no `zoompan`). **No cambiar sin petición de Daihana.**

## Voz, música y costes
- Penny: ElevenLabs `eleven_v3`, voz Nichalia Schwartz `XfNU2rGpBa01ckF309OY`. Voces secundarias distintas por personaje (lista en el Anexo B). Un bloque por llamada.
- Música y efectos: **reutilizar la biblioteca de Sofía, nunca generarlos.** Música a −23/−28 dB bajo la voz, efectos al 12 %. **Nunca sonidos de transición.**
- Sonoridad −16 a −12 LUFS, pico ≤ −1 dBTP.
- Un vídeo cuesta ≈36 000–47 000 créditos (≈6–8 €). `estimate_only` antes de cada tanda y aprobación expresa. **Nunca repetir una llamada de generación.** Guardar los session_ids en disco al lanzar cada tanda.

## Título, miniatura y subida
- Título: el nombre que la gente busca al principio, cifra en dólares, «accused/alleged» si hay presunción de inocencia, **«(Explained Simply)» al final**, 59–86 caracteres. Título de reserva más prudente en cada guion. No tocar títulos publicados en dos semanas ni durante una prueba A/B.
- Miniatura 1280×720 JPG <2 MB: cifra roja grande, línea blanca, recuadro negro recto con el caso y fecha. Se entrega como JPG individuales, uno por mensaje.
- Subida: archivo 1920×1080 (nunca la versión ligera), `.srt` propio, «No» en contenido sintético, no es para niños, comentarios con retención de los inapropiados. Paquete `Penny_NN_<Caso>_YOUTUBE.md` con cada vídeo.
- Entrega por partes ≤25 MB, cada una en su mensaje «Parte N de M», con `UNIR_VIDEO.bat`. Siempre decir la duración.

## Listas y textos de Studio (27 oct 2026)
- Listas públicas: «Money Stories Right Now» (6), «Billion-Dollar Scams» (7), «Crashes & Crises» (1). «How They Got Rich» y «Penny's Playbook» no existen. Criterio: vídeos 5–8 → Billion-Dollar Scams; del 10 en adelante → Money Stories Right Now.
- Descripción del canal, palabras clave y banner v2 (`banner-v2-vista-previa.jpg` es solo una vista previa de 2000×1125; el archivo bueno es `penny_banner_v2.jpg`, 2560×1440) están preparados en `textos-studio-canal.txt`. **Sin aplicar aún en Studio**: siguen con «like you're 6».

## Trato con Daihana
Trabajar en silencio y un único mensaje final corto en español. Guiones siempre como archivo. Aprobación de texto y coste antes de gastar créditos.
