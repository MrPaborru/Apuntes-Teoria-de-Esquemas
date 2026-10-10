# Apuntes de Teoría de Esquemas

Proyecto LaTeX basado en la plantilla de los apuntes de Homotopía Estable. Cada capítulo corresponde a una sesión del profesor. Como regla general, sus partes se agregan completas en orden. La sesión 7 queda pendiente de una unificación coherente cuando estén disponibles todos sus materiales y el usuario la solicite; para ese trabajo se permite apartarse de la estructura estricta de los esqueletos.

Las reglas permanentes del proyecto están en [AGENTS.md](AGENTS.md). Las carpetas auxiliares `tmp/` y `docs/criterios/` son locales y están excluidas de Git.

## Compilación

Desde la raíz del proyecto, ejecuta `latexmk -pdf`. Los archivos auxiliares y el documento compilado se guardan en `build/`; la salida principal es `build/main.pdf`.

## Alcance de los materiales recibidos

El programa académico enumera 24 sesiones. En `Recursos` se recibieron el programa, la introducción de la Sesión 0 y materiales de clase hasta la Sesión 7.c. Las sesiones 0–7 tienen apuntes desarrollados; las sesiones pendientes no se incluyen en el documento compilado. `NumClases` cuenta las sesiones numeradas actualmente apuntadas, excluyendo la introducción: su valor actual es 7.
