# ACTIVIDAD GRUPAL. Github: Crear un repositorio github. Control de versiones
## Introducción a la Programación Científica · UNIR · 2026/2027
### Grupo 9: Buzón Martínez, José Manuel · Cabeza Flores, Laura · Lorenzo Fernández, Andrea · Sapiña Hernández, Esther · Camero Casares, Jose Manuel

La siguiente actividad refleja un proyecto teórico de bioinformática con el propósito de establecer y dar contexto a la actividad realizada. Se expone un proyecto genérico en el que se pretende realizar un análisis de asociación del genoma completo (GWAS) basándonos en bibliografía. 

Bibliografía: 
Choi, S. W., Mak, T. S.-H., & O’Reilly, P. F. (2020). Tutorial: a guide to performing polygenic risk score analyses. Nature Protocols, 15(9), 2759–2772. https://doi.org/10.1038/s41596-020-0353-1
Marees, A. T., de Kluiver, H., Stringer, S., Vorspan, F., Curis, E., Marie-Claire, C., & Derks, E. M. (2018). A tutorial on conducting genome-wide association studies: Quality control and statistical analysis. International Journal of Methods in Psychiatric Research, 27(2), e1608. https://doi.org/10.1002/mpr.1608


## Proyecto:
Se plantea un proyecto en el que se pretende realizar un análisis de asociación del genoma completo de individuos para determinar la susceptibilidad genética de los individuos al desarrollo de una enfermedad. 
Los datos genéticos de los pacientes se obtienen a partir del genotipado de muestras biológicas de pacientes controles o sanos y pacientes diagnosticados con la enfermedad utilizando la tecnología de los microarrays.
Los datos genotipados obtenidos deben ser filtrados y depurados atendiendo a controles de calidad (QC). Para ello se eliminan las variantes o SNPs duplicados, aquellas que se desvían del equilibrio de Hardy-Weinberg y aquellas con frecuencias alélicas extremadamente raras, entre otros QC. 
Posteriormente se realiza la imputación de los datos filtrados. La imputación consiste en ampliar la información de los datos genotipados utilizando genomas de referencia para "rellenar huecos" atendiendo a la herencia de dichas variantes y de sus genes adyacentes. Es importante tener en cuenta la ascendencia genética de los pacientes controles y afectados para determinar el uso de un genoma de referencia que se adecue y represente a nuestra muestra de la población. 
Tras la obtención de nuestros datos imputados obtenemos un p-valor para cada variante genotipada e imputada y utilizamos métodos de estadística para determinar la relación entre dichas variantes y los fenotipos de nuestras muestras (control o afectado). Esto lo podemos determinar para cohortes individualmente o para el conjunto de las cohortes mediante un metaanálisis con la finalidad de tener un mayor poder estadísticos al sumar las N de cada cohorte. 
Finalmente, realizamos un análisis del desequilibrio de ligamiento a partir de las variantes asociadas y/o sugestivas para la susceptibilidad a la enfermedad estudiada para determinar el impacto genético la herencia de dichas variantes patogénicas en el genoma de los individuos.
