ENSO metrics package for climate model evaluation
Metrics and collections devised by CLIVAR ENSO group

Contact details:
Eric Guilyardi <eric.guilyardi@locean-ipsl.upmc.fr>
Yann Planton <yann.planton@locean-ipsl.upmc.fr>

**Install The Package on Gdai**
1. refer to the package main wiki https://github.com/CLIVAR-PRP/ENSO_metrics/wiki/Install-using-conda-forge-(recommended)
2. run "conda create -n [YOUR_CONDA_ENVIRONMENT] -c conda-forge enso_metrics" on Gadi
3. you files will be located at "/scratch/p66/ars599/conda/envs/enso_metrics"

**Preperation**
1. enso
2. ls /g/data/p66/ars599/CMIP6/APP_output/CMIP6/CMIP/CSIRO-ARCCSS/ACCESS-CM2/piControl/r3i1p12f1/Amon/ts/gn/v20231104/ts_Amon_ACCESS-CM2_piControl_r3i1p12f1_gn_1* > path_to_xml_file/ts_Amon_piControl_r3i1p12f1_list_files
3. cdscan -x path_to_xml_file/ts_Amon_piControl_r3i1p12f1.xml -f path_to_xml_file/ts_Amon_piControl_r3i1p12f1_list_files

