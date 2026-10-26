# MANUAL COMPLETO DEL CANAL "BEFORE YOU SAIL"

Versión: 26/10/2026 · Para: Daihana · Redactado por Claude a partir de los documentos del proyecto "CANAL BYSAIL EN INGLES".
Los textos que se publican en YouTube van en **inglés** (porque así debe escribirse en el canal); las explicaciones para ti, en español.

---

## 1. Identidad del canal

| Campo | Valor |
|---|---|
| Nombre | **Before You Sail** |
| Handle | **@BeforeYouSail** (en la práctica funciona como @beforeyousail) |
| ID del canal | UCjS2NPSTp1QBg1GH46quunw |
| Cuenta de Google del canal | daihanar014@gmail.com (la personal, soleday9@gmail.com, tiene otro canal: "Sole Rivas") |
| Creado | 20/09/2026 |
| Idioma | Inglés (guion, voz, subtítulos, títulos, descripciones, comentarios fijados) |
| Tema | Consejos de cruceros: antes de reservar y antes de embarcar. Contenido *evergreen* |
| Lema | "Cruise tips that save you money" |
| Público | Viajeros de cruceros de EE. UU., sobre todo **personas mayores** (primerizos y repetidores). Por eso: ritmo calmado, nada de "dopamina", frases claras |
| Por qué este nicho | RPM de audiencia en inglés ≈ 6–10+ USD (frente a 0,5–4,5 en español). Referentes: Cruise Insider y CruiseSmarter |
| Frecuencia | Decidido 17/10/2026: **2 vídeos por semana, lunes y jueves**, rotando la hora para probar cuándo ven más los mayores de EE. UU. (prueba: lunes 15:00 y jueves 18:00 hora de España) |
| Presentador | **Jerry**, presentador IA (hombre mayor, pelo canoso peinado, barba blanca, blazer azul marino sobre camisa azul claro, cubierta de crucero). Es la identidad del canal: **no se sustituye ni se elimina** |
| Narrador | **Max** (voz de ElevenLabs) |

### Descripción del canal (copiar tal cual)
```
Before You Sail helps first-time and returning cruisers make better decisions before they book.

Every week we take one cruise question — cabins, drink packages, shore excursions, tipping, hidden fees, embarkation day — and break it down in plain English: what's worth paying for, what to skip, and the small choices that quietly cost you hundreds.

No hype and no sponsored spin. Just clear, practical guidance you can use on your next sailing.

New video every week. Subscribe so you don't book your next cruise blind.

Our videos are narrated and presented using AI-generated voice and imagery. Information is researched from official cruise line and public sources, but policies change often — always confirm details with your cruise line before you book.
```
(Si se mantiene el ritmo de 2 vídeos por semana, conviene cambiar "New video every week" por "New videos every week".)

### Palabras clave del canal
```
cruise tips, cruise advice, first time cruise, cruise planning, cruise guide, cruise mistakes, cruise packing tips, cruise hacks, cruise ship, cruise vacation, cruise cabin guide, shore excursions, cruise drink package, cruise budget, cruise for beginners
```

---

## 2. Tono del narrador y de Jerry

- Amable, claro y práctico, como un amigo que sabe del tema y te cuenta lo que ha comprobado. Sin hype, sin dramatismo, sin patrocinios.
- Frases cortas, vocabulario sencillo, números dichos con claridad (se escriben como se dicen: "twenty dollars", "October fifteenth").
- **Opinión propia etiquetada**: cuando es opinión se dice "in our view"; los datos nunca se mezclan con opinión.
- **No se hace ranking de navieras** en los guiones de temas (enseña a comprobar, no a elegir marca). Excepción: el vídeo 6, que resume encuestas reales de pasajeros y lo dice.
- Jerry **no tiene experiencia inventada**: no dice "yo viajé…", no es una persona real. Se presenta como presentador IA (así consta en el vídeo y en la descripción).
- Enfoque de títulos/ganchos: priorizar el ángulo "errores / advertencia / lo que te cuesta dinero" (rindió mucho mejor que las comparaciones neutras: vídeo 1 → 210 visitas frente a 60 y 19).

---

## 3. Formato y duración de los vídeos

- **15–20 minutos** (objetivo habitual ≈ 16–17 min). Guion de ≈ 2.400–3.000 palabras a ≈ 147 palabras por minuto.
- Vídeo horizontal **1920×1080, 25 fps**, mp4 (libx264, `-preset veryfast -crf 29 -maxrate 2500k`, audio AAC 192k, `+faststart`).
- Voz + imágenes/clips de stock con movimiento suave + subtítulos quemados + música de fondo + clips de Jerry.
- Un plano nuevo aproximadamente cada **7,5 s** (≈ 130 planos por vídeo de 17 min, ≥ 65 piezas distintas, **ninguna se usa más de 2 veces** en el mismo vídeo).
- Ritmo visual **calmado y sobrio** (público mayor). Más imágenes cuando el canal monetice, pero sin acelerar.
- **Apariciones de Jerry**
  - Vídeos 1–9: clip de apertura (~25 s) y clip de cierre (~15 s).
  - **Desde el vídeo 10 (decidido 25/10/2026, porque el público no ve el vídeo entero):** Jerry abre (clip 1) y hace un **rehook de 10–15 s hacia el 40–50 % del vídeo**, en un cambio de bloque (avance de lo que viene y por qué seguir). El **cierre** (suscripción + avance del siguiente vídeo) lo dice la **voz de Max** sobre imágenes, sin clip final de Jerry. Misma duración total. Subtítulos también en ambos clips. Los vídeos 8 y 9 se quedan como están.
- Calendario aproximado hasta ahora: trailer (21/9) · V1 errores primerizos (21/9) · V2 cabinas (28/9) · V3 paquetes de bebidas (5/10) · V4 costes ocultos (12/10) · V5 excursiones (14/10) · V6 ranking de navieras (19/10) · V7 cruceros después de los 65 (22/10) · V8 día de embarque (26/10) · V9 qué incluye la tarifa (programado 29/10, 15:00) · V10 letra pequeña del contrato (aprobado, sin producir) · V11 perder el barco (pendiente).

---

## 4. Estructura del guion

Cabecera del archivo: título de trabajo, duración objetivo, regla de exactitud del guion, 3 opciones de título, concepto de miniatura.

Estructura estándar (vídeos 1–9):
1. **[HOST CLIP 1]** (~25 s): Jerry promete lo que se va a ver y avisa de lo que no hace (p. ej. "con una mezcla distinta de navieras por tema").
2. **COLD OPEN** (≈ 0:28): ejemplo concreto que muestre por qué importa + qué vamos a ver + **aviso de fuentes**: "Every figure here comes from the cruise line's own page, checked on [date]… United States versions… confirm before you sail."
3. **PARTES 1–5** (≈ 2–4 min cada una): una idea por parte, con datos de fuentes oficiales y una conclusión práctica al final de cada parte. Parte final = rutina de comprobación de 3–5 pasos para el espectador.
4. **RECAP** (≈ 1,5 min): repaso en frases cortas.
5. **[HOST CLIP 2]** (~15 s): cierre y avance del siguiente vídeo + suscripción. *(Desde el vídeo 10: bloque marcado `[HOST CLIP 2 – REHOOK]` a mitad de vídeo y cierre redactado para Max.)*
6. Después del guion: descripción, etiquetas, **comprobaciones previas a publicar**, resumen de auditoría y notas para Daihana (en español).

Cada guion en inglés tiene su traducción al español (`guion-NN-es-traduccion.md`) solo para que tú lo revises. **Los guiones siempre se entregan como archivos .md**, nunca pegados en el chat.

Un guion de ejemplo completo está en el Anexo B.

---

## 5. Reglas de exactitud y de fuentes

1. **Jerarquía de fuentes**: página oficial de la naviera > blog oficial de la naviera > contrato/condiciones vinculantes (si discrepan con el blog, manda el contrato) > fuentes secundarias (solo para contexto; lo que solo está en secundarias **no entra** en el guion).
2. **Investigación el mismo día en que se escribe el guion** (regla permanente). No se vuelven a comprobar los datos otro día salvo que sea imprescindible; sí se deja una nota de fecha ("Sources checked on…"). No dejar consultas ni re-comprobaciones abiertas, sobre todo una vez empezada la producción.
3. Se usan las **versiones de EE. UU.** de las páginas y el guion lo dice ("other regions can differ").
4. **Cifras y citas literales** se verifican palabra por palabra (caso real: "touring" vs "faring" en el vídeo 5).
5. Todo dato dependiente de fecha (tarifas, ofertas, versiones de documentos) se redacta como "lo que decía la página en la fecha de la comprobación".
6. **Lo que no se puede comprobar se quita** y se pide al público que confirme o pregunte al reservar.
7. Sin superlativos ni generalizaciones no probadas ("la más estricta", "todas las navieras"); opiniones etiquetadas como tales ("in our view").
8. Sin recomendaciones médicas, legales o financieras personalizadas: se remite al seguro, al médico o a la naviera (p. ej. vídeo 7, cruceros después de los 65).
9. No se copian títulos, estructura ni guion de otros canales (solo inspiración de tema y formato).
10. **Auditoría antes de grabar** (guion contra fuentes, hecha por subagentes independientes que no ven mis conclusiones) y **después de producir** (sonido, imagen, guion/fuentes) y auditoría "delta" tras cualquier arreglo. Procedimiento completo en `claude/auditorias/checklist_auditoria_produccion.md`.
11. **Puerta de gasto** (antes de gastar un solo crédito): guion cerrado y auditado → presupuesto → voz → imágenes/stock → clips de Jerry. Cada partida se genera **una sola vez**. **Nunca repetir una llamada de generación para reintentar** (se cobra dos veces).
12. El coste estimado se da en cuanto el guion está terminado, antes de producir, siempre con nombre y duración del vídeo.

---

## 6. Estilo visual

### Material de imágenes y clips
- Orden de preferencia: **(1) banco de imágenes ya creadas** (hueco mínimo: si se usó en el vídeo N, puede reutilizarse desde el N+4) → **(2) fotos y clips de Pexels** (cuanto más stock, mejor) → **(3) imagen generada con IA** solo para lo que no exista.
- Mezcla: planos "literales" (comida, recibos, billetes, documentos, cabinas) + planos de ambiente y escenario (playa, mar, hamaca, bebidas, baile, Alaska/Canadá/México… cualquier destino popular entre cruceristas de EE. UU., "vistas desde el barco"). El objetivo es retener, no vender cruceros.
- **Prohibido**: logos de navieras o marcas, **nombres de barcos o de navieras legibles**, texto legible que parezca de una app o documento real, **perros** (norma actual), rostros reconocibles, clips verticales. Todo el stock se revisa a resolución completa antes de montar.
- Imágenes de IA: ElevenLabs (gpt-image-2, 1280×720), estilo fotorrealista genérico.
- Movimiento: panorámica suave "sub-píxel" (lienzo de 4560×2565, ventana de 3840×2160 desplazándose 1 px por fotograma y reducida a 1920×1080).

### Subtítulos (siempre, también en los clips de Jerry y sincronizados con el audio)
- Fuente **Poppins Medium**, tamaño 54 (sobre 1920×1080), blanco `#FFFFFF`, contorno oscuro `#101010` de 4 px, sombra suave, centrados abajo con 70 px de margen, máx. ≈ 44 caracteres por línea y 2 líneas.
- Tiempos por palabra (a partir de los tiempos reales de la voz).

### Tipografía y colores de marca
- Tipografía de marca: **Poppins Bold** (títulos, miniaturas, banner, logo) y **Poppins Medium** (subtítulos, textos secundarios).
- Paleta:
  - Azul marino `#0A1A30` / `#081628` (fondos, contornos de texto)
  - Amarillo `#FFD026` (palabra clave de la miniatura)
  - Rojo `#DC2020` (bandas de texto, botón SUBSCRIBE, círculo de prohibido)
  - Dorado `#E2B25C` (acentos, subrayados, detalles del logo)
  - Blanco `#FFFFFF`
  - Verde `#2EBE60` (solo para el "check" en miniaturas)
- Logo/icono del canal: círculo azul marino con anillo rojo y símbolo de sol dorado sobre tres rayas blancas (mar); sin texto a tamaños pequeños.
- Marca de agua del vídeo: círculo del logo con el rótulo SUBSCRIBE (versión con campana).
- Banner: 2560×1440 (zona segura 1235×338 centrada), Jerry a la derecha, "BEFORE YOU SAIL" a la izquierda, subrayado dorado y "Cruise tips that save you money". Foto de perfil 800×800 (el logo).

---

## 7. Voz y herramientas

### Voz (narración)
- **ElevenLabs**, voz **Max** (`Gfpl8Yo74Is0W6cPUWWT`), modelo `eleven_multilingual_v2`, formato `mp3_44100_128`, flow `UYTPzOn4GNcqhiOuBW6q`. Una sola generación por bloque (`generations_count = 1`).
- Siglas y números deletreados para que se pronuncien bien (p. ej. B-T-U); nombres difíciles revisados antes de grabar.
- Nivelado: voz objetivo −22 dB de habla antes de mezclar; caída > 3 dB dentro de un bloque → nivelar o partir en tomas de ≤ 60 s.

### Presentador Jerry
- Foto base fija + clips con sincronía de labios (`creatify-aurora`, 720p) generados con el audio final de Max. Texto de los clips cerrado antes de generar (≈ 3 USD por clip). Se generan una sola vez y se revisan fotograma y sonido antes de montar.

### Música
- **ElevenLabs Music v2.5**, instrumental, relajante, sin percusión ni voz; **3 pistas de 3:00** combinadas (orden 1-2-3-1-3-2) para que no se repita; ≈ 18 dB por debajo de la voz y constante; fundidos de 7 s entre pistas, 5 s de entrada y 8 s de salida. Plan ElevenLabs **Creator** (sin atribución). No se registra en Content ID. Descripción: "AI-generated music".

### Montaje y calidad (entorno de Claude)
- Python + Pillow + ffmpeg (render por plano, concatenado, mezcla y limitador). Scripts completos en `claude/pipeline-codigo-completo.md` y `claude/pipeline-musica-mezcla.md`.
- Objetivos de auditoría técnica: duración del vídeo = duración del audio; ≈ −13,8 LUFS; pico < −0,5 dBFS; sincronía de Jerry ≤ 10 ms; ninguna pieza más de 2 usos; subtítulos presentes en los clips de Jerry.

### Otras herramientas
- Pexels (stock gratuito, uso comercial sin atribución; requiere el dominio `pexels.com` permitido en la red de la cuenta). Nexlev (datos y análisis de canales; de pago). YouTube Studio (subida y programación). Para ti: el archivo de vídeo se entrega partido en trozos de ≤ 25 MB + `UNIR-VIDEO.bat` + `md5.txt`.

### Costes de referencia (por vídeo ≈ 8 USD)
- Voz ≈ 2,3–2,7 USD · 2 clips de Jerry ≈ 5,9 USD · imágenes de IA ≈ 3 c cada una · música: gasto único de 1,35 USD (reutilizable) · miniatura ≈ 3 c. ≈ 5.500–6.000 créditos por USD.

---

## 8. Títulos y miniaturas

### Títulos
- Inglés, claros, que prometan algo concreto; preferir el ángulo "errores / advertencia / lo que te va a costar" sobre comparaciones neutras.
- Que el título **no prometa más de lo que el vídeo da** (la auditoría del V9 descartó un título que prometía una respuesta universal).
- Siempre 3 opciones en el guion; la elegida se anota en la ficha de publicación.
- Ejemplos publicados: "10 Cruise Mistakes First-Timers Make (And How to Avoid Them)" · "Don't Book a Cruise Cabin Until You Watch This!" · "Hidden Cruise Costs Nobody Warns You About" · "Embarkation Day Mistakes That Cost You Time (With Real Deadlines)".
- Sin nombres de navieras en el nombre del canal; en títulos de vídeo solo si el contenido lo exige y sin implicar vínculo con ellas.

### Miniaturas
- **Una sola versión** por vídeo, siempre **con botón SUBSCRIBE y campana** (no ofrecer variante sin ellos).
- 1280×720. Texto en **Poppins Bold**, 2–4 palabras de gancho, la clave en **amarillo** y el resto en blanco con contorno azul marino y sombra; una banda **roja** con texto blanco para el remate; fondo con degradado azul marino para dar contraste.
- Un elemento visual claro (insignia circular con prohibido/check, objeto en primer plano, o Jerry recortado a un lado con su base pegada al borde inferior).
- Sin logos, sin nombres de barcos o navieras, sin perros.
- Se entrega junto al `.srt` en inglés.

---

## 9. Listas de reproducción y ajustes de subida

### Listas de reproducción (crear aunque empiecen vacías)
1. **Cruise Basics: Start Here** — para quien nunca ha viajado en crucero.
2. **Money & Hidden Costs** — paquetes de bebidas, propinas, costes ocultos.
3. **Cabins & Ships** — tipos de cabina, ubicaciones, barco grande o pequeño.
4. **Onboard & Ports** — excursiones, restaurantes, día de embarque.

Página principal: vídeo destacado para suscriptores, vídeo destacado para visitantes nuevos, "Subidas recientes" y después las cuatro listas.

### Valores predeterminados de subida
- Visibilidad: **Privado** por defecto; se programa/publica después con tu confirmación. Claude **nunca publica** sin tu visto bueno.
- Categoría: Viajes y eventos. Idioma del vídeo, título y descripción: inglés. Licencia estándar.
- Comentarios permitidos, con moderación de los posiblemente inapropiados.
- **Hecho para niños: No.**
- **Contenido alterado o sintético: SÍ** (presentador y voz de IA).
- Subtítulos: subir el `.srt` en inglés de cada vídeo (lo prepara Claude).
- Miniatura personalizada: subirla a mano (Studio no permite subir archivos desde el navegador de Claude).

### Plantilla de descripción de cada vídeo
```
[One sentence: the promise of the video.]

Timestamps (approx.):
00:00 Intro
[chapters with the REAL timestamps after render]

[Link to related earlier video, if any]

Sources mentioned in this video (official pages, United States versions):
[list of URLs]

A note on numbers: fees, inclusions and rules change and differ by region. Every figure here is what the cruise line's page said on the date we checked; confirm your own line's current version before you sail. Sources checked on [Month Day, Year].

More cruise guides: [playlist link]
Subscribe: [channel link]

This video uses an AI-generated narrator and presenter, and AI-generated music.
```
- Los tres primeros renglones son los que se ven sin desplegar: ahí va lo importante.
- Decisión abierta: redacción "Sources checked on…" frente a "accurate as of…" (ahora se usa la primera).
- Sin enlaces de afiliados hasta tener audiencia real.

### Etiquetas
- 11–13 por vídeo: base del canal (`cruise tips, cruise advice, first time cruise, cruise guide, cruise planning, cruise mistakes, cruise hacks, cruise vacation, cruising for beginners, before you sail`) + 3–5 propias del tema.

### Comentario fijado
- Lo redacta Claude tras publicar (y puede escribirlo en Studio con tu permiso).

### Después de subir
- Revisar en Studio las comprobaciones de contenido antes de la hora programada.
- Seguimiento: `claude/metricas-rendimiento.md`, `claude/costes-resumen.md`, `claude/registro-videos-sheet.md`, `claude/pendientes.md`.

### Monetización (Programa de Partners)
- Nivel inicial: 500 suscriptores + 3 vídeos públicos en 90 días + 3.000 horas de reproducción en 12 meses. Nivel de anuncios: 1.000 suscriptores + 4.000 horas. Verificación en dos pasos, AdSense, sin avisos activos. Voz sintética y canal sin cara son válidos si el guion es original y aporta perspectiva propia.

---

## 10. Reglas permanentes de trabajo contigo (tus preferencias)

- Resúmenes de costes: siempre con **nombre y duración** de cada vídeo; dar el coste estimado en cuanto el guion esté terminado, antes de producir.
- Textos largos (guiones, descripciones, etiquetas) **en archivos .md** o en secciones desplegables, no volcados en el chat.
- **Todo lo que es para ti, también en español** (notas, comprobaciones, resúmenes de auditoría); hablas poco inglés y te apoyas en las traducciones.
- Siempre que pidas los datos de YouTube de un vídeo, enviar también el `.srt` en inglés.
- Miniatura: una sola versión, con SUBSCRIBE y campana.
- Auditar todo antes de producir para no gastar dinero innecesario.
- Ninguna imagen o clip se repite más de dos veces en el mismo vídeo; Pexels primero, IA solo lo que falte; banco compartido con hueco mínimo de 3 vídeos.
- Jerry no se sustituye ni se elimina para ahorrar.
- Subtítulos en pantalla se mantienen y se sincronizan de verdad con el audio (también en los clips de Jerry).
- Te gusta ir adelantada: 2–3 vídeos hechos y programados por adelantado.
- Música: plan Creator, sin atribución, sin Content ID.

---

## ANEXO A — Instrucciones de este proyecto, tal cual están

El campo de **instrucciones personalizadas** del proyecto de Claude "CANAL BYSAIL EN INGLES" está **vacío** (`""`). Lo único que contiene el proyecto como definición es:

> **Nombre:** CANAL BYSAIL EN INGLES
> **Descripción:** CANAL DE CRUCEROS CON ALTO RPM EN INGLES

Las reglas con las que trabajo salen de (1) tus preferencias guardadas (sección 10), (2) los documentos del proyecto (plan, configuración, pipeline, auditorías, pendientes) y (3) lo que me has ido pidiendo. Si quieres que este manual pase a ser el campo de instrucciones del proyecto, puedes pegarlo (o su sección 10) en Ajustes del proyecto.

Documentos clave del proyecto: `plan-canal-cruceros-ingles.md`, `configuracion-canal-youtube.md`, `investigacion-canales-faceless-15-20min.md`, `presupuesto-y-presentador-ia.md`, `origen-del-personaje-jerry.md`, `estrategia-jerry-rehook.md`, `pipeline-codigo-completo.md`, `pipeline-musica-mezcla.md`, `auditorias/README.md`, `auditorias/checklist_auditoria_produccion.md`, `costes-resumen.md`, `metricas-rendimiento.md`, `registro-videos-sheet.md`, `pendientes.md`, y por vídeo: `guion-NN-en-*.md`, `guion-NN-es-traduccion.md`, `publicacion-video-NN.md`.

---

## ANEXO B — Guion de ejemplo (Vídeo 9, versión final auditada, sin la parte de auditoría)

# VIDEO 9 — "'Included' Doesn't Mean the Same Thing on Every Cruise Line"

**Channel:** Before You Sail · **Target length:** ~16 min (narration ≈2,428 words at ≈147 wpm → ≈16:31) · **Narrator voice:** Max (ElevenLabs)
**Host clips (lip-sync):** 2 — [HOST CLIP 1] and [HOST CLIP 2]
**Everything else:** narration over still images / stock clips with slow zoom. **No cruise-line logos, no named ships, no dogs** in any image.

**Accuracy rule for this script:** every figure and quote comes from a cruise line's own official page, checked on **14 October 2026** and re-checked on **15 October 2026**. They are the **United States versions** of those pages; other regions can differ, and the script says so. The script covers five lines (Norwegian, Royal Caribbean, Carnival, Virgin Voyages, Viking) with a different mix of lines per topic, and the host clip says so. It never ranks the lines; it teaches the viewer how to check their own. Editorial opinions are labelled ("in our view").

### TITLE OPTIONS
1. "Included" Doesn't Mean the Same Thing on Every Cruise Line *(chosen: it matches the content best)*
2. Before You Pay Extra: What Your Cruise Fare Already Includes (and What It Doesn't)
3. Check This Before You Buy a Drinks Package or Wi-Fi Plan (What's Already Included)

### THUMBNAIL CONCEPT
A close-up of a printed fare breakdown on a wooden table, with a pen and a coffee cup; two lines circled in red. Left two-thirds is the paper; right side, bold white stacked text: **"WHAT'S"** over **"INCLUDED?"**. Small red cross and green check icons beside it. No logos, no legible brand names, no ship names.

---

## [HOST CLIP 1] — 0:00
*(On camera, deck, ~25 seconds)*

> Cruise lines love to talk about what's included. The trouble is that they don't all mean the same thing by it. In this video, we look at what five real cruise lines say on their own pages about what the fare includes, how room service works, and which drinks you can bring, with a different mix of lines for each topic, so you don't pay twice for something you already have, and you don't assume something is free when it isn't.

---

## COLD OPEN — 0:28
*(Image: a printed fare breakdown on a table; a cabin door with a room-service tray)*

Here is a small example of why this matters. Virgin Voyages says its restaurants and Wi-Fi are part of the fare. Its own help page also says there is a ten dollar delivery charge on room service, unless you order items totaling ten dollars or more, or you're staying in RockStar Quarters. Viking, on the other hand, lists twenty-four-hour room service among the things included in its fare. Royal Caribbean's page says a service charge applies when you order. Same ocean, same idea, different rules.

A lot of cruise advice is about what to buy. This video is about what to check before you buy anything. We'll look at what one mainstream line lists as included and not included, what four lines say about room service, which drinks you may carry on board at three lines, what two other lines actually put in the fare, and a cost that's easy to overlook: gratuities.

A quick note before we start. Every figure here comes from the cruise line's own page, checked on October fifteenth, twenty twenty-six. These are the United States versions of those pages, and other regions can differ. Cruise lines change these rules, so treat every number as what it said when we looked, and confirm your own line's version before you sail. We cover five lines, so if yours isn't here, the same questions still apply.

---

## PART 1 — How a cruise line defines "included" — 2:12
*(Images: a fare page on a laptop; a gym; a coffee bar; a not-included list)*

Let's start with how a cruise line defines its own word "included". Norwegian Cruise Line publishes a page titled "What does my cruise fare include?", and it is quite detailed.

On the included side, it lists meals at the complimentary dining venues, iced tea, regular coffee, tea and ice water, all onboard entertainment except dinner and lunch theater, access to fitness facilities, and the outdoor pools and hot tubs. Room service menu items are on that list too, but with a note in parentheses: a convenience charge may apply. The coffee bar entry has a note as well. Regular coffee and pastries are included, but specialty coffees cost extra.

Now the not-included side. The same page lists service charges first, and Norwegian explains them on a separate service charge page, which we'll come back to later. It also lists specialty restaurant meals, alcoholic drinks, and sodas and some other non-alcoholic beverages. It also lists spa and salon services, exercise classes, the casino, shore excursions, photography, laundry, Wi-Fi, and use of the medical center.

Three of those are worth a second look. First, the gym is included, but exercise classes are listed separately as not included. Second, Wi-Fi is on the not-included list, so it isn't part of the base fare on that page. Norwegian's current Free at Sea promotion, on its own offer page, includes one hundred fifty minutes of Wi-Fi per person on eligible reservations created on or after November fifth, twenty twenty-five, with limits set out in its terms. So the exact answer depends on which offer your booking includes. And third, the medical center is not included, which is one more reason to ask your own insurer what it covers at sea before you go.

None of this is a complaint about Norwegian. The point is that this page exists, and it is a quick way to see what the base fare covers. Several lines publish something similar, so look for yours, or ask the line. The full terms are in your ticket contract.

---

## PART 2 — Room service: where "free" can come with a footnote — 4:27
*(Images: a room-service tray at a cabin door; a breakfast tray; a hallway)*

Next, room service, because this is a place where "free" can come with a footnote.

Royal Caribbean's own page says you order from the room service menu in your stateroom, and that a service charge of seven dollars and ninety-five cents applies. It adds that an eighteen percent gratuity is additional and added automatically to your check, and that the charge is subject to change without notice. The same page says room service is available any time of the day or night.

Norwegian's page for this says a convenience charge of up to nine dollars and ninety-five cents is added to each order placed. The menu items themselves remain complimentary. The page also lists a four dollars and ninety-five cent room service breakfast fee for breakfast orders, but it doesn't say whether that replaces the convenience charge or is added to it, so ask when you order. Norwegian's fare page says the convenience charge does not apply to guests in The Haven and Norwegian Suites. It doesn't say whether the breakfast fee is waived for them too. Separately, a twenty percent gratuity and beverage service charge applies to non-complimentary beverages and special-occasion items. So for someone in a standard cabin who orders breakfast in the room every morning, there could be a charge on every one of those orders.

Virgin Voyages calls its in-cabin dining ShipEats, and its page says there's a ten dollar delivery charge, waived if you order items totaling ten dollars or more, or if you're staying in RockStar Quarters. Viking, as we said, lists twenty-four-hour room service as included.

We're not saying one approach is better. We're saying that you should look up your own line's room service rule before you decide how much to rely on it. And if mobility makes the dining room harder for you, ask the line's accessibility team before you sail, instead of assuming room service will cover it.

---

## PART 3 — What you can carry on board yourself — 6:39
*(Images: a carry-on bag with cans and cartons; a terminal bag check; a sealed wine bottle)*

Now, what you can carry on board yourself. Before you pay for bottled water or a drinks package, it's worth knowing what each of these lines lets you bring. The answers are very different. On two of the three lines below, ordinary bottled water for drinking isn't allowed in your carry-on.

Royal Caribbean says guests may bring non-alcoholic beverages as carry-on items on boarding day, up to twelve standard seventeen-ounce cans, bottles, or cartons per stateroom. That limit is per room, not per person. On embarkation day, each guest of drinking age may also bring one sealed seven hundred fifty milliliter bottle of wine or champagne. Boxed wine isn't allowed. The page points to a separate corkage policy, so check that too. Distilled water for infant, medical, or dietary use is permitted.

Carnival has different container rules, and this is its policy for departures from the United States. Its page says water, sodas, and other non-alcoholic drinks packaged in glass or plastic bottles are not allowed. Sealed cans or cartons are allowed on embarkation day, up to a dozen per person, each twelve ounces or less, in your carry-on bag. It also allows one sealed seven hundred fifty milliliter bottle of wine or champagne per person, for guests twenty-one and over, on embarkation day only. If you drink your own bottle in the main dining room, a specialty restaurant, or a bar, Carnival lists a fifteen dollar corkage fee per bottle. Carnival's page also has a separate rule for distilled water for CPAP machines: it must be hand-carried, along with the machine. If you use one, read that section.

Norwegian's rule is the shortest to state: no drinks, with a few exceptions. Its page says guests are prohibited from bringing any beverages, with exceptions for sealed purified or distilled water used with medical devices or infant formula, and for sealed wine. If you need that medical water, the page says to contact Norwegian's access desk to verify an exception and get pre-approval to show to security. Wine is for guests twenty-one or older, boxed wine isn't allowed, and there's a corkage fee of fifteen dollars for a seven hundred fifty milliliter bottle. The page says guests with a beverage package don't pay it. Separately, the page says guests who bring drinks to the terminal are told to take them back to their car, and if there's no car there, the drinks are thrown away. And Norwegian's page also says you can't bring any drinks back on board at a port of call, and that includes open containers of water. If you buy alcohol ashore, the page says the ship stores it and you pick it up later.

So the same plan, "I'll just bring my own", works up to a limit on one line, works only in cans and cartons, also up to a limit, on another, and is mostly not allowed on a third. Check your line's page before you pack. Items that don't pass the rules may be confiscated or thrown away at embarkation, and Carnival's page says that happens without compensation.

---

## PART 4 — Two longer inclusion lists, and the cost on a different page — 9:48
*(Images: two fare lists side by side; a folio statement; a Wi-Fi symbol on a phone)*

Now two lines that publish longer lists of what's in the fare.

Virgin Voyages, in its own what's-included article from December twenty twenty-five, says its restaurants are included, that Wi-Fi is included with every sailing, and that it includes free group fitness classes like yoga, spin, and HIIT, as well as entertainment. It also says it always includes soda and other essential drinks like drip coffee, tea, and still and sparkling water. Cocktails, mocktails, smoothies, and fresh-pressed juices are sold separately. Virgin's VoyageFair Choices page adds that, for Sea Terrace cabins and below, the Wi-Fi level depends on the fare you pick. The Base fare includes Basic Wi-Fi, which Virgin describes as social media, messaging, and limited browsing. The Essential fare includes Classic Wi-Fi, which Virgin describes as browsing plus audio calling. The Premium fare includes Premium Wi-Fi for two devices. Its dining page also says Treat Yourself items on select menus, and dinner shows like Another Rose, cost extra.

Viking's page for its ocean cruises, which is priced for United States residents, lists a complimentary shore excursion in every port of call, free Wi-Fi with connection speed that may vary, beer, wine, and soft drinks with onboard lunch and dinner, twenty-four-hour specialty coffees, teas, and bottled water, alternative restaurant dining at no extra charge, and twenty-four-hour room service. The page also says fares don't include pre-paid charges, optional facilities, and personal charges. The offer shown on that page was for bookings made in October twenty twenty-six, so check the current terms.

Compare those to Norwegian's list from earlier. Virgin's page names free group fitness classes. Viking's page lists access to its fitness center but doesn't mention classes, so ask. Norwegian lists classes as not included. These lines include different things, and that doesn't make one better. It means that when you compare prices, you are not comparing the same thing.

And here is a cost that often sits on a different page: gratuities. Norwegian lists service charges as not included, and its service charge page puts them at twenty dollars per person per day for most cabins, and twenty-five dollars in The Haven and suites, for guests three and older. Royal Caribbean's page says eighteen dollars and fifty cents per guest per day in standard cabins, and twenty-one dollars in suites, and it says gratuities are optional and can be adjusted or removed. Virgin calls its guests Sailors. It says that for voyages booked on or after October seventh, twenty twenty-five, it automatically applies a daily service gratuity of twenty-two dollars per Sailor to your onboard folio, or twenty dollars a night if you pre-pay. If you pay on board, Virgin says you can change or remove it at the Sailor Services desk, while a pre-paid gratuity is locked in and non-refundable. If you booked before that date, check your own booking. And Viking's U.S. ticket contract says gratuities on board and on land are not included in the cruise fare. The amount depends on the line, and on some lines on your cabin, so look up your line's figure, multiply it by the nights and the people, and add it in before you compare two fares.

---

## PART 5 — A five-step routine to check your own line — 13:00
*(Images: a checklist on a clipboard; a phone screenshot; a calendar)*

So how do you check your own line, quickly? Here is a short routine.

First, find the line's own "what's included" or "what does my fare include" page, or ask the line, and save a screenshot with the date. If a rule changes later, you'll have a record of what it said when you booked. But recheck before you sail, because fees and onboard rules can change. Keep your booking confirmation too, because some offers depend on the date you booked.

Second, read both lists. Read the not-included list for things like Wi-Fi, classes, and gratuities. And read the small notes in the included list. On Norwegian's page, for example, that's where "convenience charge may apply" sits, in parentheses.

Third, look for the small words: "convenience charge", "service charge", "gratuity", and "subject to change". Those words are often where fees and changes show up.

Fourth, check the drinks you can bring. Look at the container type, the number, whether it's per room or per person, and whether it's for embarkation day only. Don't pack anything the page doesn't clearly allow, and if you need water for a medical reason, ask the line before you pack.

And fifth, do this before you buy a drinks package, a Wi-Fi plan, or any other add-on. We covered how drink packages work in an earlier video, and the link is in the description. In our view, it's easiest to judge a package once you know what's already included, so settle that first, and decide on the add-on second.

---

## RECAP — 14:40
*(Images: quick sequence of the earlier images)*

So, to bring it together. "Included" doesn't mean the same thing on every line, so read your line's own list, both sides of it. Room service can carry a charge on most orders, as on Norwegian, or a delivery charge, as on Virgin, or be listed as included, as on Viking, so look up yours. Carry-on drinks were allowed up to a limit on one line, limited to cans and cartons on another, and mostly not allowed on the third, so check the container, the number, and whether it's per room or per person. And gratuities often sit on a separate page, so add them in before you compare any two fares.

None of this is hard once you know it's there. Checking first is what keeps you from an expensive surprise.

---

## [HOST CLIP 2] — 15:12
*(On camera, deck, ~15 seconds)*

> Check what's included first, and you're more likely to spend your money on the things you actually want. Next time, we'll look at the fine print that's easy to miss. Subscribe, and we'll see you then.

---

### VIDEO DESCRIPTION (ejemplo)
```
"Included" doesn't mean the same thing on every cruise line. We look at what five real lines say on their own pages about what the fare includes, how room service works, which drinks you can bring, and what gratuities cost, with a different mix of lines for each topic, so you don't pay twice or assume something is free when it isn't.

Timestamps (approx.):
00:00 Intro
00:28 Why this matters
02:12 1. How a cruise line defines "included"
04:27 2. Room service: where "free" has a footnote
06:39 3. What you can carry on board
09:48 4. Two longer inclusion lists, and gratuities
13:00 5. A five-step routine to check your own line
14:40 Recap

How drink packages work (earlier video): [link to Video 3]

Sources mentioned in this video (official pages, United States versions):
Norwegian — What does my cruise fare include?: https://ncl.com/cruise-faq/cruise-fare-includes
Royal Caribbean — In-room food service: https://www.royalcaribbean.com/faq/questions/in-room-food-service
Carnival — Liquor and beverage policy (Know Before You Go): https://www.carnival.com/help?topicid=2633
Virgin Voyages — What's included: https://www.virginvoyages.com/ahoy/stories/whats-included-on-a-virgin-voyages-cruise
Viking — Viking Inclusive Value (ocean): https://www.vikingcruises.com/oceans/why-viking/viking-difference/viking-inclusive-value.html
(…the full list of 15 official pages is in the original script file)

A note on numbers: fees, inclusions and rules change and differ by region. Every figure here is what the cruise line's page said on the date we checked; confirm your own line's current version before you sail. Sources checked on October 15, 2026.

More cruise guides: [playlist link]
Subscribe: [channel link]

This video uses an AI-generated narrator and presenter, and AI-generated music.
```

### TAGS (ejemplo)
```
what's included on a cruise, cruise fare includes, cruise extra costs, cruise room service fee, bring drinks on a cruise, cruise carry-on drinks policy, cruise gratuities, cruise wifi included, cruise tips for beginners, before you sail, cruise mistakes, cruise add-ons, cruise service charge
```

### COMPROBACIONES PREVIAS A PUBLICAR (ejemplo, en español para ti)
1. Volver a comprobar las tarifas el día de grabar y el de publicar (cambian) y actualizar la fecha dicha en voz y la de la descripción.
2. La página de Viking está ligada a una oferta de octubre de 2026: releerla si se publica después.
3. Poner el enlace del vídeo 3 y los de lista de reproducción y canal en la descripción.
4. Al subir, marcar **Sí** en contenido alterado o sintético.
5. Imágenes: banco compartido (hueco ≥ 3 vídeos), sin logos, sin barcos con nombre, sin perros; Pexels primero, IA solo lo que falte.
6. Voz: medir el nivel por sección y nivelar si baja más de 3 dB; luego añadir la música (3 pistas, ≈ 18 dB bajo la voz).
7. El guion dice "United States versions" y que otras regiones pueden variar: no quitarlo. Mantener "con una mezcla distinta de navieras por tema" en el clip de Jerry.
8. Subtítulos también en los dos clips de Jerry.

*(El guion original en el proyecto, `guion-09-en-cruise-fare-includes.md`, incluye además el resumen completo de la auditoría y las notas para Daihana.)*
