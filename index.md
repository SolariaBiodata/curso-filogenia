---
permalink: /index.html
---
![alt text](https://solariabiodata.com.mx/images/solaria_banner.png "Soluciones de Siguiente Generación")
# Curso de Análisis Filogenéticos

## Sesión Práctica del Día 01

### Descripción
En esta sesión aprenderemos lo necesario para descargar secuencias de NCBI, filtrar las búsquedas con opciones avanzadas y empezar a realizar comparaciones en resultados de alineamientos.

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
    - Seaview
    - ClustalX
    - MEGA

## Ejercicio 01: Búsqueda en NCBI
### Descripción
Realizaremos una exploración de secuencias utilizando palabras clave en el campo de búsqueda, desde la interfaz de la página de NCBI y en la base de datos nucleotídica no-redundante, también conocida como Genbank.

### Instrucciones
1. Buscar en la NCBI en nucleotide `hiv2ben`.
2. Seleccionar el primer registro.
3. En la parte superior, oprimiremos el botón `SEND TO` y almacenaremos el archivo en formato FASTA.
4. Visualizar la secuencia completa que se ha descargado.


## Ejercicio 02: Números de Acceso y BLAST
### Descripción
Realizaremos una búsqueda de secuencia por No. de Acceso, que consiste en un ID único, que sirve como distintivo para una secuencia particular, en toda la colección disponible de NCBI.

### Instrucciones
1. Buscaremos en NCBI el número de acceso `L20106.1`.
2. ¿A qué secuencia corresponde?
3. Almacenaremos la secuencia de nucleótidos en formato FASTA.
4. Realizaremos un 'BLAST' a la secuencia, para identificar todos los elementos de respuesta a esta búsqueda.

## Ejercicio 03: Búsqueda Avanzada
### Descripción
Utilizaremos utilidades adicionales en la búsqueda normal de NCBI para filtrar más a detalle el conjunto de la colección resultante.

### Instrucciones (Parte 1)
1. En `all fieds` seleccionar `MeSH Terms`, escribir en la ventana `hyperglycemia`.
2. En la siguiente línea escribir `newborn`.
3. Seleccionar `add to history` , lo anterior mostrara todas las búsquedas.
4. Click en el número y click en save in MyNCBI.

### Instrucciones (Parte 2)
1. En `all fieds` seleccionar `Organism`  escribir en la ventana `influenza AH1N1 `
2. En la siguiente línea escribir  `Neuramindase`
3. Seleccionar `add to history`, lo anterior mostrará todas las búsquedas.
4. Click en el número y click en save in MyNCBI.

## Ejercicio 04: Filtros de Búsqueda
### Descripción
Con este ejercicio, repasaremos algunos filtros adicionales en la búsqueda de secuencias y recopilaremos la información basada en propiedades de la subida en Genbank.
### Instrucciones
1. En NCBI nucleotide, buscaremos las secuencias de: `RPB2`
2. En el lado izquierdo, Filtraremos nuestra búsqueda respecto a:
    - Source `Refseq`
    - Species `Fungi`
    - Molecule Type `mRNA`
3. Apreciaremos el tamaño de la selección resultante
4. Descargaremos las primeras 20 secuencias, con el nombre de `rpb2.fasta`

## Ejercicio 05: Alineamiento Múltiple de Secuencias
### Descripción
Repasaremos lo que hemos aprendido respecto a los métodos de alineamiento múltiple de secuencias, utilizando el algoritmo de alineamiento global con las secuencias del gen _rpb2_ o el gen _ha1_ que ya hemos descargado previamente.

### Instrucciones (Parte 1)
1. Dirigirse a la dirección https://www.ebi.ac.uk/Tools/msa/clustalo/
2. Seleccionar el tipo de molécula a DNA.
3. Pegar el contenido del archivo de secuencias o cargarlo desde la ventana que se abre al dar clic en 'Examinar'.
4. Seleccionar el formato de salida a Pearson/FASTA.
5. Clic en el botón de 'Submit' y esperar a los resultados.
6. Descargar el alineamiento resultante dando clic derecho y 'Guardar Como... '
7. Daremos clic en el botón 'Result Viewers' y después en `MView`
8. Descargaremos también la visualización.

### Instrucciones (Parte 2)
1. Dirigirse a la dirección https://www.ebi.ac.uk/Tools/msa/muscle/
2. Repetiremos los pasos 3 al 8 de la Parte 1 de este mismo ejercicio.


## Ejercicio 06: Selección de modelos
### Descripción
Vamos a hacer un ejercicio de selección de modelos

### Instrucciones (Parte 1)
1. Dirigirse a la dirección http://iqtree.cibiv.univie.ac.at/
2. Seleccionar la pestaña de selección de modelo
3. En la sección de entradas, mediante el botón 'Browse' Busca tu alineamiento seleccionalo.
4. En la sección de opciones selecciona un criterio de selección.
5. Clic en el botón de 'Submit' y esperar a los resultados.
