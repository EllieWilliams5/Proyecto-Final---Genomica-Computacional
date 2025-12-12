# Evolución molecular de opsinas visuales en Cetacea: análisis filogenético de la transición terrestre-acuática

## Genómica Computacional (2026 - 1)
**Profesor :** Sergio Hernández López \
**Ayudante :** Rafael López Martínez \
**Ayud. Lab. :** Jazmín de Jesús Santillán Manjarrez

## Integrantes del equipo
- Caballero Rosas Santiago 
- Hernández Amaro María Fernanda 
- Mendiola Montes Víctor Manuel


## Organización de Carpetas
```
Proyecto Final/
|
| - Docs/
|   |
|   | - Evolución_molecular_de_opsinas_visuales_en_Cetacea__análisis_filogenético_de_la_transición_terrestre_acuática.pdf (Reporte de nuestro trabajo)
|   | - Exposición.pdf
|
FILOGENIAS/
|
| - Ancestors Analysis/  (Cuidado con estas, fueron todas hechas sobre el arbol de LWS)
|   |
|   | - LWS/
|   |   |
|   |   | - Ancestral-states-details.txt
|   |   | - Changes List.txt
|   |   | - LWSexons_ancestors.png
|   |   | - LWSexons_ancestors_numbers.png
|   |   | - Most Probable Sequences.txt
|   |   | - site-41-ancestral-states.txt
|   |
|   | - RH1/
|   |   |
|   |   | - Ancestral States.txt
|   |   | - Ancestral-states-details.txt
|   |   | - Changes List.txt
|   |   | - Most Probable Sequences.txt
|   |   | - RH1 Exons.mtsx
|   |   | - RH1 Exons_ancestors.png
|   |   | - RH1 Exons_ancestors_numbers.png
|   |
|   | - SWS1/
|   |   |
|   |   | - Ancestral-states-details.txt
|   |   | - Changes List.txt
|   |   | - Most Probable Sequences.txt
|   |   | - site-1-ancestral-states.txt
|   |   | - SWS1exons_ancestors.png
|   |   | - SWS1exons_ancestors_numebrs.png
|
|
| - LWS/
|   |
|   | - LWS Exon 1 amplicon/
|   |   |
|   |   | - Caption_tree.txt
|   |   | - LWS Exon 1 amplicon.meg
|   |   | - LWS Exon 1 amplicon_tree.png
|   |   | - SEQ4.txt
|   |   | - SEQ4_MODELANALYSIWS.pdf
|   |   |  
|   |   | - Sessions/
|   |   |   |
|   |   |   | - LWS Exon 1 amplicon.mdsx
|   |   |   | - LWS Exon 1 amplicon_tree.mtsx
|   |
|   | - LWS_Exons/
|   |   |
|   |   | - Caption_tree.txt
|   |   | - LWSExons_MODELANALYSIS.pdf
|   |   | - LWSExons_tree.png
|   |   | - SEQ3.meg
|   |   | - SEQ3.txt
|   |   |  
|   |   | - Sessions/
|   |   |   |
|   |   |   | - Newick Export.nwk
|   |   |   | - SEQ3.mdsx
|   |   |   | - SEQ3_tree.mtsx
|   |   |   | - TREE_Nedwick
|
|
| - RH1/
|   |
|   | - RH1 Exons/
|   |   |
|   |   | - Caption_tree.txt
|   |   | - RH1 Exons.meg
|   |   | - RH1 Exons.txt
|   |   | - RH1 Exons_MODELANALYSIS.pdf
|   |   | - RH1 Exons_tree.png
|   |   |  
|   |   | - Sessions/
|   |   |   |
|   |   |   | - RH1 Exons.mdxs
|   |   |   | - RH1 Exons_tree.mtsx
|
|
| - SWS1/
|   |
|   | - SWS1_IntronesExones/
|   |   |
|   |   | - Caption_tree.txt
|   |   | - SWS1 Introns + Exons.meg
|   |   | - SWS1 Introns + Exons_MODELANALYSIS.pdf
|   |   | - SWS1 Introns + Exons_NUCLEOTIDCOMPOSITION
|   |   | - SWS1 Introns + Exons_treeanalysissummary
|   |   | - SWS1_EXONSINTRONS_TREE.png
|   |   |  
|   |   | - Session/
|   |   |   |
|   |   |   | - SEQ1.mdxs
|   |   |   | - SWS1_EXONSINTRONS_TREE.mtsx
|   |
|   |
|   | - SWS_Exons/
|   |   |
|   |   | - Caption_tree.txt
|   |   | - SEQ2.meg
|   |   | - SEQ2.txt
|   |   | - SWS1Exons_MODELANALYSIS.pdf
|   |   | - SWS1Exons_tree.png
|   |   |  
|   |   | - Sessions/
|   |   |   |
|   |   |   | - SEQ2.mdsx
|   |   |   | - SEQ2_tree.mtsx
|
| - Readme.md (Este archivo)
```
## Explicación del contenido de las carpetas

En la carpeta `Docs`, hemos puesto el reporte completo de nuestro trabajo y nuestra exposición.

Las carpetas `LWS`, `RH1`, `SWS` son para los genes, y `Ancestor Analysis` es la que contiene el análisis de ancestros para todos en general.

En `LWS` estan las carpetas `LWS Exon 1 Amplicon` y `LWS Exons`. Dentro de ambas carpetas, estan los siguientes archivos:
- `Caption Tree` que son los que generan el programa MEGA cuando hacemos el árbol.
- Un archivo `MEG`, que es el archivo para abrir la secuencia.
- Un `PNG` asociado al árbol para cada uno de estos.
- Un archivo `TXT`, que es un archivo donde se tienen las secuencias en crudo.
- Un `PDF` que siempre termina en Model Analysis, que tiene que ver con el análisis de AICO.
- Una carpeta `Sessions`. En esta carpeta tenemos dos archivos para directamente para `MEG`, listos para abrir o cargar ya la secuencia alineada o abrir los árboles. 

Es un caso análogo para la carpeta `SWS1` y `RH1`, solo que tenemos una única carpeta `RH1 Exons`. Dentro de ella tenemos una carpeta `Sessions`, `Caption Tree`, `RH1`, el archivo `MEG`, el `TXT`, el `PNG` y el `PDF`. En `SWS1` tenemos las carpetas `SWS Exons` y `SWS1`, para Baja, Intrones, Exones, y tienen la misma estructura todos. 

En `Ancestral Analysis`, tenemos las carpeta `LWS`, `RH1` y `SWS`. En todas las carpetas tenemos un archivo llamado `Ancestral States Details`, que son como un detalle del análisis ancestral. `Changes List`, que es una lista de cambios. Dos `PNG`, que son los árboles de las reconstrucciones ancestrales, uno con número y otro sin número, (por eso uno está así y el otro dice Numbers). `Most Probable Sequences`, un archivo de secuencias más probables, y un archivo de estados ancestrales.
