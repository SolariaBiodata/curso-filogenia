---
permalink: /sesion02.html
---
![alt text](https://solariabiodata.com.mx/images/solaria_banner.png "Soluciones de Siguiente Generación")
# Curso de Análisis Filogenéticos

## Sesión Práctica del Día 02

### Descripción
En esta sesión aprenderemos lo necesario para realizar reconstrucciones filogenéticas, interpretar cómo se relacionan entre ellos y renderizar gráficos listos para la publicación.

### Requisitos

Para poder realizar este ejercicio, necesitaremos:

1. Datos de secuencias:
    - Puedes usar las secuencias del gen _rpb2_ del curso, que encontrarás [en este link](data/rpb2.fasta)
    - Puedes usar también las secuencias del gen de _ha1_ del curso, las encontrarás en [este link](data/ha1.fasta)
    - Puedes usar tus propias secuencias, en formato FASTA
2. Acceso a las siguientes páginas de internet:
    - Página de [NCBI](https://www.ncbi.nlm.nih.gov/)
    - Página de la [Herramienta Blast](https://blast.ncbi.nlm.nih.gov/Blast.cgi)
    - Página del [Algoritmo ClustalW](https://www.ebi.ac.uk/Tools/msa/clustalo/)
    - Página del [Algoritmo MUSCLE](https://www.ebi.ac.uk/Tools/msa/muscle/)
3. Sofware Recomendable para esta sesión:
    - Bloc de Notas
    - MEGA
    - FigTree
    - Inkscape
4. Elementos Gráficos para el último ejercicio:
    - Vector [Verde](data/virus-green.svg)
    - Vector [Rojo](data/virus-red.svg)
    - Vector [Azul](data/virus-blue.svg)
5. Árbol Filogenético en Formato Newick:
    - Úsalo sólo si quieres repasar el ejercicio 02 y 03: [ha1.nwk](data/ha1.nwk)

## Ejercicio 01: Reconstrucción filogenética
### Descripción
En este ejercicio, utilizaremos el programa de MEGA para realizar el proceso indicado en la sesión de Métodos de Filogenia. Para lo anterior, reutilizaremos las secuencias que ya habíamos descargado en la sesión 01 de este mismo curso.

### Instrucciones

1. En la interfaz, localizaremos el ícono de _‘Align’_
2. Seleccionamos la opción _‘Edit/Build Alignment’_
3. En la nueva ventana, seleccionamos _‘Retrieve a sequence from a file’_
4. Realizaremos los siguientes alineamientos:
    - DNA con `Muscle`
    - Aminoácidos con `ClustalW`
5. Una vez alineado, podemos ver una representación _dot-alignment_
6. Podemos hacer varias actividades, como computar la matriz de distancias (entre cada una de las secuencias) o calcular el mejor modelo para una reconstrucción por Máxima Verosimilitud
7. Para realizar la filogenia, nos ubicamos en _‘Phylogeny’_
8. Para este ejercicio, realizaremos un árbol por el **método de NJ**
9. En la ventana de parametrización:
    - `Test: Bootstrap (100)`
    - `Maximum Composite Likelihood`
    - `Substitutions: Transitions + Transversions`
    - `Data Subset: Pairwise`
10. ¡Hemos generado un par de filogenias a partir de secuencias descargadas!
    - Árbol de **NJ**
    - Árbol del método estadístico
11. Exportaremos el árbol filogenético desde la pestaña _‘Image’_ a los siguientes formatos:
    - Guardar como PDF
    - Guardar como PNG
12. Exportaremos el árbol en un formato especial, denominado por NWK desde la pestaña _‘File’_

## Ejercicio 02: Generación de Figuras
### Descripción
En este ejercicio, utilizaremos el árbol generado en formato Newick para modificar y embellecer el aspecto visual de la filogenia. En este ejercicio es necesario que ya hayas tenido el árbol generado.

### Instrucciones

1. En _‘File’_ abriremos la opción _‘Open’_.
2. Cargaremos el archivo en formato NWK que se ha generado desde MEGA
3. Una vez cargado, tendremos la disponibilidad de cambiar cada una de las propiedades del gráfico.
4. En este ejercicio, retiraremos el nombre de los nodos para observar a mayor detalle el árbol.
5. Modificaremos entre los tipos de layout:
    - Rectangular
    - Radial
    - Polar
6. Aprenderemos a utilizar algunas opciones como:
    - Ancho de líneas
    - Selección y Remarcado
    - Colores
    - Inclusión de formas en nodos
    - Transformación
    - Enraizamiento

## Ejercicio 02: Renderizado
### Descripción
En este último ejercicio, realizaremos la importación del árbol en formato vectorial en un software de diseño gráfico gratuito, que puede ayudarnos a agregar elementos visuales y cambiar de último momento la apreciación de colores, o la inclusión de más elementos gráficos.
### Instrucciones
1. En la ventana de FigTree, seleccionamos la opción ‘Export to SVG’ y guardamos
2. Cargaremos este archivo en Inkscape
3. Recuperaremos elementos gráficos, preferentemente en formato SVG:
    - En el Navegador, iremos a la siguiente dirección: https://flaticon.com
    - Elementos que tenemos en el repositorio del ejercicio
4. Revisaremos algunos elementos vectoriales:
    - Inclusión de objetos
    - Desagrupamiento
    - Cambios de color final
    - Exportación a PNG
