# Opdracht Bachelor

Cell type deconvolution is a computational technique to estimate cell type proportions of mixtures (bulk). This allows to compare differences in proportions of specific cell types between two (or multiple) groups. Examples are differences in immune cell types or the proportion of tumor derived materials. Both applications are research topics in the lab. To perform a more optimal deconvolution a good marker set is needed and therefore single cell data is often generated. MuSIC is a Bioconductor package which performs deconvolution. For this exercise, we ask you to perform deconvolution with MuSiC (https://xuranw.github.io/MuSiC/articles/MuSiC.html) on bulk RNA-sequencing samples of ALS patients. We want to explore the proportions of the distinct immune cell types and compare these to healthy donor PBMCs. The bulk data was downloaded for you from this paper (https://www.nature.com/articles/sdata20196) and saved as a tsv file. To characterize immune cells in depth, single cell data is needed. In this case, we will use public data of PBMCs. This data was saved as an ‘SingleCellExperiment’ object in the rds file that is provided to you, you can read the data by using the readRDS function in R. The file can be downloaded through: https://ugentbe-my.sharepoint.com/:u:/g/personal/celine_everaert_ugent_be/EbaNogtJe7BMhUhY18-OWzsBjKzE3gCNR543WickvZ5dHg?e=BQK1SU

When you obtained the resulting proportions by running MuSIC, we would like to see the results in some nice figures. Bundle everything in a RMarkdown file and knit it to a html so we can see your results.

If you encounter errors, or have questions you can contact us by mail.

Some code to start with is availble to you in de RMarkdown notebook.




