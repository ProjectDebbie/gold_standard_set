# gold standard set  

The gold standard set is a list of PMIDs for abstracts selected to represent the biomaterials literature, with focus on biological evaluation of biomaterials and biocompatibility.

## Description 

To create the gold standard set, articles were identified using the following MeSH terms and keywords 'Biomaterials', 'Cell scaffolds', 'Biomedical and dental materials', 'Prostheses and implants', 'Materials testing','Tissue engineering', 'Tissue scaffolds', 'Equipment safety' and 'Medical device recalls' in PubMed. From these, 250 relevant articles were manually selected by scanning the records manually in approximately one-month intervals. Special effort was made to select articles with as many varying topics as possible. After a preliminary set of 251 relevant abstracts was selected manually, their
PubMed ID’s (PMIDs) were used to train the MedlineRanker classifier in order to rank all abstracts from the past 10 years by their similarity to the relevant set. The top 1000 ranked records, which are those considered to be most related to the topic of interest were manually scanned to remove reviews and added to the Biomaterials set. The final filtration step was the exclusion of records with no abstract, non-English records and records published earlier than 2004. The final biomaterials set contained 1173

## Pipeline (Add image in here)


## To Run the pipeline.  Ongoing work 

sh INSTALL.sh

## Built With
* [MedlineRanker](http://cbdm-01.zdv.uni-mainz.de/~jfontain/cms/?page_id=4)

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/ProjectDebbie/DEBBIE_pipeline/tags). 

## Authors

* **Javier Corvi** - **Austin McKitrick** - **Osnat Hakimi**

## License

This project is licensed under the GNU GENERAL PUBLIC LICENSE Version 3 - see the [LICENSE](LICENSE) file for details


	
		
