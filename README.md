# Apuntes de Teoría de Esquemas

Proyecto LaTeX basado en la plantilla de los apuntes de Homotopía Estable. Cada capítulo corresponde a una sesión del profesor. Las partes de una misma sesión se agregan completas en orden, sin fusionar sus secciones: 1.a → 1.b → 1.c y 7.a → 7.b → 7.c.

Las reglas permanentes del proyecto están en [AGENTS.md](AGENTS.md). Los prompts originales se conservan íntegros en [docs/criterios](docs/criterios).

## Compilación

Desde la raíz del proyecto, ejecuta `latexmk -pdf`. Los archivos auxiliares y el documento compilado se guardan en `build/`; la salida principal es `build/main.pdf`.

## Alcance de los materiales recibidos

El programa académico enumera 24 sesiones. En `Recursos` se recibieron el programa, la introducción de la Sesión 0 y materiales de clase hasta la Sesión 7.c. Las sesiones 0–7 tienen apuntes desarrollados; las sesiones pendientes no se incluyen en el documento compilado. `NumClases` cuenta las sesiones actualmente apuntadas.
