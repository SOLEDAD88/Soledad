# Las cuentas de Sofía — manual resumido

Detalle completo: `manual-completo.md` (26 oct 2026; incluye las reglas permanentes del proyecto en §16). Donde una norma antigua choca con una reciente, manda la reciente.

## Identidad
- `@LasCuentasDeSofia` · español de España (canal, vídeo, título, descripción y todo texto dentro de las imágenes) · categoría Educación.
- Tema: finanzas y economía explicadas con dibujos, sin tecnicismos y con datos oficiales. Faceless; protagonista **Sofía**, personaje animado.
- Posicionamiento «El Profesor + El Operador». Se quitó la fórmula «como si tuvieras 5 años» en textos nuevos (los publicados no se tocan).
- **Secciones (desde el 18 oct 2026):** lunes **Casos** (historias españolas de dinero) · miércoles **«Lo básico, sin prisa»** (público de 55+) · viernes **AL DÍA** (actualidad con datos oficiales y fecha).
- **Ningún vídeo nuevo se produce sin el ok de Daihana.**

## Tono
- Sofía: voz cercana, tranquila, conversacional. Frases cortas, una idea por frase, señales para ordenar («esto es lo importante»).
- Ejemplos con números reales; los inventados se avisan como inventados.
- Neutral: sin partidos ni Gobiernos; sin nombres de personas ni entidades salvo lo imprescindible; presunción de inocencia.
- Prudente: no dice dónde poner el dinero ni si algo «es seguro». Divulgación, no asesoramiento.
- **Nunca se menciona que algo esté generado con IA, en ningún texto** (regla del 26 oct 2026).
- Metáfora recurrente: el patio del cole (quioscos = bancos o empresas, caja común…), con papeles fijos dentro de cada vídeo y avisando de que es una imagen.

## Formato
- Duración real **10–12 min como mínimo** (suelen salir de 11 a 19). ≈154 palabras por minuto → 1 900–2 500 palabras. 1920×1080, 30 fps, MP4 H.264 + AAC 192k.
- Una imagen nueva cada ≈6 s; ninguna escena <1,3 s; láminas fijas >11 s se parten.
- Transiciones: siempre fundido suave (≈0,4 s). Rótulos con fundido (≈0,35 s), sin rebote ni sonido, nunca dos textos en la misma posición; principal ≥2,6 s, fuente ≥4 s.

## Estructura del guion (vigente, 26 oct 2026)
1. **Hook** (35–50 s): lo más sorprendente, un hecho vivo y concreto; una sola cifra limpia; la pregunta antes del segundo 25–30; no adelanta el final.
2. Primeros minutos = la información más valiosa.
3. **Rehook** hacia la mitad.
4. Partes numeradas, una idea cada una, un patrón nuevo cada ≈90 s.
5. **CTA interno** a mitad (una pregunta para comentarios).
6. **Resumen** en ideas numeradas.
7. **Cierre fijo:** CTA → aviso de voz «Este vídeo es divulgativo, no asesoramiento financiero. Las fuentes están aquí, y también en la descripción.» → tarjeta FUENTES (solo instituciones, sin voz) → tarjeta final de marca (15 s, sin voz; único sitio donde Sofía sonríe).
- **Prohibido al principio:** «regla del juego», cómo investigamos, fuentes, fecha de corte y el aviso de «no es asesoramiento». Todo eso va solo al final y en la descripción.
- Cada vídeo es una foto fija a su fecha de corte; el día de publicar no se consulta nada. Lo hecho no se rehace salvo petición de Daihana.

## Exactitud
- **Solo fuentes oficiales** (BOE, CENDOJ/Poder Judicial, Banco de España, CNMV, INE, ministerios, UE/EUR-Lex…). **Nunca prensa**, ni webs de bancos o comparadores. Lo que solo está en prensa se deja fuera.
- Una cifra por rótulo con fecha, magnitud y fuente en el mismo fotograma. «Plan ≠ hecho». El rótulo usa el mismo sujeto, verbo y tiempo que la voz.
- Casos con muchas partes: sin nombres de personas ni entidades; «hasta donde hemos podido comprobar, ninguna condena en fuentes oficiales a [fecha]».
- **Auditoría en tres capas** (guion antes de producir con 2 auditores hasta 0 ALTA; MP4 después; fotogramas cambiados). Ver `procedimiento-auditoria-sofia.md` en el proyecto.
- El dibujo también afirma: bocas rectas, monedas solo donde haya dinero real, sin destellos, sin escudos ni banderas, balanzas niveladas con «?» si la cuenta está abierta.

## Estilo visual
- Animación 2D plana: muñecos de palo, contorno negro grueso, colores planos, escenario patio del cole. Figurantes: cabeza redonda blanca, sin pelo, boca recta. **Sin vídeo de stock, logos, escudos ni banderas.**
- **Sofía (única versión válida):** cara melocotón claro, cejas marrones pequeñas, ojos de punto, mejillas rosas, **boca recta**, pelo castaño con flequillo ladeado y **coleta ALTA rizada con coletero rosa**, camiseta blanca, falda rosa en A, zapatillas blancas, cuerpo completo. Generar siempre con `connect_from` = nodo de referencia `XVU64QHIPdEh3UOkH9UV` (flow `ZvSqbdvBrB6cGHTT47gK`), modelo gpt-image-2, con el texto obligatorio de la regla de aspecto (manual §16.1). Antes de dar un vídeo por terminado: hoja de contacto de cabezas.
- Paleta neutra en AL DÍA y Lo básico: crema, amarillo pálido, ocre, arena, gris claro. Marca: rosa de Sofía, blanco, negro.
- Rótulos en **PermanentMarker** mayúsculas (el «&» parece «+»); cifras y fechas como rótulos de código, nunca dibujadas por la IA.
- Todo texto dentro de la imagen en español; revisar **cada** imagen por texto en otro idioma.

## Voz y herramientas
- ElevenLabs «Sofia – Captivating» (versión «Narración con más energía»), `voice_id pN4aFdNIp2mvGfTwy1Oj`, `eleven_v3`. Comprobar con Whisper.
- Imágenes: gpt-image-2 en el flow `ZvSqbdvBrB6cGHTT47gK`, 16:9 en el prompt, ≈185–420 créditos por imagen. Reintentos solo de láminas señaladas por la auditoría.
- Montaje: Python + PIL + numpy + ffmpeg, zoom/paneo lento. Música sintetizada `MUSIC_GAIN = 0.035` relativo a la voz; mezcla −15,3 LUFS, TP ≈ −1,5. Efectos solo puntuales y temáticos (6–16 por vídeo), nunca por rótulo ni en transiciones.

## Título, miniatura y subida
- Título ≤≈60 caracteres con el gancho en los primeros 40; el nombre de la sección va en la miniatura, no en el título. 3 opciones, aprobadas por Daihana.
- Miniatura 1280×720 por sección: Casos = panel azul petróleo + ilustración; Lo básico = fondo verde con rayos y Sofía recortada, cifra en amarillo; AL DÍA = fondo amarillo con rayos y Sofía.
- Ajustes: no es para niños; **contenido alterado o sintético = No**; lista con número; pantalla final (inicio = duración − 15 s, Suscribirse + 2 vídeos, sin enlaces); comentario fijado con pregunta y fecha de corte; subtítulos automáticos revisados.
- Cada vídeo trae `datos-youtube-<vídeo>.md` con lista de reproducción y número, pantalla final con minuto, minuto de la tarjeta FUENTES y duración real.

## Entrega y trato con Daihana
- Carpeta `C:\Users\Propietario\Documents\CANAL LAS CUENTAS DE SOFIA`, una subcarpeta por vídeo; MP4 en partes ≤26 MB con `UNIR_VIDEO.bat` y `MD5.txt`; versiones viejas a `VIDEOS MALOS` con `MOVER_VIDEOS_MALOS.bat`.
- **No narrar la producción en el chat:** trabajar en silencio y mandar un único mensaje final corto (resultado, archivos, fecha de corte, lo que le toca a ella). Textos largos siempre en `.md`.
