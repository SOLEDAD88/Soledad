# Retail Requiem — manual resumido

Detalle completo: `manual-completo.md` (26 oct 2026; apéndice A = guion de ejemplo de Red Lobster, apéndice B = protocolo de auditoría). Vídeos, títulos, descripciones y subtítulos en **inglés (EE. UU.)**; todo lo que es para Daihana lleva traducción al español, y con ella se habla en español, de tú, sin jerga.

## Identidad
- `@RetailRequiem` · ID `UC85cPHMLTClgP4zVSyoemBw` · país España · categoría Educación · «No creado para niños».
- Lema: *The rise and fall of America's brands*.
- Tema: auge y caída de marcas y cadenas de EE. UU., como documental con cifras de documentos oficiales.
- **Ángulo fijo:** el titular popular explica la caída con una sola causa; el vídeo mira los documentos y muestra que la historia es más grande (deuda, alquileres, compras apalancadas, decisiones de dueños).
- Promesa del primer minuto: se apoya en documentos de la empresa, dice cuándo algo es solo una acusación y cuándo se acaban las pruebas.
- Siguiente marca: elegida con datos de demanda (Nexlev, vidIQ); marcas con pocos vídeos largos y algo de actualidad. Daihana delega el tema.
- Cadencia deseada: 3 vídeos por semana (sábado, martes, jueves), hoy limitada por los créditos de Fish.

## Tono
Narrador en primera persona («I»), sereno y documental. Frases cortas; sin sensacionalismo; **cada cifra atribuida** a su origen; acusaciones presentadas como acusaciones con la defensa a continuación; admite los límites («I couldn't find the result»); sin burlas ni juicios sobre personas reales; cierre reflexivo con una imagen corta. **Prohibido pedir al espectador que corrija cifras.** Desde el vídeo 4: llamada a comentar y suscribirse, integrada en el cierre.

## Formato
- **20–31 min** (hoy ≈22 con el plan Plus de Fish). 1920×1080, 25 fps, H.264 CRF 19, −14 LUFS, pico ≤ −1 dBTP. Sin música por ahora.
- Una ilustración por plano, 6–8 planos por minuto (3,7–15 s), zoom lento 2,5–9 % alternando in/out. Fundidos cruzados de 2–6 fotogramas dentro de pausas de la voz. **Sin texto en pantalla**: el texto lo ponen los subtítulos.
- Subtítulos: SRT propio en inglés (nunca los automáticos), 2 líneas de ≤42 caracteres, 1–6,5 s, CRLF, texto idéntico al guion auditado. Un capítulo por bloque.

## Estructura
`### BLOQUE NN` con párrafos en blanco; cada bloque = un capítulo.
1. **Gancho** (≈1 min): hecho fechado, titular popular, contradicción con tres cifras, pregunta y la promesa de fuentes.
2. Orígenes · 3. Máximo y giro · 4. Decisiones clave en orden cronológico · 5. Fuga de caja · 6. Quiebra · 7. Después · 8. Litigios abiertos (hechos separados de acusaciones) · 9. Cierre «What killed it?» sin causa única.
- Marcas de fuente `{clave}` → `[S#]`; `{~clave}` = cálculo propio `[calc: S#]`. Cada guion trae versión en español.
- Números en palabras para la voz (fechas y años los convierte el preparador de texto). Nombres difíciles con grafía de voz decidida antes de grabar (tabla en el manual §7); los subtítulos conservan la grafía real.

## Exactitud
1. Cada cifra, fecha, nombre, cargo y cita lleva [S#] con la fuente abierta y leída. Nada queda [VERIFICAR].
2. **Gana la fuente primaria** (documentos de la empresa, SEC, expedientes judiciales, notas de la época) sobre la secundaria; si discrepan, se anota.
3. Prudencia mejor que recorte: atribuir en vez de quitar. Cifras no fijables, en rango.
4. Antes de publicar un caso abierto, volver a mirar el expediente.
5. **Auditoría independiente antes y después de producir**, más pasada delta (protocolo en el apéndice B). Veredictos CONFIRMADA / CON MATIZ / CONTRADICHA / SIN VERIFICAR con prioridad. Se corrigen las obligatorias y recomendadas.
6. Pie fijo de descripción: «Sources are listed above. Narration and illustrations are AI-generated; scripts are AI-assisted. All trademarks belong to their owners; this channel is not affiliated with any company mentioned.»
7. **Uso de IA en Studio = «No»** en todos los vídeos (se pasa a «Sí» si algún día se imita a una persona real, hay imágenes realistas de hechos o música generada como foco).

## Estilo visual
- Ilustración vectorial plana editorial, 16:9 (1088×608), una por plano. Texto de estilo fijo antepuesto a cada escena (manual §9). Sin texto, cifras ni logos legibles; carteles en blanco; figuras sin cara; sin crustáceos en fachadas.
- **Código de color por rol:** azul = empresa protagonista (turquesa en Toys R Us), naranja = los demás (rival, dueños, prestamistas, compradores), gris pizarra = neutros (tribunales, documentos, deuda). Vigilar toldos, carteles y uniformes.
- Utilería de la época de la narración. Gráficos con proporciones del dato (medidas en píxeles). Sin saltos de brillo >±100 entre planos.
- Marca: Playfair Display + Inter. Miniatura: Playfair Display Black crema `#FAF0DC` con contorno `#081018`, etiqueta Oswald Bold sobre naranja `#E87018`.

## Voz y herramientas
- **Fish Audio**, voz «Adrian» (elegida el 6 oct 2026), mismos ajustes siempre. Tomas por frase/párrafo, comprobadas con reconocimiento de voz. Cadena de audio «3 media» (graves 70 Hz, agudos −6 dB, de-esser, voz a −17 LUFS mono). Pausas: 0,40 / 0,70 / 1,10 / 1,20 s.
- Empalme que conserva la duración para regrabar una frase.
- Imágenes: gpt-image-2 en Fish, calidad «low», 150 créditos por imagen. Presupuesto: **2 500–2 800 créditos por minuto** terminado (≈56 000–61 000 por 22 min). Plan Plus 13,49 €/mes, 250 000 créditos, no se acumulan.
- Máquina de 8 GB y 2 núcleos: un reconocimiento de voz a la vez.
- Faltan por registrar: parámetros exactos y id de la voz, hexadecimales de los colores, texto de estilo de los vídeos 1 y 2, descripción y etiquetas por defecto (están en «Kit del canal»).

## Título, miniatura y subida
- Título: **«Why [Brand] Went Bankrupt ([el giro que corrige el tópico])»**. Coincide con el contenido y con «Start here» de la descripción del canal.
- Miniatura 1280×720 JPG <2 MB: fondo sin texto generado en Fish, texto compuesto con PIL (marca arriba a la izquierda + etiqueta naranja de 3–4 palabras). Tres variantes A/B/C.
- Lista «The Rise and Fall of America's Brands». Idioma EN-US, licencia estándar, 4 etiquetas propias + las del canal, SRT propio «Con tiempos» (hay que pulsar «Publicar»).
- Descripción ≤5 000 caracteres: gancho, recorrido con advertencia, capítulos, fuentes principales con [S#], pie fijo. La lista completa de fuentes va en dos comentarios.
- Programación: **sábado 7:00 de Nueva York** (13:00 o 12:00 en Madrid según el cambio de hora). Claude **nunca** sube, programa ni publica sin Daihana.

## Entrega
MP4 en partes de 25 MiB + `unir_video.bat` (con SHA-256), clips de escucha de lo cambiado, hojas «antes | después». Carpeta del PC: `Documentos\CANAL RETAIL REQUIEM\NN MARCA`. En documentos, escribir «USD» (el signo del dólar se interpreta como fórmula).
