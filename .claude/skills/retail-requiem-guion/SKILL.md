---
name: retail-requiem-guion
description: Escribe, audita o prepara la publicación de un vídeo del canal de YouTube «Retail Requiem» (auge y caída de marcas de EE. UU. como documental, en inglés, voz de Fish Audio). Úsala para guiones con fuentes [S#], planos ilustrados, auditorías, títulos, miniaturas y paquetes de publicación de ese canal.
---

# Guion para Retail Requiem

Lee primero `channels/retail-requiem/CLAUDE.md`; el detalle, un guion completo (Red Lobster) y el protocolo de auditoría están en `manual-completo.md`.

## Proceso
1. **Marca.** Con datos de demanda de YouTube: marcas con pocos vídeos largos y algo de actualidad. Título con la fórmula «Why X Went Bankrupt (…)».
2. **Investigación en fuentes primarias:** memorias anuales, presentaciones ante la SEC, expedientes judiciales, notas de la época. Todas abiertas y leídas.
3. **Guion** en un archivo con `### BLOQUE NN` y marcas `{clave}` / `{~clave}`. El generador produce el guion con [S#] (el que se audita), la narración limpia (se graba y se subtitula) y la lista de fuentes. Versión en español para Daihana.
4. **Estructura:** gancho → orígenes → máximo y giro → decisiones clave → fuga de caja → quiebra → después → litigios (si los hay) → cierre «¿Qué la mató?» con la llamada a comentar y suscribirse integrada (desde el vídeo 4).
5. **Nombres difíciles:** decidir la grafía para la voz antes de grabar y usarla igual en todas las menciones.
6. **Auditoría previa** con dos auditores independientes; corregir obligatorias y recomendadas; guion EN/ES y fuentes actualizados **antes** de grabar.
7. Producción, auditoría posterior (voz con Whisper y Parakeet, imágenes en fotogramas del MP4 final, técnica) y pasada delta.

## Reglas de redacción
- Primera persona, sereno, frases cortas, sin adjetivos de escándalo.
- Cada cifra atribuida a su origen; cálculos propios marcados `[calc: …]`.
- Acusación = acusación, y a continuación la defensa. Admitir cuando las pruebas se acaban.
- Nunca pedir al espectador que corrija cifras.
- Cifras grandes en palabras para la voz; dólares como «dollars».

## Prompts de imagen
Texto de estilo fijo del manual §9 + escena concreta con época y colores por rol (azul protagonista, naranja los demás, gris pizarra neutros). Sin texto, logos, rostros ni crustáceos en fachadas. Medir proporciones de gráficos contra el dato.

## Antes de gastar
Presupuesto de créditos de Fish (2 500–2 800 por minuto) y aviso a Daihana. Un reintento de imagen cuesta créditos: solo los señalados por la auditoría.

## Publicación
Paquete: títulos, descripción con capítulos y fuentes principales, comentarios con la lista completa de fuentes, SRT propio, miniaturas A/B/C, pie fijo, «Uso de IA = No». Programar para el sábado 7:00 de Nueva York solo con Daihana presente.
