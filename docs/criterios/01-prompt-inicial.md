Quiero que construyas desde cero mis apuntes de **Teoría de Esquemas**, trabajando directamente sobre la carpeta:

`D:\Github\Apuntes Teoría de Esquemas`

Ya tienes permiso para modificar y crear archivos dentro de esta carpeta.

El proyecto actualmente solo contiene una carpeta llamada `recursos`. **No empieces a construir los apuntes desde una plantilla genérica**: quiero que utilices como plantilla mi proyecto anterior de apuntes de Homotopía Estable:

`D:\Github\Apuntes-Homotop-a-Estable`

Ese proyecto ya contiene la estructura que quiero para mis apuntes: portada, configuración de LaTeX, paquetes, comandos, ambientes, índice, formato de capítulos, estilos, etc. Puedes copiar directamente esa estructura y adaptarla al nuevo curso.

Modifica únicamente lo que sea necesario para Teoría de Esquemas, por ejemplo:

- nombre de la materia;
- nombre del profesor;
- información de la portada;
- notación;
- comandos específicos;
- ambientes que sean necesarios;
- cualquier otro detalle particular del curso.

**No quiero que reinventes el formato si ya existe una solución en mi plantilla de Homotopía Estable.**

---

# 1. PRIMERO INSPECCIONA TODO; DESPUÉS ESCRIBE

Antes de comenzar a redactar cualquier capítulo, quiero que hagas una **fase de inspección global de todo el proyecto**.

No empieces a escribir los apuntes después de leer solamente el primer PDF.

Primero debes:

1. leer el programa académico completo;
2. inspeccionar todos los archivos relevantes de `Esqueletos`;
3. inspeccionar todos los archivos relevantes de `Presentaciones`;
4. identificar cómo se corresponden entre sí las sesiones, incluyendo subdivisiones como `1.a`, `1.b`, etc.;
5. determinar el orden cronológico de las sesiones;
6. identificar los títulos que el profesor asigna a cada sesión;
7. inspeccionar la estructura de mi proyecto de Homotopía Estable;
8. entender cómo están organizados sus archivos `.tex`, portada, índice, paquetes, comandos y ambientes;
9. determinar qué elementos de esa plantilla deben conservarse y cuáles deben adaptarse para Teoría de Esquemas.

**No necesito que me informes de cada uno de estos pasos ni que me pidas confirmación.**

Haz esta inspección completa primero y, una vez que hayas entendido la estructura del curso y la plantilla, construye el proyecto completo.

No quiero un flujo en el que termines una sesión, me preguntes qué hacer y después continúes con la siguiente. **Quiero que construyas todo el proyecto de una sola vez**, utilizando la información obtenida durante esta inspección inicial.

Una vez terminado el proyecto, realiza una revisión global para detectar omisiones o inconsistencias.

---

# 2. Recursos del curso

Dentro de:

`D:\Github\Apuntes Teoría de Esquemas\recursos`

hay un PDF con el **programa académico completo del curso**.

Debes leerlo primero.

Úsalo para comprender:

- la estructura general del curso;
- los temas;
- la organización por sesiones;
- el orden general de los contenidos.

Además, dentro de `recursos` existen dos carpetas:

- `Esqueletos`
- `Presentaciones`

Debes inspeccionar ambas.

---

# 3. Esqueletos: fuente principal

La carpeta `Esqueletos` contiene PDFs elaborados por el profesor. Son los **bocetos de lo desarrollado en clase**: contienen la estructura, resultados, definiciones, argumentos, fórmulas, etc., pero deliberadamente dejan sin desarrollar buena parte de los detalles.

Estos documentos deben ser tu **fuente principal para estructurar los apuntes**.

Quiero que reconstruyas cada sesión siguiendo la organización y el hilo argumental que aparece en estos esqueletos.

No sustituyas la estructura del profesor por una estructura propia simplemente porque te parezca más pedagógica.

Si el profesor presenta:

1. una definición;
2. una construcción;
3. una proposición;
4. un ejemplo;
5. una demostración;

quiero que los apuntes mantengan esencialmente ese mismo orden.

Tu trabajo consiste en **desarrollar y escribir los huecos**, no en rediseñar la clase.

---

# 4. Presentaciones: material complementario

La carpeta `Presentaciones` contiene los **Beamer que el profesor utilizó durante las clases**.

Es importante que entiendas que estos archivos **no son pizarras ni transcripciones completas de las clases**. Son las presentaciones que el profesor utilizó como material de apoyo.

Por tanto, deben utilizarse como **material complementario** para desarrollar y completar los esqueletos.

Pueden servir para recuperar:

- definiciones;
- resultados;
- argumentos;
- ejemplos;
- fórmulas;
- cálculos;
- diagramas;
- explicaciones;
- detalles técnicos;
- referencias;
- cualquier otro contenido que ayude a reconstruir lo desarrollado en clase.

En algunos casos, el profesor **escribe o hace anotaciones directamente sobre las diapositivas durante la clase**. Estas anotaciones manuscritas son especialmente relevantes, pues pueden contener parte del desarrollo realizado durante la sesión que no aparece en el Beamer original.

Cuando existan anotaciones manuscritas, utilízalas como evidencia del desarrollo realizado en clase y, cuando correspondan a un punto del esqueleto, intégralas en los apuntes.

Sin embargo, **no debes asumir que todo lo que aparece en las presentaciones fue desarrollado con el mismo nivel de detalle durante la clase**. Los Beamers son material de apoyo, mientras que los esqueletos proporcionan la estructura principal de lo que debe quedar en los apuntes.

La jerarquía general de las fuentes debe ser:

**programa académico → estructura general del curso**

**esqueletos → estructura principal y contenido que debe reconstruirse**

**Beamers → material complementario para desarrollar y completar los esqueletos**

Si aparece información adicional en un Beamer que no está reflejada en el esqueleto, no la conviertas automáticamente en una sección nueva. Determina primero si sirve para completar, aclarar o justificar algún punto de la estructura que ya está presente.

El objetivo es reconstruir **lo que realmente se desarrolló en el curso**, no convertir los Beamers en el contenido principal de los apuntes.

---

# 5. Fidelidad al profesor

Esta es una de las instrucciones más importantes.

Quiero que los apuntes sean **lo más fieles posible a los argumentos, notación y forma de presentar las matemáticas del profesor**.

No quiero que reemplaces sistemáticamente sus argumentos por demostraciones que tú consideres más elegantes, estándar o pedagógicas.

Cuando el profesor da un argumento:

1. conserva su idea;
2. conserva su orden;
3. conserva su notación;
4. conserva sus convenciones;
5. desarrolla únicamente los pasos que quedaron implícitos o demasiado comprimidos.

En otras palabras:

> **rellena los huecos argumentales, pero no rehagas la clase.**

Por ejemplo, si en el esqueleto aparece:

> definición → observación → construcción → afirmación → demostración esquemática,

quiero que el apunte conserve exactamente ese hilo y que tú desarrolles los pasos que sean necesarios para que el texto sea matemáticamente legible y autocontenido.

No cambies una demostración simplemente porque conozcas una demostración alternativa.

## Notación

Prioriza siempre la **notación del profesor**.

Si el profesor utiliza una notación particular para un objeto, morfismo, construcción, diagrama, functor, etc., utiliza esa notación aunque exista otra que sea más común en libros de texto.

Puedes crear o modificar comandos de LaTeX para que esa notación quede cómoda y consistente en todo el proyecto.

No cambies la notación únicamente para hacerla coincidir con alguna convención externa.

Si necesitas introducir una notación auxiliar para poder escribir algo que el profesor dejó implícito, hazlo de la manera más discreta posible y sin alterar la notación principal.

---

# 6. No agregar teoría externa innecesaria

Los apuntes deben representar el curso que realmente se está impartiendo.

Por ello:

- No agregues resultados importantes que no aparezcan en los materiales.
- No introduzcas teoría adicional solo porque sea útil para comprender el tema.
- No conviertas una observación breve del profesor en una sección completa de teoría externa.
- No adelantes resultados que el profesor todavía no haya introducido.
- No sustituyas el contenido del curso por una exposición general de teoría de esquemas basada en libros.

Sí puedes completar un paso argumental cuando sea necesario para que una demostración tenga sentido, pero debe tratarse de una **completación del argumento del profesor**, no de contenido nuevo.

Si en algún punto los materiales son insuficientes para determinar exactamente qué quiso decir el profesor, conserva la interpretación más fiel y evita inventar detalles.

---

# 7. Organización por SESIONES, no por clases

Hay una diferencia fundamental con mis apuntes de Homotopía Estable.

En Homotopía Estable cada capítulo corresponde a una clase. **En Teoría de Esquemas NO quiero eso.**

Aquí:

> **Cada capítulo debe corresponder a una SESIÓN del profesor.**

Una sesión puede abarcar varias clases.

Por ejemplo, si los materiales contienen:

- Sesión 1.a
- Sesión 1.b

esto debe convertirse en **un solo capítulo: Sesión 1**.

Dentro de ese capítulo debes colocar primero todo el contenido correspondiente a 1.a y después el correspondiente a 1.b, respetando estrictamente el orden cronológico y lógico en que fue desarrollado.

No quiero capítulos separados para 1.a y 1.b.

Lo mismo debe hacerse con cualquier subdivisión equivalente:

- 2.a + 2.b → Sesión 2
- 3.a + 3.b → Sesión 3
- etc.

La división `a`, `b`, etc. utilizada por el profesor debe entenderse como una subdivisión interna de una misma sesión, **no como capítulos independientes**.

## Orden cronológico

Es especialmente importante que todo el contenido quede en el orden en que fue desarrollado.

No reorganices posteriormente las definiciones, proposiciones o construcciones para formar una exposición "más bonita" si eso rompe el orden del curso.

Si un concepto aparece en 1.a y luego se continúa desarrollando en 1.b, conserva esa continuidad.

---

# 8. Título de los capítulos

En Homotopía Estable los capítulos tienen como nombre la fecha de la clase.

Para este proyecto **NO quiero utilizar fechas como título de los capítulos**.

El nombre de cada capítulo debe ser el **título que el profesor asigna a la sesión**.

Por ejemplo, si el material indica:

> Sesión 4: Morfismos y propiedades universales

el capítulo debe corresponder a esa sesión y utilizar el título dado por el profesor.

Si existe una subdivisión:

> Sesión 4.a: ...
>
> Sesión 4.b: ...

debes fusionarlas en un único capítulo:

> Sesión 4: ...

y dentro de él conservar el orden 4.a → 4.b.

No inventes títulos nuevos para las sesiones cuando el profesor ya haya proporcionado uno.

---

# 9. Sesión 0

La **Sesión 0** puede tratarse de manera especial.

Quiero que la adaptes como una **introducción general al curso**, utilizando el material correspondiente y, especialmente, el programa académico.

Puede funcionar como una introducción que explique brevemente:

- qué estudia el curso;
- cuál es la motivación general;
- qué temas se desarrollarán;
- cómo se relacionan las distintas partes del curso.

No es necesario forzar la Sesión 0 a tener exactamente la misma estructura que una sesión matemática ordinaria.

---

# 10. Ejercicios

Los ejercicios que aparezcan en los esqueletos, presentaciones o materiales del profesor **sí deben incorporarse a los apuntes**, conservando el enunciado y la notación del profesor.

Sin embargo:

> **NO RESUELVAS LOS EJERCICIOS.**

Los ejercicios los entregaré resueltos por separado.

Por tanto:

- incluye el enunciado;
- conserva la numeración si existe;
- conserva la notación del profesor;
- coloca los ejercicios en el lugar correspondiente dentro de la sesión;
- **no escribas soluciones ni sugerencias de solución**;
- no conviertas los ejercicios en ejemplos resueltos.

Si el profesor desarrolla en clase un ejercicio como parte de la exposición y ese desarrollo forma parte efectiva del contenido de la sesión, entonces sí debe escribirse dicho desarrollo como parte de los apuntes. La restricción es específicamente que **los ejercicios propuestos como ejercicios no deben ser resueltos por ti**.

---

# 11. Estilo de mis apuntes

Quiero que los apuntes de Teoría de Esquemas mantengan **el mismo estilo general de mis apuntes de Homotopía Estable**.

Inspecciona directamente varios de los archivos `.tex` existentes en:

`D:\Github\Apuntes-Homotop-a-Estable`

para entender exactamente cómo escribo y cómo está organizado el documento.

En particular, conserva estas características:

- Redacción matemática en español.
- Introducción o resumen breve al comienzo de cada sesión.
- Pocas `\section`, reservándolas para bloques temáticos generales.
- Usar `\subsection` para los temas concretos.
- Evitar dividir artificialmente el material en demasiadas secciones.
- Evitar una cantidad excesiva de saltos de línea.
- Preferir matemáticas en modo inline cuando la expresión lo permita.
- Reservar ecuaciones desplegadas para expresiones realmente grandes o importantes.
- Mantener una redacción matemática compacta y clara.
- No sobreformalizar innecesariamente.
- No convertir los apuntes en un libro de texto independiente del curso.
- Mantener los ambientes, comandos y convenciones de LaTeX de mi plantilla siempre que sean adecuados.
- Reproducir los diagramas matemáticos relevantes.
- Mantener consistencia en referencias, numeración y notación.

---

# 12. Construcción del proyecto LaTeX

Construye el proyecto completo dentro de:

`D:\Github\Apuntes Teoría de Esquemas`

partiendo de la plantilla de:

`D:\Github\Apuntes-Homotop-a-Estable`

Quiero que:

1. inspecciones cómo está organizado el proyecto de Homotopía Estable;
2. identifiques la estructura principal del documento;
3. copies/adaptes la plantilla;
4. ajustes nombre de materia, profesor y demás información pertinente;
5. adaptes los comandos y ambientes si la notación del curso de Teoría de Esquemas lo requiere;
6. generes los archivos `.tex` correspondientes a las sesiones;
7. mantengas el índice y la estructura general del documento;
8. mantengas los paquetes y configuraciones útiles de la plantilla;
9. elimines solamente aquello que realmente no sea necesario;
10. hagas que el proyecto sea compilable.

**No quiero que simplemente produzcas texto en el chat. Quiero que construyas físicamente los archivos del proyecto en la carpeta indicada.**

---

# 13. Revisión final obligatoria

Una vez que hayas construido todos los apuntes, haz una **revisión global del proyecto completo**.

Compara nuevamente los capítulos generados con los materiales originales y revisa especialmente:

- que todas las sesiones estén representadas;
- que ninguna parte importante de los esqueletos haya sido omitida;
- que el orden cronológico sea correcto;
- que las sesiones a/b hayan sido fusionadas correctamente;
- que los títulos de los capítulos correspondan a los títulos del profesor;
- que la notación sea consistente;
- que los argumentos del profesor no hayan sido sustituidos innecesariamente;
- que los huecos argumentales importantes hayan sido rellenados;
- que las definiciones, proposiciones, lemas, teoremas y ejemplos estén correctamente clasificados;
- que los diagramas relevantes no hayan sido omitidos;
- que los ejercicios estén incorporados **sin soluciones**;
- que no hayas agregado teoría externa innecesaria;
- que la estructura de LaTeX siga la de mis apuntes de Homotopía Estable;
- que el documento pueda compilarse.

Si durante esta revisión encuentras una omisión o inconsistencia, **corrígela directamente en los archivos del proyecto**.

No me entregues únicamente una lista de problemas: corrige los problemas que puedas corregir directamente.

---

# 14. Criterio general de calidad

Prefiero unos apuntes **fieles y completos al curso** antes que unos apuntes artificialmente "bonitos" o excesivamente pedagógicos.

Mi objetivo es que, al leerlos, pueda reconocer claramente:

> "Esto es exactamente lo que dio el profesor, pero con los huecos y detalles necesarios para que quede escrito de manera completa."

No quiero que parezca un libro de Teoría de Esquemas escrito por ti.

Quiero que parezca **mi versión escrita y ordenada de las clases del profesor**.

Por tanto, ante cualquier conflicto entre:

**elegancia expositiva propia** vs. **fidelidad al profesor**,

elige **fidelidad al profesor**.

Ante cualquier conflicto entre:

**agregar contenido útil** vs. **mantenerse dentro del contenido del curso**,

elige **mantenerse dentro del contenido del curso**.

Ante cualquier conflicto entre:

**reorganizar el material para hacerlo más pedagógico** vs. **conservar el orden en que lo desarrolló el profesor**,

elige **conservar el orden del profesor**.

Antes de comenzar a escribir, inspecciona primero **todo** el programa, los esqueletos, las presentaciones y la plantilla de Homotopía Estable. Después construye el proyecto completo directamente en la carpeta indicada y realiza la revisión global final antes de darlo por terminado.