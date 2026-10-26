---
name: penny-drops-guion
description: Escribe, audita o prepara la publicación de un vídeo del canal de YouTube «Penny Drops TV» (historias de dinero explicadas con palitos, en inglés de EE. UU., narradora Penny). Úsala para guiones, constantes de personajes, rótulos, títulos, miniaturas y paquetes de YouTube de ese canal.
---

# Guion para Penny Drops TV

Lee primero `channels/penny-drops/CLAUDE.md`; el detalle y un guion completo de ejemplo (SVB) están en `manual-completo.md`.

## Proceso
1. **Tema.** Caso real y documentado; si es muy sensible al tiempo, a final de cola. No repetir historias de Las cuentas de Sofía.
2. **Investigación** con subagentes, solo fuentes oficiales. Nunca prensa ni Wikipedia como evidencia.
3. **Guion en un solo `.md`:** cabecera (`Title`, `Alt title`, `Thumbnail`, `Playlist`, `Voices`, reglas de rótulos, moneda y atribución) → **Personajes y objetos constantes** → **Fuentes** con URL oficial → cuerpo → versión en español (no se graba) → notas de control (duración estimada, qué se omitió y por qué).
4. **Cuerpo:** `## Cold open`, `## Act 1…4`, `## Penny's Playbook`. Cada bloque: `**n** [escena con constantes; caption "…"]` y debajo `PENNY: …`. Marcadores `[CARD: …]`, `**CTA1**`, `**CTA2**`, `[End screen: …]`. Entre 45 y 85 bloques.
5. **Voz:** cifras en letra; en el rótulo, en dígitos. Decidir antes cómo se escriben nombres y siglas difíciles.
6. **Revisión:** al menos dos repasos independientes antes de enseñarlo; la fórmula «explained simply» solo una vez; frases vecinas revisadas.
7. **Auditoría previa** (un auditor por protagonista + uno editorial/legal). Aplicar obligatorias y recomendadas; anotar lo no aplicado.
8. **Visto bueno de Daihana** al texto y al coste. Luego `estimate_only` y aprobación expresa antes de generar nada.

## No negociable
- Todo en dólares; fechas dentro de la frase; atribución en cada afirmación.
- Etiquetas: Dramatization, IMAGINED EXAMPLE, Read from the …
- Personas con nombre: descripciones literales reutilizadas; personajes genéricos, sin aspecto famoso.
- Rótulos, cifras y fechas nunca dentro del dibujo.
- Música y efectos de la biblioteca de Sofía; sin sonidos de transición.
- Duración ≈15 min; decirla siempre.

## Entregables
Vídeo en partes + `UNIR_VIDEO.bat`, `.srt`, miniaturas JPG individuales, `Penny_NN_<Caso>_YOUTUBE.md` (título, alternativo, miniatura, lista, hueco, descripción, etiquetas, comentario fijado y ajustes), informe de auditoría corto en español.
