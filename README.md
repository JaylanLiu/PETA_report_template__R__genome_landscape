# PETA_report_template__R__genome_landscape
PETA report template using IR kernel to illustrate genome landscape

## uthor
JilongLiu

liujilong@genomics.cn

## upported data
All genomics records with mutation as TCGA`s MAF format.

## Analysis
Use Bioconductor`s maftools library:
1. Variants distribution in Sample level
1. Variants distribution in Gene level
1. oncoprint
1. maf summary
1. Ti/Tv 
1. mutation count comparian with TCGA
1. mutant gene cloud
1. somatic interactions


## Usage
Supposed that you have access to BGI-PETA database and to the selected data set:
```
$jwr -i PETA_report_template__R__genome_landscape.ipynb -o PETA_report_template__R__genome_landscape.html --json_str xxx --token xxx
```
'xxx' should replace your information.
