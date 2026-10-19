# Apuntes de Teoría de Esquemas

Apuntes personales de **Pablo Jair Aranda Pérez** para el curso de Teoría de Esquemas impartido por el **Dr. Jesús Rogelio Pérez Buendía** en el CIMAT, durante 2026. El texto está escrito en español y reúne definiciones, resultados, demostraciones, ejemplos, ejercicios y diagramas de las clases.

**[Leer los apuntes en PDF](build/main.pdf)** · **[Tareas y soluciones](https://github.com/MrPaborru/Tareas-Teoria-de-Esquemas)** · **[Reportar una errata](https://github.com/MrPaborru/Apuntes-Teoria-de-Esquemas/issues/new?template=errata.yml)**

## Contenido y estado

El documento incluye la introducción y las **sesiones 1–8**, con materiales incorporados hasta **S8b**. El programa completo contempla 24 sesiones; las que aún no están apuntadas no aparecen en el PDF.

| Sesión | Tema |
| --- | --- |
| 0 | Introducción: alcance del curso, lecturas y prerrequisitos |
| 1 | Motivación y el conjunto de ideales primos `Spec A` |
| 2 | La topología de Zariski |
| 3 | Localización y funciones regulares |
| 4 | Pregavillas y gavillas |
| 5 | La gavilla estructural |
| 6 | Esquemas afines y equivalencia contravariante |
| 7 | Definición de esquema y pegado |
| 8 | Ejemplos globales: plano menos el origen, morfismo canónico y espacios proyectivos |

Cada capítulo corresponde a una sesión. Las clases a, b, c, etc. de una misma sesión se integran en una exposición continua cuando completan argumentos anteriores. Los apuntes conservan los contenidos distintos de los esqueletos y los desarrollos, dibujos y diagramas de las presentaciones.

Este es un documento de estudio en elaboración. Las correcciones y precisiones matemáticas son bienvenidas.

## Cómo leer y descargar

- [Abrir el PDF completo](build/main.pdf): contiene el índice y referencias internas con hipervínculos.
- [Descargar el PDF](https://github.com/MrPaborru/Apuntes-Teoria-de-Esquemas/raw/refs/heads/main/build/main.pdf).
- [Consultar el programa del curso](Recursos/programa_geometria_algebraica_esquemas_2026_v3.pdf).
- [Consultar los materiales de clase](Recursos): esqueletos, presentaciones y anotaciones.

El documento incluye ejercicios propuestos. Las soluciones de las tareas se reúnen en el [repositorio de tareas](https://github.com/MrPaborru/Tareas-Teoria-de-Esquemas).

## Organización del repositorio

| Ruta | Contenido |
| --- | --- |
| [`main.tex`](main.tex) | Documento principal, paquetes y datos de portada |
| [`Apuntes/Cuerpo.tex`](Apuntes/Cuerpo.tex) | Sesiones que se incluyen en el documento |
| [`Apuntes/`](Apuntes) | Fuentes LaTeX por sesión; los archivos `Pendiente*.tex` no se incluyen en el PDF |
| [`Recursos/`](Recursos) | Programa y materiales del profesor |
| [`Personalizacion/`](Personalizacion) | Comandos, entornos, títulos, índice y encabezados |
| [`Portada/`](Portada) | Portada y elementos gráficos |
| [`build/main.pdf`](build/main.pdf) | Versión compilada que se publica |
| [`latexmkrc`](latexmkrc) | Configuración de compilación y salida en `build/` |

## Compilación local

Se necesitan **pdfLaTeX**, **latexmk** y **Perl**, además de los paquetes utilizados en [`main.tex`](main.tex). Una instalación de TeX Live o MiKTeX debe incluir las fuentes `newtx`, TikZ, `tikz-cd`, `tikz-nfold`, `tcolorbox`, `cleveref` y los demás paquetes del preámbulo.

Desde la raíz del repositorio:

~~~sh
latexmk -pdf main.tex
~~~

El resultado queda en **`build/main.pdf`**. La configuración incluida envía allí los archivos auxiliares y no abre un visor externo. La bibliografía actual usa `thebibliography` y no necesita Biber.

Para recompilar al guardar cambios:

~~~sh
latexmk -pdf -pvc main.tex
~~~

Para eliminar auxiliares conservando el PDF:

~~~sh
latexmk -c main.tex
~~~

## Erratas y colaboraciones

Para señalar un error, indica la sesión, la página del PDF o la etiqueta del resultado, la versión consultada y la corrección propuesta. También puedes enviar una propuesta de cambio en los archivos `.tex`.

Consulta [CONTRIBUTING.md](CONTRIBUTING.md) para los criterios de edición y los pasos para colaborar.

## Autoría, referencias y citación

La redacción de estos apuntes es de **Pablo Jair Aranda Pérez**. Los materiales de clase y las referencias bibliográficas conservan su atribución; los detalles están en [CREDITS.md](CREDITS.md).

Para citar el material, usa [CITATION.cff](CITATION.cff) e indica el commit o la versión del PDF consultada.

**Repositorio complementario:** [Tareas de Teoría de Esquemas](https://github.com/MrPaborru/Tareas-Teoria-de-Esquemas).
