# Master Thesis
Repo containing stuff related to my master thesis.

## Experiment Data
The data for the experiments is too large for Github LFS, therefore it needs to be downloaded from here: https://1drv.ms/u/s!AkykgxUUl4FugZoMIPaODffIT1hXDA?e=ac23d2. All files from that folder should be copied into a subfolder called 'experiments'.

## Folder Structure
1. Analysis_Final - contains the generated comparisons of symbolic & subsymbolic models
2. Experiments - contains the experiment data, the aggregated experiment data & the datasets 
3. Proposal - contains LaTex files for the thesis proposal 
4. Temp - contains precalculated data for more complex operations 
5. Thesis - contains LaTex files for the final thesis 
6. Testsets - contain the generated testsets

## File/ Code Structure
1. analysis_all.ipynb - is used to generate the analysis for all dataset/ model combinations
2. analysis_{dataset}.ipynb - is used to generate the analysis for one dataset
3. format_predictions - aggregates the data retrieved from AnyBURL & libkge experiments
4. graphs - contains the code to generate the content for the analysis 
5. utils - provides utility functions for all other notebooks
6. evaluate_anyburl_on_testsets & evaluate_kge_on_testsets - evaluates models on the generated testsets
7. output_kge_metrics - prints relevant metrics for all kge models
