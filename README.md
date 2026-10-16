# Apuntes de Teoría de Esquemas

Proyecto LaTeX basado en la plantilla de los apuntes de Homotopía Estable. Cada capítulo corresponde a una sesión del profesor. Sus clases a, b, c, etc. se integran cohesivamente cuando retoman y completan argumentos anteriores: los recordatorios se reúnen en un solo enunciado y se conservan todos los contenidos, ejemplos, ejercicios y diagramas distintos. La sesión 7 unifica 7a, 7b y 7c con una demostración continua del Lema de Pegado en cinco pasos; la sesión 8 integra los detalles complementarios de 8a y 8b.

Las reglas permanentes del proyecto están en [AGENTS.md](AGENTS.md). Las carpetas auxiliares `tmp/` y `docs/criterios/` son locales y están excluidas de Git.

## Compilación

Desde la raíz del proyecto, ejecuta `latexmk -pdf`. Los archivos auxiliares y el documento compilado se guardan en `build/`; la salida principal es `build/main.pdf`.

## Alcance de los materiales recibidos

El programa académico enumera 24 sesiones. En `Recursos` se recibieron el programa, la introducción de la Sesión 0 y materiales de clase hasta la Sesión 8b. Las sesiones 0–8 tienen apuntes desarrollados; las sesiones pendientes no se incluyen en el documento compilado. `NumClases` cuenta las sesiones numeradas actualmente apuntadas, excluyendo la introducción: su valor actual es 8.

La Sesión 8, «Ejemplos globales», conserva ocho secciones principales. El apartado del plano menos el origen integra la definición del morfismo canónico, su verificación en cuatro pasos desarrollada en clase, la propiedad universal, la naturalidad y el criterio de afinidad. Las ampliaciones de 8b completan también la construcción por pegado y la prueba de no afinidad de la recta proyectiva. Se conservan los contenidos posteriores ya apuntados, la tabla sobre los enteros y todos los dibujos y diagramas de ambas presentaciones. La lista final contiene seis ejercicios; la verificación del morfismo canónico aparece junto a su definición.
