# RDS_Sociological_Methodology
## Networked Populations
Networked populations, and the code to generate them from the manuscript "Evaluation of respondent driven sampling prevalence estimators using real-world reported network degree"


There are eleven numbered populations, corresponding to the population numbers in Table 1 of the manuscript.

Within each folder are two files:

1. The neighbours.csv file which provides the connections for each node. 
For example, the first line for Population 1 is: 1,872,11985,10333 which indicates that node 1 connects to nodes 872,11985 and 10333
2. The node_attributes files which provides the id, degree and outcome status for each node.

## Modification to RDS-I Estimator
 The modified_RDS_rds_i_weights_function.R file contains a one-line change (highlighted) to the revised the transition matrix if there are no ties between groups.
 
## Citation
**to be determined**
