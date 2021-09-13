# R_HLA-DPB1_permissive_matching
R code to perform DPB1 permissiveness matching on HLA-DPB1-mismatched donors.

V2.0 includes revised handling of the result of the online TCE tool hosted by the IMGT. There is now a new column which presents the result, as text, from the online tool. This result is then translated to a logical TRUE/FALSE result in a different column. 

V1.0 is the initial version of the code. This code determines HLA-DPB1 mismatches between BMT recipients and donors from a HistoTrac database, and then uses the DPB1 T-Cell Epitope Algorithm v2.0 tool hosted by the IMGT (https://www.ebi.ac.uk/ipd/imgt/hla/dpb_v2.html) to determine if mismatches are permissive or non-permissive.
