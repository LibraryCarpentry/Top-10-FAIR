---
title: "Biomedical Data Producers, Stewards, and Funders"
teaching: 0
exercises: 0
questions:
- "Key question"
objectives:
- "First objective."
keypoints:
- "First key point."
---


## Top 10 FAIR Things for Biomedical Data Producers, Stewards, and Funders


(these Things are not necessarily in any specific order - can be reordered, maybe based on priority or by stage in the research life cycle) 

**Thing 1: Metadata creation and curation**
* Various types of metadata
  * Descriptive
  * Technical
  * Administrative 
  * Provenance
* Use of controlled vocabularies and Common Data Elements, i.e. use of metadata consistent with the standards within the discipline. Activity: review CDE Resources https://www.nlm.nih.gov/cde/ 
* Standardized minimal/core metadata used across disciplines (or at least ability to crosswalk between standards)
Automated metadata creation (based on similar datasets)

**Thing 2: Use of standard data models**
* Example: OMOP data model https://www.ohdsi.org/data-standardization/the-common-data-model/ 

**Thing 3: unique persistent identifiers**
* DOI
* Handles
* Accession number
* ORCID - use ORCIDs from start of data creation, i.e. attach data creator name/ORCID to dataset as a metadata field. Include ORCIDs with datasets in repositories (e.g. in SRA, include the ORCID for the data creator).  Allows for tracking of provenance. 

**Activity:** go through Getting Started with ORCID Integration https://members.orcid.org/api/getting-started 
Enabling data citation

**Thing 4: Versioning and data “retirement”**
* Persistence of identifiers pointing to different/earlier versions 
* Maintaining previous versions of code, software, data 
* Sharing various levels of processed data (primary, secondary, or raw/clean/processed, etc)
* De-accessioning of data that has reached the end of its life cycle

**Thing 5: Linking research objects**
* Connecting code to data to paper (i.e. if I find a paper, I can get the data that goes with it, and vice versa, if I find some data, I can  find the paper that describes it)
  * Github repos, Zenodo code
  * Repositories with data
  * Articles
  * People who created the objects (ORCID)
  * Documentation for commercial software
* Graph database?

**Thing 6: Human and machine readability**
* API access
* Allows for automatic integration of multiple datasets
* Use of standard formats widely accepted in the discipline

**Thing 7: Maintain/preserve entire research environment (e.g. software)**
* Containerization
* Software preservation/emulation

**Things 8: Indexing repositories to enable findability**
* Register with re3data.org
* Use schema.org to get indexed with Google
* Listing in https://fairsharing.org/ 

**Thing 9: Broad consent**
* Informed consent for human subjects should be broad enough to make reuse possible
* https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4791589/
* Recommendations for Broad Consent Guidance: https://www.hhs.gov/ohrp/sachrp-committee/recommendations/attachment-c-august-2-2017/index.html 

**Thing 10: Application of metrics to evaluate the FAIRness of data/repository**
* There is a recent paper on this https://www.biorxiv.org/content/biorxiv/early/2018/09/16/418376.full.pdf
* And you might want to reference the  Make Data Count project… and Zenodo has an example of being the first repository to respond to Make Data Count http://blog.zenodo.org/2018/07/18/2018-07-18-usage-statistics/. 



Long-term preservation of biomedical research data: https://f1000research.com/articles/7-1353/v1

a design framework for exemplar metrics for FAIRness https://www.nature.com/articles/sdata2018118 
