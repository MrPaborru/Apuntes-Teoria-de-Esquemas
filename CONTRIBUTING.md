# Cómo colaborar

Puedes colaborar señalando una errata, aclarando un argumento o proponiendo una corrección de las fuentes LaTeX.

## Reportar una errata

Usa la plantilla [Errata matemática o de edición](https://github.com/MrPaborru/Apuntes-Teoria-de-Esquemas/issues/new?template=errata.yml). Incluye:

- La sesión y la página del PDF, o el archivo y la etiqueta del entorno.
- El fragmento afectado y una explicación del problema.
- Una corrección o referencia que permita revisarlo, si la tienes.
- El commit o la fecha de la versión que estás leyendo.

Para problemas al generar el PDF, utiliza la plantilla [Problema de compilación](https://github.com/MrPaborru/Apuntes-Teoria-de-Esquemas/issues/new?template=compilacion.yml). Adjunta solo las líneas relevantes del registro.

## Proponer cambios

1. Crea una copia del repositorio mediante un fork y una rama para tu corrección.
2. Modifica las fuentes `.tex` correspondientes y conserva los cambios centrados en un mismo asunto.
3. Si modificas LaTeX, compila desde la raíz con `latexmk -pdf main.tex` y revisa las páginas afectadas.
4. Envía una pull request explicando qué corriges, por qué y qué páginas cambian. Si solo editas documentación, no es necesario regenerar el PDF.

## Criterios de edición

- Conserva la notación del curso y la estructura de los esqueletos para los contenidos distintos. Integra los detalles complementarios de una clase en el argumento al que pertenecen.
- Mantén todos los resultados, advertencias, ejemplos y diagramas distintos. Reúne los recordatorios repetidos sin perder sus precisiones.
- Conserva las etiquetas existentes. Todo entorno numerado nuevo lleva inmediatamente una etiqueta descriptiva, como `\label{prop:nombre}`.
- Usa `\cref`, `\myref` o `\abvref` para las referencias internas.
- Para conjuntos explícitos usa `\set{...}` o `\set*{...}`, con `\given` cuando corresponda.
- Mantén los estilos aprobados, evita que se partan las fórmulas en línea y cuida los finales de párrafo.
- Conserva los ejercicios y las pistas de las fuentes. Solo incluye una solución en los apuntes cuando el profesor la haya desarrollado en clase; las soluciones de tareas tienen su propio repositorio.
- No incluyas registros de compilación, auxiliares, archivos del editor ni imágenes temporales de revisión. Los materiales de clase y el PDF publicado sí forman parte del repositorio.

Las instrucciones de mantenimiento completas están en [AGENTS.md](AGENTS.md).
