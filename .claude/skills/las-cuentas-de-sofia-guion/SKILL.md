---
name: las-cuentas-de-sofia-guion
description: Escribe, audita o prepara los datos de YouTube de un vídeo del canal «Las cuentas de Sofía» (finanzas explicadas con dibujos, español de España, secciones Casos, Lo básico sin prisa y AL DÍA). Úsala para guiones, rótulos, prompts de imagen de Sofía y datos-youtube.
---

# Guion para Las cuentas de Sofía

Lee primero `channels/las-cuentas-de-sofia/CLAUDE.md`; el detalle y un guion de ejemplo están en `manual-completo.md`. **No produzcas nada sin el ok de Daihana.**

## Proceso
1. **Sección** (lunes Casos, miércoles Lo básico, viernes AL DÍA) y tema acordado con Daihana. Fecha de corte = fecha de investigación.
2. **Investigación solo en fuentes oficiales** (BOE, CENDOJ, Banco de España, CNMV, INE, ministerios, UE). Nunca prensa. Cifras clave cotejadas en dos páginas cuando se pueda.
3. **Guion** con cabecera (canal, lista y número, narradora, tema, público, fecha de corte, duración, estilo, fuentes, neutralidad, 3 títulos ≤≈60 caracteres) y escenas `[ESCENA: …]` tras cada párrafo.
4. **Estructura nueva:** hook → información valiosa directa → rehook a mitad → partes numeradas → CTA a mitad → resumen → cierre fijo (CTA, aviso de voz, tarjeta FUENTES, tarjeta final).
5. **Auditoría del guion** con dos auditores independientes hasta 0 ALTA. Informe a `auditoria-*.md`.
6. Con el ok de Daihana: voz, imágenes (Sofía fiel a la referencia), alineado, mezcla, render, auditoría del MP4 y comprobación de los fotogramas cambiados.

## Reglas de redacción
- Español de España, frases cortas, una idea por frase, palabras de la calle.
- Hook: hecho vivo y sorprendente; una sola cifra limpia al principio; sin fechas, horas ni salvedades jurídicas en la primera frase; la pregunta antes del segundo 25–30.
- **Prohibido en los primeros minutos:** reglas del juego, fuentes, fecha de corte y aviso de «no es asesoramiento».
- Sin la fórmula de la edad. **Nunca mencionar IA** en voz, rótulos ni descripción.
- Plan ≠ hecho; una cifra por rótulo con fecha, magnitud y fuente; mismo sujeto y verbo que la voz.
- Sin nombres de personas ni entidades salvo lo imprescindible; presunción de inocencia.
- «Lo básico»: 55+, ritmo pausado, letra grande, sin jerga, sin tratar como a un niño.

## Prompts de imagen
Usar el prefijo de estilo, «Every person is…» y «16:9 scene:». Si sale Sofía, incluir **íntegro** el texto obligatorio de `manual-completo.md` §16.1 y `connect_from` = nodo `XVU64QHIPdEh3UOkH9UV`. Texto dentro de la imagen siempre en español y palabra por palabra; calendarios como cuadrícula vacía.

## Datos de YouTube (`datos-youtube-<vídeo>.md`)
Títulos propuestos, descripción (gancho, capítulos con hora real sin capítulo de reglas, fuentes con enlaces, fecha de corte, aviso, próximo vídeo, hashtags), etiquetas, casillas (no niños; sintético **No**), **lista de reproducción con número**, **pantalla final** (inicio = duración − 15 s) con minuto de FUENTES, comentario fijado, miniatura y duración real. Comprobar estos puntos antes de entregar.

## Entrega
Un único mensaje final corto: resultado, archivos y dónde están, fecha de corte y lo que le toca a Daihana. Sin narrar pasos.
