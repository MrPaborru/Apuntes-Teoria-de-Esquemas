# Instrucciones permanentes del proyecto

Estas pautas son la base del proyecto y se aplican a toda incorporación o corrección futura. Leer también los prompts íntegros conservados en `docs/criterios/`: `01-prompt-inicial.md`, `02-fidelidad-estructural.md` y `03-incorporacion-secuencial.md`. En conflictos, prevalecen las instrucciones posteriores del usuario y las indicaciones vigentes de la conversación.

## Fuentes y estructura

- Programa académico: organización general del curso. Esqueletos: documento maestro literal de estructura y contenido. Presentaciones y anotaciones: desarrollos dentro de esa estructura. Completar solo los huecos seguros del argumento del profesor.
- Antes de redactar, inspeccionar todos los materiales relevantes y su correspondencia cronológica. Conservar la plantilla de Homotopía Estable ya adaptada, sus paquetes, comandos y estilo; no reinventarla.
- Una sección/subsección del esqueleto equivale a una sección/subsección con exactamente el mismo nombre y en el mismo orden. Copiar íntegramente el contenido base, incluidos resultados, observaciones, advertencias, fórmulas, diagramas, referencias y ejercicios. Mantener el tipo y el título de cada entorno.
- Cada capítulo corresponde a una sesión, con el título del profesor, sin fechas como título. La sesión 0 funciona como introducción general.
- Las partes a, b, c, etc. de una misma sesión se concatenan completas en orden: [a completo] + [b completo] + [c completo]. Cada nueva parte se AGREGA AL FINAL de la anterior. No fusionar secciones, eliminar repeticiones del esqueleto, mover contenido previo ni reorganizar para incorporar una nueva parte.
- Mantener numeración automática continua dentro de la sesión: no reiniciar contadores entre partes. Los títulos internos explícitos del esqueleto se conservan, aunque mencionen una parte previa.
- Preservar el trabajo previo correcto. Modificarlo solo por una omisión, título distinto, cambio importante de orden, error real o desarrollo relevante ausente. No sustituir formulaciones ni pruebas correctas por alternativas propias.
- Usar la notación, convenciones, orden y argumentos del profesor. No añadir teoría externa, resultados nuevos ni adelantar contenido. Integrar los desarrollos del Beamer dentro de las secciones del esqueleto, sin crear una estructura paralela.
- Conservar ejercicios y pistas de las fuentes, SIN resolverlos ni añadir pistas propias. Solo reproducir una solución cuando las fuentes documenten que el profesor la desarrolló como exposición.

## LaTeX y edición

- Español matemático compacto y claro; reproducir diagramas relevantes. La fidelidad a los títulos del esqueleto prevalece sobre reducir la cantidad de secciones.
- Cada entorno numerado debe tener inmediatamente un `\\label{entorno:etiqueta-descriptiva}`, único y consistente. Las referencias posteriores usan `\\cref`, `\\myref` (incluye nombre) o `\\abvref`; no escribir tipo/número manualmente ni usar `\\ref` sin una razón específica.
- Para conjuntos explícitos usar `\\set{...}` o `\\set*{...}`, con `\\given` cuando corresponda; no usar llaves y barras manuales para sustituir estos comandos.
- Evitar finales de párrafo de apenas palabras cortas mediante ajustes mínimos de redacción. Las fórmulas inline no deben partirse entre líneas. Conservar los ajustes editoriales del proyecto.
- `NumClases` cuenta las sesiones actualmente apuntadas (incluida la introducción si así lo cuenta el proyecto); actualizar al añadir una nueva sesión. Añadir una parte a una sesión existente no incrementa el total. Las sesiones pendientes no aparecen en el documento.
- Conservar los estilos aprobados de portada, TOC, Introducción, referencias y ejercicios; no cambiarlos para incorporar contenido.

## Revisión y entrega

- Cotejar secciones, títulos, orden, TODOS los resultados, fórmulas, diagramas, pruebas y ejercicios con cada esqueleto correspondiente. Reconstruir desarrollos de clase con las presentaciones. Conservar las repeticiones que figuren en las fuentes.
- Compilar con `latexmk -pdf`; salida en `build/main.pdf`. Corregir errores y referencias indefinidas; revisar visualmente las páginas modificadas.
- Al terminar cada trabajo, generar un commit para GitHub con título descriptivo y cuerpo bien comentado: motivo, cambios concretos y comprobaciones realizadas. Incluir solo los archivos del trabajo; no incorporar modificaciones ajenas. No subir a GitHub sin autorización para publicar; la instrucción de commit autoriza el commit local.
