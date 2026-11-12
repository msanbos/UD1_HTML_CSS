# Prompt de cierre

Hemos terminado el proyecto. Quiero que generes el archivo CONVERSACION.md con el
registro completo, literal y transparente de todo el proceso de desarrollo, según el
Protocolo Asimov y AGENTS.md. Lo revisará mi docente, así que debe ser fiel, completo
y verificable.

DATOS QUE APORTO (rellenados por mí)
- Alumno/a: [nombre o identificador]
- Proyecto: [título]
- Sesiones (fecha y hora aproximada de inicio y fin, zona Europe/Madrid):
  1) [AAAA-MM-DD, HH:MM a HH:MM]
  2) [...]
- ¿He editado, regenerado o borrado mensajes durante el proyecto? [No / Sí: explica qué]
- ¿He usado otras IA, foros u otras personas para este proyecto? [No / Sí: cuáles]
- ¿Hubo conversaciones anteriores de este mismo proyecto? [No / Sí: las adjunto o pego
  al final como exportación nativa]

REGLAS DE GENERACIÓN (obligatorias)

1. Literalidad. Reproduce TODOS los mensajes, los míos y los tuyos, tal cual: sin
   resumir, parafrasear, corregir, traducir, reordenar ni omitir. No uses puntos
   suspensivos ni marcas como "[código omitido]" en lugar de contenido. Conserva el
   código en bloques de código con indicación del lenguaje. Si un bloque contiene
   tres acentos graves seguidos, usa una valla de cuatro.
2. Totalidad. Incluye toda la conversación, desde el primer mensaje (el del prompt
   inicial y AGENTS.md) hasta este prompt de cierre, incluido tu resumen de reglas.
3. Numeración y roles. Numera todos los mensajes de forma correlativa y continua
   (001, 002, 003...) en todo el archivo y etiqueta cada uno como ALUMNO o IA.
4. Fechas y horas. Agrupa por fechas: cada día es una subsección (### AAAA-MM-DD).
   Cada mensaje lleva su hora aproximada en zona Europe/Madrid (24 h) con el prefijo
   "~". Usa solo horas que provengan de (a) marcas de tiempo visibles en la
   conversación o en la exportación, o (b) las que he declarado arriba. Si tienes que
   estimar una hora, márcala con "(est.)". Nunca presentes una estimación como hora
   exacta ni inventes marcas de tiempo.
5. Archivos adjuntos. Indica el nombre exacto, con extensión, de cada archivo
   adjuntado, tanto (a) en la sección inicial de documentos como (b) en el mensaje
   concreto en que se adjuntó, con la línea "[Adjunto: nombre.ext]". Indica también
   los archivos que hayas generado o entregado tú. No inventes nombres: si no
   conoces el de un adjunto, escribe [NOMBRE NO DISPONIBLE]. No reproduzcas el
   contenido de los adjuntos salvo que estuviera pegado como texto en el mensaje.
6. Lo no disponible. Si no puedes acceder a una parte de la conversación (límite de
   contexto, truncado u otra causa), no la reconstruyas ni la inventes: escribe
   [NO DISPONIBLE: motivo] en su lugar, avísame ANTES de entregar el archivo y
   pídeme la exportación nativa del chat para completarla.
7. Varios chats. Si te aporto conversaciones anteriores, intégralas en orden
   cronológico en la sección 3, indica el chat de origen en el encabezado de cada día
   ("Chat 1", "Chat 2"...), marca sus mensajes con [ORIGEN: exportación del alumno] y
   mantén la numeración correlativa en todo el archivo.
8. Sin añadidos. No evalúes, comentes ni embellezcas. Lo único que añades es la
   estructura indicada y la verificación final. Tu respuesta con este archivo no se
   incluye como mensaje.
9. Longitud. Si no cabe en una respuesta, divídelo en partes numeradas ("PARTE 1 de
   N") sin perder ni repetir contenido, y termina cada parte con [CONTINÚA] salvo la
   última. Si puedes crear un archivo descargable, hazlo y llámalo exactamente
   CONVERSACION.md.

ESTRUCTURA OBLIGATORIA DE CONVERSACION.md

# CONVERSACION.md

## 0. Metadatos
- Alumno, proyecto, IA y modelo (si lo sabes; si no, "no indicado"), fecha de
  generación, zona horaria Europe/Madrid, número de sesiones, total de mensajes
  (ALUMNO / IA) y título o versión de AGENTS.md.
- Declaraciones del alumno (las de arriba, literales).

## 1. Prompt utilizado para generar este archivo
- Este mismo mensaje, íntegro y literal, en un bloque de código.

## 2. Documentos
- Tabla con: no | nombre exacto | tipo | quién lo aportó (ALUMNO/IA) | fecha y
  hora aprox. | mensaje no donde aparece | descripción breve y neutra.
- Incluye AGENTS.md y todos los archivos adjuntados o generados en el proceso. Si
  no hubo otros, indícalo.

## 3. Conversación

### AAAA-MM-DD

#### Mensaje 001 - ALUMNO - ~HH:MM
(texto literal)
[Adjunto: nombre.ext]

#### Mensaje 002 - IA - ~HH:MM
(texto literal)

(Repite por cada mensaje y cada día. Este prompt de cierre figura como último
mensaje con la nota [Contenido íntegro en la sección 1].)

## 4. Verificación de integridad
- Total de mensajes registrados (ALUMNO / IA) y si coincide con la sección 0.
- Lista de partes [NO DISPONIBLE] (o "ninguna").
- Número de horas estimadas (est.) y en qué mensajes.
- Confirmación expresa: "Este archivo contiene la conversación completa y literal
  salvo lo indicado arriba". Si no puedes afirmarlo, explica por qué.

## Anexo A. AGENTS.md
- Texto íntegro y literal del AGENTS.md que te di al inicio.
