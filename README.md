# Seguimiento 1 Juanita Vélez Uribe
## Desarrollo del primer seguimiento de bioinformática. Por: Juanita Vélez Uribe
______________________________________________________________________________________________________________________________________________________________________________
## Descripción de los campos que contienen los archivos GFF 3
    #Columna		Nombre	      Descripción
       1	      seqid	        Secuencia (cromosoma, contig, etc.)
       2	      source	      Fuente del dato (programa o base de datos)
       3	      type	        Tipo de característica (gene, mRNA, exon, etc.)
       4	      start	        Posición inicial (1-based)
       5	      end	          Posición final (inclusive)
       6	      score	        Puntaje numérico o "." si no aplica
       7	      strand	      Hebra: "+" o "-" o "." si no aplica
       8	      phase	        Fase de lectura (0, 1, 2) o "." si no aplica
       9	      attributes	  Atributos en formato clave=valor; separados por ";"

  *Ejemplo de una línea:*
    chr1	Ensembl	gene	1000	5000	.	+	.	ID=gene0001;Name=BRCA1;Note=tumor_suppressor_gene

## Breve descripción del organismo _Gouania willdenowi._
De acuerdo a GBIF Secretariat (2023), el _G. willdenowi_ es un animal que habitas el mar mediterráneo en profundidades de entre 0.5 y 2 metros. Es conocido comúnmente cmo 'pez chupasangre de hocico romo' o 'pez chupasangre romo'. Este organismo difiere de especies cogenéricas por la combinación de las siguientes características: Perfil dorsal de la cabeza recto entre la nuca (encima del ojo) y la punta del labio superior, el ángulo posterior de las mandíbulas se extiende entre una línea vertical trazada por el borde posterior de la narina anterior y una línea vertical trazada por el borde anterior del ojo, la invaginación infraorbital vertical a la parte posterior del ojo, el borde opercular posterior en forma de W con dos puntas de igual longitud, las filas longitudinales infralaterales y filas transversales suborbitales de neuromastos superficiales ubicados en un surco profundo bien definido, la sección transversal del tronco detrás de la base de la aleta pectoral en forma de medio óvalo con lado ventral recto, los gránulos en el cuerpo poco profundos y poco visibles, entre otras. 

*Webgrafía:* 
> Gouania willdenowi (Risso, 1810) in GBIF Secretariat (2023). GBIF Backbone Taxonomy. Checklist dataset https://doi.org/10.15468/39omei accessed via GBIF.org on 2025-07-28.

## Preguntas que deben responderse desde la terminal:
i. ¿Cuantos features contiene el archivo?: 1623638
ii. ¿Cuantas regiones de la secuencia (cromosomas) contiene el archivo?: 441
iii. ¿Cuántos genes están listados en el organismo?: 23190
iv. ¿Cuál es el top 10 de tipo de features (columna 3) más anotados en el genoma?: 
  Número  Tipo               # anotaciones
    1     exón               740005
    2     CDS                698153 
    3     mRNA               698153
    4     five_prime_UTR     43296
    5     three_prime_UTR    32466
    6     gene               23190
    7     biological_region  21452
    8     ncRNA_gene         2979
    9     lnc_RNA            2471
    10    rRNA               757
