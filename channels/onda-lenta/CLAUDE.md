# Onda lenta — manual del canal

Versión del manual: 26 oct 2026. Fuente: proyecto de Claude «CANAL ONDA LENTA» y decisiones de Daihana.
Manual íntegro (con el guion de ejemplo del vídeo 11, las instrucciones del proyecto y el estado de los vídeos): `manual-completo.md`.

## 1. Identidad
- Handle `@onda_lenta` · ID `UCzIrxZj7j6ySaNSTNnn6dDQ` · País España.
- Tema: psicología y neurociencia divulgativa, con los estudios delante. Faceless.
- Lema: «Sin prisa y sin gritos.» Cada dato viene de una fuente comprobable; si la ciencia no está cerrada, se dice. Incluye desmontar mitos de otros canales.
- Idioma: español neutro hispanoamericano (decisión 26 oct 2026). Público de toda América, incluido el hispano de EE. UU. Sin giros de España («da igual» → «no importa»; «cíngulo» → «corteza cingulada»).
- Nombre: viene de la onda lenta del sueño profundo.
- Descripción de YouTube: «Tu cerebro tiene una onda que te limpia cada noche. Se llama onda lenta.» + aviso de que es divulgación, no consejo médico.

## 2. Marca
| Color | Hex | Uso |
|---|---|---|
| Negro | `#030200` | Fondo de banner, miniaturas y tarjetas |
| Crema | `#F7F1E3` | Onda del logo, titulares |
| Crema atenuada | `#96928A` | Lemas y texto secundario |
| Ámbar | `#F0A830` | Cifras de tarjetas, rótulo de hora y contador. Nada más. |

Poppins para logo y banner (Bold titulares, Light lemas). Banner 2560×1440, <6 MB, texto dentro de la zona segura 1235×338.

## 3. Narración
- Narradora femenina, treinta y pocos, grave y calmada, «narradora documental afilada». Segunda persona, frases cortas.
- Clínico y sereno: sin sustos, sin música dramática, sin alarmismo. Lo observado es hecho; la explicación, hipótesis, y se dice.
- Deber de cuidado: si un bloque toca ansiedad, duelo, desrealización o insomnio, una frase dice que tiene tratamiento y que no hay que gestionarlo solo. Nunca consejos clínicos ni dosis.
- Prohibido: muletillas («lo curioso es que», «honestamente»), frases repetidas entre bloques, patrones calcados, cadenas de 3 negaciones seguidas.

## 4. Formato
- Vídeo largo: **9–11 min** (≈150–175 ppm; 1 500 palabras ≈ 9,5 min). 1080p, 25 fps, H.264, AAC 192 kb/s. **−14 LUFS**, pico ≤ −1 dBTP.
- Series «hora a hora»: rótulo de hora arriba a la derecha, Inter Display Bold 64, ámbar sobre caja oscura, solo sobre clips.
- Shorts: <60 s, vertical, 3 por vídeo largo, cierre «Vídeo completo en el canal @onda_lenta». Salen del vídeo ya auditado.
- Calendario: largo martes y viernes 19:00 (España); Shorts jueves y domingo 19:00. Se suben en privado y se programan. Un día perdido se recupera en el siguiente hueco.

## 5. Guion
Estructura vigente: **HOOK → B1 → B2 → B3 → RE-HOOK → B4 → B5 → B6 → CIERRE**. Detalle y reglas de redacción en la skill `onda-lenta-guion`.

## 6. Exactitud y fuentes (resumen)
1. Solo fuentes primarias u oficiales. Prohibidos Wikipedia, prensa y divulgación.
2. Cada dato con su fuente abierta y leída; si no, **SIN VERIFICAR** y fuera del guion.
3. Auditoría independiente **antes** de producir (veredicto por frase: CONFIRMADA / CON MATIZ / CONTRADICHA / SIN VERIFICAR) y **después** (voz, imágenes, técnica), con pasada delta tras cada arreglo.
4. Tabla de fuentes: ✅ comprobado · ⚠️ hipótesis · 🔎 fuente secundaria (ninguno al publicar).
5. Nombres de científicos con nombre completo comprobado y misma ortografía en todo el guion.
6. Miles según RAE (18 330 con espacio fino; 9095 sin separador).

## 7. Estilo visual (estándar vídeo 7 v4, 16 oct 2026)
- Mezcla de clips Pexels (sin audio), fotos con movimiento lento, tarjetas de texto y rótulos. IA solo ambiente, 0–8 por vídeo, sin personas ni hechos reales.
- **60+ imágenes distintas por 10 min, máximo 2 usos cada una.** Planos de 4–10 s (media ≈6,5).
- No usar: caras reconocibles en primer plano, niños, marcas/logos/texto legible, perros, relojes digitales, cerebros de neón o azules en 3D, cámara en mano temblorosa, imágenes alarmistas, animales de laboratorio, gráficos con marca de revista.
- Clips cortos se sustituyen (nunca se congela el último fotograma); clips casi inmóviles (movimiento <0,25) también.
- Conversión a 25 fps con fundido de fotogramas; clips sin zoom (solo escalado y recorte a 1920×1080).
- Color: saturación 0,8, brillo −0,07, contraste 0,92; paleta fría en el re-hook.
- Transiciones: fundido cruzado de 1 s; tarjetas con fundido a negro de 1 s; pausa de 0,9 s entre bloques.
- Tarjeta tipo: etiqueta AUTORES · AÑO · REVISTA, cifra grande ámbar, una línea de explicación, fuente pequeña. Texto nunca fuera del encuadre (ancho útil 1700 px). Tipografía Inter / Inter Display.
- Científicos en pantalla: nombre completo; 1–2 autores con nombre y apellido; 3+ → primer autor + «Y SU EQUIPO».
- Grafías fonéticas de la locución nunca en pantalla ni subtítulos.
- Audio: de-esser 5–13 kHz, estante −3,5 dB sobre 8 kHz, paso bajo 9 kHz. Música propia de piano y cuerdas, ≈20 dB bajo la voz con ducking.

## 8. Voz y herramientas
- ElevenLabs (plan Pro compartido). Voz «VOZ CANAL PSICOLOGIA» (el nombre lleva un espacio final), `voice_id` **`ANUExybPNJLiUd0KGypp`**, modelo `eleven_v3`, speed 1.00, stability 50, similarity 75, style bajo. **No se cambia nunca. No clonar.**
- Texto para la voz: números en letra; pausas con «…» y saltos de párrafo; máximo 6 etiquetas de audio por vídeo ([calm], [slowly], [softly], [whispers]).
- Una toma por bloque; si hay corrección, otra toma solo de ese bloque. Descartar tomas que cierran frase subiendo de tono.
- Audios: `1 GUION 9 ONDA LENTA.mp3`, `2 GUION 9 ONDA LENTA.mp3`…
- **Avisar del coste en créditos antes de generar y esperar el visto bueno** (≈10 000–15 000 créditos por vídeo).
- Stock: Pexels (libre de derechos). Montaje: Python + ffmpeg propio. Miniaturas: script PIL (Anton + Noto Color Emoji). Analítica: YouTube Studio, Nexlev, vidIQ.
- Entrega: partes `.ts` de 28 MB + `UNIR_VN.bat`. Carpeta en el PC: `C:\Users\Propietario\Documents\CANAL ONDA LENTA\VIDEO NN - Título\` con `AUDIOS/`, vídeo final y `textos_youtube_videoN.txt`.
- Copia en Google Drive («ONDA LENTA — copia de seguridad») y estado en Notion.

## 9. Título y miniatura
- Título: promesa concreta y comprobable, 45–60 caracteres, neutro. El número coincide con lo narrado. Alternativas listas por si el CTR no arranca a los 3 días.
- Miniatura «rejilla de círculos»: 1280×720, fondo negro; titular en Anton, línea principal roja `#EB1C24` con contorno amarillo y resplandor naranja; etiqueta inclinada roja con texto amarillo; círculos de ≈240 px con aro cian y un fotograma del vídeo (6 bastan); último círculo grande con aro amarillo «+N Y MÁS».
- **Ninguna palabra del titular de la miniatura repite palabras del título.** Nada que el vídeo no contenga. Variante A/B preparada.

## 10. Listas de reproducción
- «Tu cerebro, hora a hora»: vídeos «hora a hora» (4 ansiedad, 9 cafeína) y largos recientes por defecto.
- «Lo que la ciencia sabe de tu cerebro»: fenómenos y estudios (vídeos 3 a 8).
- «Fenómenos mentales en un minuto»: Shorts.

## 11. Ajustes de subida (YouTube Studio)
- Visibilidad: **Privado al subir → Programar** (martes o viernes 19:00 hora de España).
- Datos desde `video-NN/datos-de-subida.md`: título, descripción (resumen, capítulos, aviso de divulgación, fuentes, «Vídeos de stock: Pexels. Música: propia.», hashtags), 15–20 etiquetas que terminan en «onda lenta», comentario fijado y ajustes.
- No es para niños · sin restricción de edad · **contenido alterado o sintético = No** (criterio fijo) · sin promoción de pago · categoría **Educación**.
- Idioma del vídeo: **Español (Latinoamérica)** (decisión 26 oct 2026). Los anteriores se subieron como «Español (España)»: pendiente de cambiar, empezando por el vídeo 9.
- Sin menciones a IA en títulos ni descripciones; solo «Algunas imágenes son ilustraciones de ambiente generadas con IA» cuando las hay.
- La miniatura la sube Daihana a mano. El comentario fijado se publica cuando el vídeo ya es público: una pregunta breve con datos auditados.
- Capítulos: uno por bloque. Pantalla final: siguiente/anterior + suscripción. Subtítulos automáticos revisados (nombres propios). A los 7 días: CTR y retención a 30 s; A/B de miniatura si el CTR es bajo.

## 12. Flujo de un vídeo
Tema → guion v1 → auditoría previa (2 auditores) → guion v2 y visto bueno → datos de subida y documento de locución → voz (aviso de coste) → lista de stock → montaje → comprobación y auditoría posterior (+ delta) → entrega al PC en partes + `.bat` → subida privada, programación y lista → comentario fijado y 3 Shorts → registro en el proyecto y en Sheets.

## 13. Trato con Daihana
Avisar del coste antes de gastar. Feedback directo citando frases concretas. No poner en el chat los pasos intermedios: avisar solo cuando algo está terminado o hace falta una decisión. Ella no compara cifras con las fuentes: lo hacen los auditores y recibe un informe en español sin jerga.

## 14. Estado de los vídeos (26 oct 2026)
Vídeos 1–8 públicos; el 9 (cafeína, hora a hora) programado el martes 27 oct 19:00; el 10 (duelo) montado para el viernes 30 oct; el 11 (Para qué dormimos) montado, siguiente martes.
