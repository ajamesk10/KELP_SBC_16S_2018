# KELP_SBC_16S_2018
16S Sequencing Analysis of Kelp Microbiomes from the Santa Barbara Channel - 2018

*Information about microbiome samples:*

This code processes raw sequencing reads from a study of Giant Kelp microbiomes. 
Sampels were collected using stand up paddle boards at two kelp beds in the Santa Barbara Channel: Arroyo Quemado (AQ: 34° 28.127′ N, 120° 07.285′ W) and Mohawk Reef (MR; 34° 23.660′ N, 119° 43.800′ W) from May to August, 2018.
Seawater samples were also collected as part of this project and to compare kelp microbiomes to microbial communities in the surrounding water column.
Gene amplicons of the V4 region of the bacterial 16S rRNA gene were generated using 515F and 806R-B primers as described by Wear et al. (2018). 
Sequencing was conducted at the University of California, Davis DNA Technologies Core on an Illumina MiSeq using PE250.
This work was conducted by AK James, CJ English, N Nidzieko, CA Carlson, and EG Wilbanks.

*Information about code:*

This code processes pre-trimmed (w/o primers) sequences through the DADA2 pipeline and then uses an admittedly (really) clunky script to visualize and statistically analyze these 16S sequences.
