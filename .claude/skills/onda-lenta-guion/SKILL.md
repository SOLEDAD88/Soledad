---
name: onda-lenta-guion
description: Escribe, revisa o audita guiones para el canal de YouTube «Onda lenta» (psicología y neurociencia en español neutro). Úsala cuando se pida un guion, hook, bloque, título, miniatura o auditoría de fuentes de ese canal.
---

# Guion para Onda lenta

Lee primero `channels/onda-lenta/CLAUDE.md`: identidad, tono, marca y reglas de exactitud. Esta skill cubre solo el proceso del guion.

## Proceso
1. **Tema y promesa.** Título concreto y comprobable (45–60 caracteres). El número del título coincide con lo narrado.
2. **Fuentes antes que texto.** Solo artículos revisados por pares u organismos oficiales (PubMed/PMC, la revista, EFSA, AASM, OMS, APA…). Nada de Wikipedia ni prensa. Si una fuente no se puede abrir, el dato es **SIN VERIFICAR** y no entra.
3. **Redactar** con la estructura `HOOK → B1 → B2 → B3 → RE-HOOK → B4 → B5 → B6 → CIERRE`, 9–11 min (≈1 400–1 700 palabras).
4. **Auditoría independiente** antes de producir (agente que no ve las conclusiones): por frase, CONFIRMADA / CON MATIZ / CONTRADICHA / SIN VERIFICAR, prioridad y texto de reemplazo. Corregir lo obligatorio y lo recomendado. Guardar el informe sin cambios en `auditorias/` con tabla de resolución.
5. **Datos de subida** (`video-NN/datos-de-subida.md`) solo con el guion definitivo.

## Estructura
| Elemento | Regla |
|---|---|
| Hook (30–40 s) | Escena concreta + promesa + bucle abierto. Sin introducción. La última frase nunca anuncia algo pequeño. |
| B1 | El dato más sorprendente, no el más reconocible. |
| Bloques | 60–90 s. Sensación primero, nombre después. Autores, año, revista, qué midieron, qué salió, qué es hipótesis. |
| Re-hook | Hacia la mitad, 10 s, paleta más fría. |
| Participación | Nunca antes del minuto 3. Un solo CTA en todo el vídeo. |
| Cierre | Tesis que une los bloques + aviso de cuidado si procede + una pregunta para comentarios. Sin datos nuevos. Cierra el bucle del hook. |
| Opcional | Marcar un bloque recortable sin romper el hilo. |

## Formato del documento
- Cada bloque lleva una caja `[V] MONTAJE` (no se locuta): **Planos** (4–5 tomas en orden), **EN PANTALLA** (rótulo literal y momento), **DÓNDE BUSCAR** (términos exactos para Pexels), **NO USES** (cliché a evitar y motivo).
- `[PAUSA]` = silencio real. Números en palabras en la locución.
- Pronunciaciones de nombres extranjeros decididas antes de grabar, solo en el texto de locución.
- Termina con la **tabla de FUENTES** (✅ / ⚠️ / 🔎) y una **nota de observaciones** para Daihana.

## Redacción
- Español neutro hispanoamericano, segunda persona, frases cortas.
- El verbo del guion nunca es más fuerte que el de los autores. Correlación ≠ causa. Mismo denominador que la fuente.
- Sin «lo curioso es que», sin dobles negaciones ni cadenas de tres negaciones, sin patrones calcados entre bloques.
- Cierre y re-hook solo resumen lo ya narrado.
- Si el tema toca ansiedad, duelo, desrealización o insomnio: una frase de cuidado, sin consejo clínico ni dosis.

## Después de producir
Auditar voz contra guion, imágenes contra narración y técnica (−14 LUFS, pico ≤ −1 dBTP, audio = vídeo, sin negros ni congelados), y hacer una pasada delta con auditor nuevo tras cualquier arreglo.

## Antes de gastar
Avisar del coste en créditos de ElevenLabs y esperar el visto bueno. La voz oficial no se cambia (ver el manual del canal).
