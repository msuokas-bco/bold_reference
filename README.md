Quarto document contains updated worklow for creation of taxonomic reference sequence set from BOLD database. The document consists of R, bash and python codes. Sequence processing also utilises QIIME2 rescript plugins.

First part fetches CoI-5P data from BOLD database in multiple parts and creates a file containing over 13 M sequences with associated taxonomical classification and other metadata.

Second part filters low quality data in multiple steps.

Third part selects Arthoropod sequences and aligns them using guided alignment with LepiF1-LepiR1 CoI primers.

After full worklow primer specific sequence and taxonomy files are created as well as QIIME2 compatible trained naive bayesian taxonomy classifier.

