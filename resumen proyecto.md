#### Estructura poblacional de ***Stenocereus thurberi***

***Stenocereus thurberi***, es un cactus que se distribuye en Estados Unidos y la porción del noreste (Baja California, Sonora y Sinaloa) de México (Turner el al. 2005).
Se trata de una planta que puede alcanzar hasta los 8m de altura, tiene varias ramas que crecen desde el suelo. Esta planta produce el fruto conocido como pitaya. y tiene distintos polinizadores principalmente murciélagos 

Las secuencias fueron alineadas en clustalw, por medio de líneas de comando en Docker. Se utilizó un archivo .fasta como input y como output se obtuvieron: .aln(default), .fasta y un .nwk.

Se construyeron scripts en Rv3.4 para llevar a cabo algunos análisis exploratorios de la estructura genética de las doce poblaciones de *S. thurberi* utilizando los de genes ya mencionados.
En R, se intalaron algunas paqueterías pertenecientes a Bioconductor y algunas de R base.

Utilizando **pegas** se calcularon los valores que se muestran en la siguiente tabla: 
 

           | Div. nucleotídica | Theta  | D de Tajima  |  Haplotipos
    -------|-------------------|--------|--------------|-------------
    |G1trnF|    0.00043        |  0.53  |   -0.40      |     4
    |G2trnL|     1.062         | 0.0024 |    1.57      |     7

Además de redes de haplotipos. Estos resultados se obtuvieron siguiendo  el script *haplotipos.R*

![](https://github.com/RaquelHdz/Proyecto_Final_Bioinf2017-II/blob/master/haplotipos%20G1.png)

![](https://github.com/RaquelHdz/Proyecto_Final_Bioinf2017-II/blob/master/haplotipos%20G2.png)

Utilizando otras paqueterías como **adegenet**, **ape**, **poppr** entre otras se calcularon Gst pareadas, las cuales fueron ploteadas y las matrices que contienen los valores obtenidos se encuentran en la carpeta data/output.data.

Los gráficos son del Gen trnF y trnL, respectivamente.

![](https://github.com/RaquelHdz/Proyecto_Final_Bioinf2017-II/blob/master/Gst%20Gen1.png)

![](https://github.com/RaquelHdz/Proyecto_Final_Bioinf2017-II/blob/master/Gst%20Gen2.png)


(Conclusión personal: Ha sido muy útil haber llevado un curso de bionformática que aunque me ha costado he aprendido mucho... y si los for loops fueran amables conmigo sería mejor, pero aún no nos llevamos bien :(  )


**Referencias**

Turner RM, JE. Bowers y TL Burgess. 2005. Sonoran Desert Plants: An Ecological Atlas. University of Arizona Press, 504pp. 