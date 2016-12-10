# analisis-exploratorio-r

Práctica Análisis Exploratorio R
Esta práctica consiste en entregar un script R markdown con el Análisis Descriptivo y Exploratorio del dataset principal utilizado en la clase de "Introducción a R".

Recordamos que el conjunto de datos que se encuentra en https://archive.ics.uci.edu/ml/machine-learning-databases/00320/student.zip

Recordad que este dataset constaba de:

2 archivos CSV con los datos: student-mat.csv, student-por.csv
Un script student-merge.R que mostraba cómo obtener los estudiantes que aparecen en ambos CSV
Un "diccionario" que describe los campos: student.txt.
La descripción de los datos (diccionario) se encuentra en: https://archive.ics.uci.edu/ml/datasets/Student+Performance

Para facilitaros la realización de la práctica, deciros que el análisis debería idealmente contar con estas 5 fases

1. Introducción con el objetivo del análisis:

En esta práctica pretende llegar sólo hasta el Exploratorio
Pero se debe ir pensando en una finalidad posterior (Modelo predictivo, Clasificación, ....) Aunque esta finalidad última no se incluya en la práctica, se debe plantear la "hipótesis" en la introducción. Con este dataset se podría tratar de predecir el valor de la nota final G3, o clasificar a los alumnos como aprobados o suspendidos en base a que esa nota sea mayor o menor que 5, pero se puede pensar otro objetivo si así se quiere).
Se recomienda leer este estudio "Using data mining to predict secondary school student performance" http://hdl.handle.net/1822/8024. Se puede bajar el paper en PDF: http://repositorium.sdum.uminho.pt/bitstream/1822/8024/1/student.pdf. Este paper aplica algunos modelos y los compara.
2. Carga de los datos

3. Análisis descriptivo

4. Análisis exploratorio (puede ser apoyado en algún método NO supervisado)

5. Conclusiones: ¿Pensamos que este dataset puede servir para la finalidad/modelo que habíamos planteado en la Introducción? ¿Tenemos ya alguna conclusión preliminar sobre qué variables pueden resultar más últimes para dicha finalidad/modelo (predictivo, clasificación, ...)?

El informe será entregado en formato Rmarkdown (http://rmarkdown.rstudio.com/) en el que se incluirá el código R y las explicaciones convenientes, así como los gráficos.

El informe PDF, Word o HTML que se genere a partir del Rmarkdown, no podrá superar las 8 páginas de extensión con un máximo de 6 figuras.

La entrega puede ser:

1. Adjuntar el archivo R Markdown al moodle.

2. Subir el archivo R Markdown a Git, a una cuenta del alumno y adjuntar como entrega, el link correspondiente

3. Adjuntar al moodle el archivo R Markdown y también pegar el link al GIT.

---------------

Siempre se valorará más que el R Markdown se haya subido al GIT.

-------------

SCRIPT REPRODUCIBLE: Tened en cuenta que el script debe poder reproducirse en cualquier entorno, por lo que no debe depender de las rutas locales (directorios, paths) de vuestro equipo. Utilizad setwd(), getwd(), y funciones de modo conveniente.
