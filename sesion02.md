---
permalink: /sesion02.html
---
![alt text](https://solariabiodata.com.mx/wp-content/uploads/2021/07/logo_red.png "Soluciones de Siguiente Generación")
# Curso de Análisis Filogenéticos

## Sesión Práctica del Día 02

### Descripción
En esta sesión aprenderemos lo necesario para realizar reconstrucciones filogenéticas, interpretar cómo se relacionan filogenéticamente las secuencias y renderizar gráficos listos para la publicación.

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
    -
3. Sofware Recomendable para esta sesión:
    - Bloc de Notas
    - MEGA

## Ejercicio 01: Alineamiento con MEGA
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

## Ejercicio 02: Alineamiento Online

### Descripción
Repasaremos lo que hemos aprendido respecto a los métodos de alineamiento múltiple de secuencias, utilizando el algoritmo de alineamiento global con las secuencias del gen _rpb2_ o el gen _ha1_ que ya hemos descargado previamente.

### Instrucciones (Parte1)

1. Dirigirse a la dirección (https://www.ebi.ac.uk/Tools/msa/clustalo/)
2. Seleccionar el tipo de molécula a DNA.
3. Pegar el contenido del archivo de secuencias o cargarlo desde la ventana que se abre al dar clic en 'Examinar'.
4. Seleccionar el formato de salida a Pearson/FASTA.
5. Clic en el botón de 'Submit' y esperar a los resultados.
6. Descargar el alineamiento resultante dando clic derecho y 'Guardar Como... '
7. Daremos clic en el botón 'Result Viewers' y después en `MView`
8. Descargaremos también la visualización.

### Instrucciones (Parte 2)
1. Dirigirse a la herramienta de (https://www.ebi.ac.uk/Tools/msa/mafft/)
2. Repetiremos los pasos 3 al 8 de la Parte 1 de este mismo ejercicio.

### Instrucciones (Parte 3)
1. Dirigirse a la herramienta de (https://www.ebi.ac.uk/Tools/msa/tcoffee/)
2. Repetiremos los pasos 3 al 8 de la Parte 1 de este mismo ejercicio.
