# Instrucciones permanentes del proyecto

Estas pautas son la base del proyecto y se aplican a toda incorporación o corrección futura. Si están disponibles, consultar también las copias locales de los prompts íntegros en `docs/criterios/`: `01-prompt-inicial.md`, `02-fidelidad-estructural.md` y `03-incorporacion-secuencial.md`. Esa carpeta es auxiliar y no se versiona; este archivo conserva las reglas permanentes. En conflictos, prevalecen las instrucciones posteriores del usuario y las indicaciones vigentes de la conversación.

## Fuentes y estructura

- Programa académico: organización general del curso. Esqueletos: documento maestro literal de estructura y contenido. Presentaciones y anotaciones: desarrollos dentro de esa estructura. Completar solo los huecos seguros del argumento del profesor.
- Antes de redactar, inspeccionar todos los materiales relevantes y su correspondencia cronológica. Conservar la plantilla de Homotopía Estable ya adaptada, sus paquetes, comandos y estilo; no reinventarla.
- Conservar los títulos, el orden y todos los contenidos distintos de los esqueletos: resultados, observaciones, advertencias, fórmulas, diagramas, referencias y ejercicios. Mantener el tipo y el título de cada entorno distinto. Cuando las partes de una sesión retomen el mismo contenido para completarlo, aplicar la integración cohesiva descrita abajo y reunir los recordatorios repetidos con el resultado correspondiente.
- Cada capítulo corresponde a una sesión, con el título del profesor, sin fechas como título. La sesión 0 funciona como introducción general.
- Las letras a, b, c, etc. distinguen clases que forman una misma sesión. Leer sus materiales completos antes de integrar una parte nueva. Si esta retoma, corrige o desarrolla lo anterior, incorporar los detalles donde completan el argumento y unificar las repeticiones. Agregar al final solo los temas que realmente continúan la exposición. La numeración y la lectura deben ser continuas, sin rastros de una concatenación de clases.
- Mantener numeración automática continua dentro de la sesión: no reiniciar contadores entre partes. Los títulos internos explícitos del esqueleto se conservan, aunque mencionen una parte previa.
- Preservar el trabajo previo correcto. Modificarlo solo por una omisión, título distinto, cambio importante de orden, error real o desarrollo relevante ausente. No sustituir formulaciones ni pruebas correctas por alternativas propias.
- Usar la notación, convenciones, orden y argumentos del profesor. No añadir teoría externa, resultados nuevos ni adelantar contenido, salvo ampliaciones que el usuario autorice expresamente. Cuando proporcione lecturas complementarias y pida seleccionar contenido útil, incorporar solo lo pertinente a los temas tratados, identificarlo como complemento y citar su procedencia. Integrar los desarrollos del Beamer dentro de las secciones del esqueleto, sin crear una estructura paralela.
- El cotejo de las presentaciones incluye las construcciones y explicaciones que preparan las demostraciones, aunque no aparezcan como entornos numerados en el esqueleto. Antes de usar un morfismo canónico, dejar explícita su construcción o remitir mediante los comandos del proyecto a donde se haya definido.
- Conservar ejercicios y pistas de las fuentes, SIN resolverlos ni añadir pistas propias. Solo reproducir una solución cuando las fuentes documenten que el profesor la desarrolló como exposición.

## Integración cohesiva de las partes de una sesión

Al incorporar S8b, el usuario extendió la pauta de integración cohesiva a las clases futuras que completen detalles de una misma sesión. Esta indicación prevalece sobre la antigua concatenación literal de partes. Conservar todos los contenidos matemáticos distintos, ejemplos, correcciones, ejercicios, pistas y diagramas; enunciar una sola vez los resultados repetidos y reunir sus demostraciones y desarrollos complementarios. Mantener las etiquetas existentes y las referencias automáticas al reorganizar.

La sesión 7 conserva su exposición unificada de 7a, 7b y 7c y la demostración del Lema de Pegado en cinco pasos. En la sesión 8, la clase 8a se detuvo antes de comenzar la recta proyectiva (apartado 8.3), y 8b completó los detalles previos y llegó a probar la no afinidad de la recta proyectiva. La clase 8c precisa las correcciones anteriores y desarrolla los puntos y fibras de la recta proyectiva, la clasificación sobre Z, los DVR y la reducción, además de completar los otros pegados. Estos desarrollos se reúnen en sus apartados correspondientes, sin repetir los recordatorios. Los materiales posteriores que ya estaban incorporados se conservan.

La clase 8d completa la maximalidad y los dos generadores de los primos de Z[t], el mapa de Mumford, la curva V(t²+1), la intersección de secciones y dos ejercicios nuevos. Estos contenidos se integran en los apartados existentes. A petición del usuario se incorporan, como lecturas complementarias citadas, la interpretación de los dibujos de Le Bruyn y las fibras p-ádicas de Serratos. Añadir una parte de la sesión 8 conserva NumClases = 8.

## LaTeX y edición

- Español matemático compacto y claro; reproducir todos los diagramas y dibujos matemáticos de las presentaciones, así como las tablas de las fuentes. La fidelidad a los títulos del esqueleto prevalece sobre reducir la cantidad de secciones.
- Cada entorno numerado debe tener inmediatamente un `\\label{entorno:etiqueta-descriptiva}`, único y consistente. Las referencias posteriores usan `\\cref`, `\\myref` (incluye nombre) o `\\abvref`; no escribir tipo/número manualmente ni usar `\\ref` sin una razón específica.
- Para conjuntos explícitos usar `\\set{...}` o `\\set*{...}`, con `\\given` cuando corresponda; no usar llaves y barras manuales para sustituir estos comandos.
- Evitar finales de párrafo de apenas palabras cortas mediante ajustes mínimos de redacción. Las fórmulas inline no deben partirse entre líneas. Conservar los ajustes editoriales del proyecto.
- `NumClases` cuenta únicamente las sesiones numeradas actualmente apuntadas: la introducción o sesión 0 NO cuenta. Con las sesiones 1 a 8 desarrolladas, su valor es 8. Actualizar al añadir una nueva sesión; añadir una parte a una sesión existente no incrementa el total. Las sesiones pendientes no aparecen en el documento.
- Conservar los estilos aprobados de portada, TOC, Introducción, referencias y ejercicios; no cambiarlos para incorporar contenido.

## Revisión y entrega

- Toda carpeta auxiliar creada por el asistente (temporales, extracciones, imágenes de revisión o copias de prompts) debe tener una entrada específica en `.gitignore`. Si ya estaba versionada, retirarla del índice conservando los archivos locales. No ignorar fuentes, recursos del profesor ni otros archivos útiles del proyecto. `AGENTS.md` se conserva versionado para mantener estas instrucciones.

- Cotejar secciones, títulos, orden, TODOS los resultados, fórmulas, diagramas, pruebas y ejercicios con cada esqueleto correspondiente. Reconstruir desarrollos de clase con las presentaciones. Al unificar partes, distinguir un recordatorio repetido de un contenido nuevo y comprobar que ningún contenido distinto se pierda.
- Compilar con `latexmk -pdf`; salida en `build/main.pdf`. Corregir errores y referencias indefinidas; revisar visualmente las páginas modificadas.
- Al terminar cada trabajo, generar un commit para GitHub con título descriptivo y cuerpo bien comentado: motivo, cambios concretos y comprobaciones realizadas. Incluir solo los archivos del trabajo; no incorporar modificaciones ajenas. No subir a GitHub sin autorización para publicar; la instrucción de commit autoriza el commit local.
