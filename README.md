markerminer-docker
---
Targeted sequencing using next-generation sequencing (NGS) platforms offers enormous potential for plant systematics
by enabling economical acquisition of multilocus data sets that can resolve difficult phylogenetic problems. However,
because discovery of single-copy nuclear (SCN) loci from NGS data requires both bioinformatics skills and access to
high-performance computing resources, the application of NGS data has been limited.

[MarkerMiner](http://www.bioone.org/doi/full/10.3732/apps.1400115) is an easy-to-use, fully automated, open-access
bioinformatic workflow and application for effective discovery of SCN loci in flowering plants angiosperms
(flowering plants), from user-provided angiosperm transcriptome assemblies (e.g. [OneKP transcriptome assemblies](http://onekp.com).
It can be run locally or via the web, and its tabular and alignment outputs facilitate efficient
downstream assessments of phylogenetic utility, locus selection, intron-exon boundary prediction, and primer
or probe development.

This repository contains the configuration(s) necessary to build a CentOS 6.6 based Docker image which can be
used to run the MarkerMiner v1.0 pipeline.

Please refer to the [Docker Manual](https://www.bitbucket.org/srikarchamala/markerminer/src/HEAD/Docs/docker_MANUAL.md?at=master) 
for detailed instructions on instantiating a prconfigured MarkerMiner Docker container to run the supporting job submission web
application.

#### Citing MarkerMiner
If you use MarkerMiner in your research, please cite the following manuscript:

Chamala, S., García, N., Godden, G. T., Krishnakumar, V., Jordon-Thaden, I. E., De Smet, R., Barbazuk,
W. B., Soltis, D. E., and Soltis, P. S. (2015) **[MarkerMiner 1.0: A new application for phylogenetic
marker development using angiosperm transcriptomes](http://www.bioone.org/doi/full/10.3732/apps.1400115)**, *Applications in Plant Sciences*, 3(4): 1400115.
