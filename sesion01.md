---
permalink: /sesion01.html
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

## Ejercicio 05: Taxonomy y Popset
### Descripción
Con este ejercicio, recuperaremos secuencias que ya han sido validadas en un análisis de tipo filogenético.
### Instrucciones
1. En NCBI Taxonomy, buscaremos El organismo `Fusarium`.
2. Seleccionaremos la casilla de Popset, desde la interfaz de búsqueda.
3. Clic en el botón GO.
4. Daremos clic en el número indicado a un lado derecho del campo `Fusarium`.
5. En el campo de búsqueda avanzada, teclearemos `AND rpb2`.
6. Descargaremos algunos de los popsets encontrados en esta búsqueda.

##Instalación de programas en Ubuntu

###Lineas de comando para FigTree:
Descargar el archivo de programa

	wget https://github.com/rambaut/figtree/releases/download/v1.4.4/FigTree_v1.4.4.tgz

Desempaquetar

	tar -xzvf FigTree_v1.4.4.tgz

Instalar java:	
	sudo apt install openjdk-11-jre-headless

Ejecutar FigTree:

	java -jar figtree.jar 

###Lineas de comando para MEGA:

Descargar el archivo desde [MEGA](https://www.megasoftware.net/)

Instalar el paquete de instalación local

	sudo apt install gdebi-core

Instalar el MEGA

	sudo gdebi -n mega_11.0.9-1_amd64.deb 

