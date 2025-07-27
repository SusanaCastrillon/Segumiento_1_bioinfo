# Segumiento_1_bioinfo

## Descripción del archivo
Se tiene un archivo .gff3, llamado General Feature Format en su versión 3. Este es un archivo tabulado de texto plano que describe anotaciones de genómicas, cada línea representa entonces, una anotación de un elemento biológico sobre una secuencia genómica, por lo que se encontrarán genes, exones, regiones codificantes (CDS), mRNA, pseudogenes, entre otros.
Cada línea contiene las siguientes 9 columnas: 
1. Nombre de la secuencia
2. Fuente de la anotación
3. Tipo de feature (gen, exón, CDS, etc.)
4. Posición de inicio del feature
5. Posición final del feature
6. Phred score o valor de confianza
7. Sentido de la hebra (+ para sentido y - para antisentido)
8. Marco de lectura para el CDS si aplica, 9. Atributos como el ID del gen.
### Ejemplo: un gen en la secuencia 2, que va desde la posición 35,680 hasta 46,893, en la hebra positiva con un ID gene 00002, nombre ABC1 y biotipo protein_coding se vería de la siguiente forma, con separador "/" en lugar de tab:
1/emsembl gene/35680/46893/./+/./ID=gene00002;Name=ABC1;biotype=protein_Coding

## Descripción del organismo biológico
Numida meleagris es comúnmente conocidad como al gallina de Guinea compun, es una especie de ave galliforme perteneceinete a la familia Numididae, esta es una ave terrestre que, aunque es capaz de volar con fuerza, prefiere correr (Oval et al., 2022). Se caracteriza por su plumaje gris oscuro salpicado de blanco, un cuerpo robusto y una cabeza desnuda con apéndices carnosos (Soara et al., 2020). La Gallina de Guinea es originaria de África subsaharina, y es la única ave domesticada originaria de esta región, que cuenta con una análisis genómico, que lo confirma (Shen et al., 2021). Es una especie apreciada no solo por su carne y huevos, que son cada vez más buscados por los conusmidores, sino también por sus valiosas características biológicas (ROSCA & Usturoi, 2018)(Georgina et al., 2020). 

## Análisis del archivo
1. ¿Cuántos features contiene el archivo?
Contiene 19 features unicos.
<img width="793" height="57" alt="image" src="https://github.com/user-attachments/assets/78fcfff8-0079-4cf0-8f22-32a4c246eb1d" />

2. ¿Cuántas regiones de la secuencia (cromosomas) contiene el archivo?
El archivo contiene 2466 líneas que indican regiones de la secuencia.
<img width="727" height="124" alt="image" src="https://github.com/user-attachments/assets/e058b43b-4687-442f-a08e-afb8aa85b03a" />

3. ¿Cuántos genes están listados en el organismo?
Se listan 15661 genes, excluyendo pseudogenes y ncRNA genes. O 23258 incluyendolos.
<img width="591" height="116" alt="image" src="https://github.com/user-attachments/assets/86359be3-4919-4023-ae1b-b27bb2aca254" />

4. ¿Cuál es el top 10 de features (Columna 3) más anotados en el genoma?
Los 10 primeros lugares en orden descendente son: exón, CDS, biological_region, mRNA, gene, five_prime_UTR, lnc_RNA, three_primem_UTR, ncRNA_gene, region.
<img width="830" height="406" alt="image" src="https://github.com/user-attachments/assets/a887db46-52a2-43f4-a37a-5dd46bbcf3cf" />
