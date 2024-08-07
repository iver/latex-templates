# Primeros pasos con LaTeX

LaTeX es un programa de composición tipográfica útil para escritos o publicaciones matemáticas y científicas. Este repositorio proporciona una descripción general de cómo empezar a utilizar LaTeX, así como recursos y ejercicios para ayudar a los nuevos usuarios.

## ¿Qué es LaTeX?

A diferencia de los programas de procesamiento de textos comunes, como Word de Microsoft, que funcionan mediante un proceso de WYSIWYG "lo que ves es lo que obtienes", LaTeX produce un documento compilado a partir de un código escrito por el usuario.  Esto permite que LaTeX se encargue de gran parte del trabajo cuando se trata de editar ecuaciones, crear tablas, insertar figuras, hacer referencias y muchos de los tediosos procesos asociados con la elaboración y el formato de un documento.

El núcleo de LaTeX es un paquete de software backend que compila el código LaTeX (archivo .tex) y crea el documento final (PDF).

### ¿Porqué TeX?

**TeX** (las consonantes en mayúsculas y la vocal en minúscula) está considerado el más potente programa formateador para producir libros científicos o técnicos de calidad profesional. Fue desarrollado por [Donald E. Knuth][Knuth] y el nombre TeX procede de la palabra griega “τεχ” que es la raíz de palabras españolas (e inglesas) tales como “técnica” o “tecnología”, aunque los griegos la usaban también como raíz de “techné”, arte. Por ello dice el autor de TeX que escogió ese nombre para poner el énfasis en el arte y en la tecnología; es decir: TeX no se conforma con obtener documentos pasables sino que busca la más alta calidad posible (la más artística) en documentos relativos a la técnica y a la tecnología. Por tanto la “x” final de TeX no es una “x”, sino el carácter griego χ, que en español se pronuncia como la jota; de ahí que TeX se pronuncie “tej” o, si se prefiere, “tek”.

El autor de TeX mientras lo generaba, estudió concienzudamente las mejores tradiciones tipográficas, diseñó sus propias fuentes, y preparó al programa para enfrentarse a todas las tareas y decisiones que suelen tomar los tipógrafos.

### LaTeX

La capacidad de TeX para escribir macros, hacía relativamente sencillo generar dialectos de TeX a partir del propio TeX. LaTeX es uno de los dialectos derivados de TeX, lo que significa que, desde el punto de vista interno, LaTeX no es sino un conjunto de macros para TeX. Fue diseñado originariamente en 1985 por [Leslie Lamport][Leslie] con la intención de simplificar el uso de TeX sin renunciar al uso de su gran calidad. Consiste en un conjunto de macros de alto nivel dirigidas a la producción de documentos técnicos, con una alta calidad tipográfica.

En resumen, LaTeX oculta al usuario la complejidad de TeX, al tiempo que le permite concentrarse en el contenido del documento, garantizando que el resultado final tendrá una alta calidad tipográfica.

## Instalación

Existen diversos programas disponibles para hacer esto dependiendo del sistema operativo del usuario.   El Proyecto LaTeX ([The LaTeX Project](https://www.latex-project.org/get/)) proporciona información sobre cómo instalar LaTeX en Windows, Mac y Linux, así como servicios en línea.

### Windows

Para una computadora con Windows, se recomienda utilizar el editor [MiKTeX][MiKTeX].  La página [MiKTeX/about][about] contiene varios enlaces que incluyen cómo [instalar][install], [desplegar][deploy] y [actualizar][update] MiKTeX.

A continuación se resumen las instrucciones de instalación, es recomendable consultar la página de [MiKTeX][MiKTeX] en caso de algún problema:

1. Descargar MiKTeX (MiKTeX 64 básico o MiKTeX 32 básico, según la computadora)
2. Ejecutar el instalador. Durante la instalación, se solicitará seleccionar el tamaño del papel. Se recomienda elegir el tamaño de letra (se puede cambiar más adelante si es necesario).
3. Se recomienda verificar si hay actualizaciones. El asistente de actualización se puede encontrar a través del menú de inicio de Windows.

### Mac OS X

El paquete a instalar en Mac es [MacTeX][MacTeX]. Se puede [descargar un paquete de instalación][downloadMT] e instalar como cualquier otro paquete de Mac. Otra opción es emplear un administrador de paquetes como [Homebrew][HB] o [MacPorts][MP]

```terminal
# homebrew
$ brew install --cask mactex

# macports
$ sudo port install texlive-latex
```

Se puede ver que para MacPorts se usa TeXLive, este paquete también se emplea en distribuciones Linux. Las instrucciones para instalar LaTeX en distribuciones Linux, se puede ver la [lista publicada por version][linuxTL] para más información se puede consultar la página de "[The LaTeX Project][latex]"

## Referencias

Para saber más sobre LaTeX en español, se recomienda la lectura de la página de la [Universidad de Murcia][UM]

[MiKTeX]: https://en.wikipedia.org/wiki/MiKTeX
[Knuth]: https://en.wikipedia.org/wiki/Donald_Knuth
[Leslie]: https://en.wikipedia.org/wiki/Leslie_Lamport
[about]: https://miktex.org/about
[deploy]: https://miktex.org/howto/deploy-miktex
[install]: https://miktex.org/howto/install-miktex
[update]: https://miktex.org/howto/update-miktex
[UM]: https://www.um.es/innova/OCW/informatica-para-universitarios/ipu_docs/latex/ipu_latex.html
[MacTeX]: https://en.wikipedia.org/wiki/MacTeX
[downloadMT]: https://www.tug.org/mactex/mactex-download.html
[HB]: https://brew.sh/
[MP]: https://www.macports.org/
[linuxTL]: https://repology.org/project/texlive/versions
[latex]: https://www.latex-project.org/get/