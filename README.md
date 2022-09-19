# Using AlphaFold to predict the impact of single mutations on protein stability and function

Data and code to the paper.

Pak M., Markhieva K, Novikova M., Petrov D., Vorobyev I., Maksimova E., Kondrashov F., Ivankov D. (2021). Using AlphaFold to predict the impact of single mutations on protein stability and function. bioRxiv 2021.09.19.460937; https://doi.org/10.1101/2021.09.19.460937.

`dataset_ddg.tsv` - Dataset of mutations from ThermoMutDB.

`dataset_gfp.tsv` - Dataset of GFP mutants.

`columns.txt` - Description of columns in datasets.

`blast.out` - Output of all-against-all BLAST of proteins in `dataset_ddg.tsv`.

`thermomutdb_v1.3.csv` - ThermoMutDB version 1.3 from http://biosig.unimelb.edu.au/thermomutdb/.

`thermomutdb_filtered.tsv` - ThermoMutDB after filtration as described in Methods.
