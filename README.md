# 410-Project

Scripts:
* 410 Project.ipynb:
  * Creates a figure named `figure_5.png` in the same file locations as this script. Also, if you can't run it as a normal python script, run it in a jupyter notebook. This requires files named `BeFree_STRING2.tsv`, `DisGeNet_STRING2.tsv`, `GOBP_STRING2.tsv`, `GWAS_STRING2.tsv`, and `MGI_STRING2.tsv` in the same location. These files can be generated with `410 Project Network Property Generator .ipynb`. Alternative, the code can be slightly altered to run with those same filenames but without the 2 at the end.
* 410 Project Network Property Generator .ipynb:
  * Creates the network properties. Requires the `data` folder which contains the folders `labels` and `networks`. The data can be downloaded from the following link: https://zenodo.org/record/3352348.
