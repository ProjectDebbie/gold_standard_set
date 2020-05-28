# gold standard set  

The gold standard set is a list of PMIDs for abstracts selected to represent the biomaterials literature, with focus on biological evaluation of biomaterials and biocompatibility.

## Description 

To create the gold standard set, articles were identified using the following MeSH terms and keywords 'Biomaterials', 'Cell scaffolds', 'Biomedical and dental materials', 'Prostheses and implants', 'Materials testing','Tissue engineering', 'Tissue scaffolds', 'Equipment safety' and 'Medical device recalls' in PubMed. From these, 250 relevant articles were manually selected by scanning the records manually in approximately one-month intervals. Special effort was made to select articles with as many varying topics as possible. After a preliminary set of 251 relevant abstracts was selected manually, their
PubMed ID’s (PMIDs) were used to train the MedlineRanker classifier in order to rank all abstracts from the past 10 years by their similarity to the relevant set. The top 1000 ranked records, which are those considered to be most related to the topic of interest were manually scanned to remove reviews and added to the Biomaterials set. The final filtration step was the exclusion of records with no abstract, non-English records and records published earlier than 2004. The final biomaterials set contained 1173

## Built With
* [MedlineRanker](http://cbdm-01.zdv.uni-mainz.de/~jfontain/cms/?page_id=4)
* [PubMed eBOT](https://www.ncbi.nlm.nih.gov/Class/PowerTools/eutils/ebot/ebot.cgi) 

## Versioning

Versions are named after their content emphasis as well as the number of PMIDs.

clinical_only_106 denotes 106 PMIDs with clinical studies of biomaterials and implants 
gs_mixed_1230 denotes 1230 PMIDs with all study types (in vitro, in vivo, clinical etc) 
gs_extra_clinical_1329 denotes 1329 PMIDs with all study types, with added clinical studies


## Authors

**Osnat Hakimi**

## License

This project is licensed under the GNU GENERAL PUBLIC LICENSE Version 3 - see the [LICENSE](LICENSE) file for details


## Citation

@article{doi:10.1002/adfm.201909910,
	author = {Hakimi, Osnat and Gelpi, Josep Luis and Krallinger, Martin and Curi, Fabio and Repchevsky, Dmitry and 	Ginebra, Maria-Pau},
	title = {The Devices, Experimental Scaffolds, and Biomaterials Ontology (DEB): A Tool for Mapping, Annotation, and 	   Analysis of Biomaterials Data},
	journal = {Advanced Functional Materials},
	volume = {30},
	number = {16},
	pages = {1909910},
	keywords = {biomaterials, databases, ontology},
	doi = {10.1002/adfm.201909910},
	url = {https://onlinelibrary.wiley.com/doi/abs/10.1002/adfm.201909910},
	eprint = {https://onlinelibrary.wiley.com/doi/pdf/10.1002/adfm.201909910},
	year = {2020}
}



	
		
