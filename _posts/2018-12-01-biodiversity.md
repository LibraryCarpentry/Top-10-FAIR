---
title: Biodiversity
---

## Sprinters

Eva Seidlmayer, Konrad Förstner, Mandela Fasemore, Silvia Di Giorgio, Till Sauerwein, Ilja Zeitlin, Susannah Bacon (ZB MED - Information Center for Life Science, Cologne, Germany), Chris Erdmann (The Carpentries, California Digital Library)

## Audience: 
Researchers

## Things

## Findability:

### Thing  1: Identifiers 

To make data findable, It has to be uniquely and persistently stored with an identifier. 

* A digital object identifier (DOI) is a unique, case-insensitive, alphanumeric character sequence and can be very helpful for this purpose. You can reach the identified digital object by using the DOI as a URL. Just fill in the DOI in the adress bar (e. g.  [https://doi.org/10.1109/5.771073](https://doi.org/10.1109/5.771073)). Also, see: [ANDS Guide: Digital Object Identifier (DOI) System for Research Data](https://www.ands.org.au/__data/assets/pdf_file/0006/715155/Digital-Object-Identifiers.pdf).

**NOTE:**
The distributing DataCite-agency for Life Sciences is PUBLISSO:  
[https://www.publisso.de/wir-fuer-sie/doi-service/](https://www.publisso.de/wir-fuer-sie/doi-service/)

* ORCID is a self-identifier for authors to avoid author name ambiguity. Use ORCIDs from the start of data creation, i.e. attach data creator name/ORCID to dataset as a metadata field. Include ORCIDs with datasets in repositories (e.g. in Sequence Read Archive (SRA), include the ORCID for the data creator).  This allows for the tracking of data provenance (the origins, custody, and ownership of research data). 

**EXERCISE:** 
For easy look up, we have a list of DOIs below. Can you match the right document to the appropriate DOI? HINT: Start from here [https://www.doi.org/](https://www.doi.org/)!

1) 10.1103/PhysRev.48.73
2) 10.5962/bhl.title.28875

* _On the origin of species_
* _The Particle Problem in the General Theory of Relativity_

Which of these is not a valid DOI ?

1) 10.1037/arc0000014
2) 12.1093/fMicb.2018.00257 
3) 10.1101/468025
HINT check the prefix!

Which part indicates the publishing institution? the prefix or the suffix of an DOI?

ORCID exercise: go through Getting Started with ORCID Integration https://members.orcid.org/api/getting-started 

### Thing 2: Citations

Zenodo for example is a tool that makes scientific data and publications easier to cite.  
It supports various data and license types. It also supports source code from GitHub repositories.

See [https://zenodo.org/](https://zenodo.org/)


**EXERCISE:** 
* Use the Zenodo Sandbox to upload an example dataset, software program, etc.  
[https://sandbox.zenodo.org/](https://sandbox.zenodo.org/)

Questions:  
1) Which metadata field do you have to add when uploading data and why? 
2) Which field are mandatory and which once are not. 
3) Which identifiers can you use. 

Todo: Screenshot of the upload form explaining some of the fields.


### Thing 3: Wikidata

It provides a common source of open data which can be used by Wikimedia projects such as Wikipedia, 
and by anyone else, under a public domain license.

https://www.wikidata.org/wiki/Wikidata

#### Exercise:
Go to Wikidata and find the publication date of the book “On the origin of species”.

- Switch over to the linked dataset of the author of the book and see his other publications.
- What did he published in 1839?


### Thing 4: Registry of research Data Repositories (re3data)

This project aims to accelerate scientific discovery and enhance the integrity, 
transparency, and reproducibility of data.
To enable FAIR data sharing, data need to be deposited in 
a repository that is taking steps to make data as open and FAIR as possible.
This is not clear-cut because at this time, there is no such thing as a FAIR 
stamp - although the CoreTrustSeal certification provides a good indication. 
Under the auspices of the Enabling FAIR Data Project, AGU, re3data, 
and DataCite therefore decided to develop a new tool to assist researchers
 in finding an appropriate repository for their data.

https://www.re3data.org/browse/by-subject/


#### Exercise:
1) How many entries are returned for the a query specific for your research topic on re3data https://www.re3data.org?
2) If you filter under subject what do you find?
3) Do you think something is missing from the results?
4) Please try to submit a missing repository


Try the Browse by Subject entry to the re3data-database 
since this gives a great overview on the wide landscape of research 
data repositories: https://www.re3data.org/browse/by-subject/




## Accessibility:

### Thing 5: Bioschema.org

Bioschemas aims to improve data interoperability in life sciences. 
It does this by encouraging people in life science to use schema.org markup, 
so that their websites and services contain consistently structured information. 
This structured information then makes it easier to discover, collate and analyse distributed data.

https://bioschemas.gitbook.io/training-portal/



### Thing 6: Licenses

Being well informed about the appropriate licenses will ensure data is available within the 
boundary intended by the authors and also enhance accessibility for target groups.

https://opensource.org/licenses
https://wiki.creativecommons.org/wiki/Data_and_CC_licenses
http://www.dcc.ac.uk/resources/how-guides/license-research-data

#### Exercise:
1) Use the link below to select the appropriate licence with the follow intentions,
2) Allow your work to be adapted and also allow it to be used commercially
- https://creativecommons.org/choose


### Thing 7: Availability via torrents

The era of Big Data is finally upon us, and Science is leading the trend. 
A prerequisite for accessibility is availability. Well established sharing protocols 
like torrents will ensure data is  perpetually available without the constraint of time and space.
Using the torrent protocol for scientific data will lead to some of the below advantages:
- Immutability 
- Distribution capabilities (lower cost for distributing the data) 
- no sole maintainer (we don’t have to rely only on one specific maintainer because data can be cloned and maintained across the peer-networks

The Magnet URI scheme defines the format of magnet links, a de facto standard for identifying files by their content, via cryptographic hash value rather than by their location.

Using Magnet URI scheme directly on the publication will make all the data accessible. 

http://academictorrents.com/
https://en.wikipedia.org/wiki/Magnet_URI_scheme

#### Exercise:
1) Upload any small data set of your choice with the above link 
2) Share with a colleague a link to access it over torrent 



## Interoperability:


### Thing 8: Elixir platforms  

Standardization of life science data will ensure interoperability across different sub fields. 
ELIXIR is an intergovernmental organisation that brings together life science resources 
from across Europe

https://www.elixir-europe.org/platforms/interoperability


### Thing 9: Research data management

- Bio2RDF is a large network of linked data for the life sciences. 
It provides a resource for different resources to be integrated into single platform

    http://bio2rdf.org/
    https://www.ncbi.nlm.nih.gov/pubmed/18472304

- GFBio is the authoritative, national contact point for issues concerning the management and standardisation of biological and environmental research data during the entire data life cycle (from acquisition to archiving and data publication). GFBio mediates expertises and services between the GFBio data centers and the scientific community, covering all areas of research data management.

    https://www.gfbio.org/


### Thing 10: Machine-readability 



Make the data accessible via an API for automated reading 

http://opendatahandbook.org/glossary/en/terms/machine-readable/


#### Exercise - Crossref:
1) Pick the DOI of a publication of your choice
2) Open a Web browser and add the url
3) https://api.crossref.org/works/<DOI> <= replace <DOI> with the DOI of the publication. 

Example: https://api.crossref.org/works/10.1371/journal.pcbi.1004668

#### Exercise - DataCite:
1) Pick the DOI of a dataset in Zenodo
2) Open https://api.datacite.org/works/DOI> <= replace <DOI> with the DOI of the Zenodo entry

Example https://api.datacite.org/works/10.5281/zenodo.1574835

## Reusability:
### Thing 11: Digitalization

If the methods to record complex experiments are prone to error, 
so that reproducible results cannot be guaranteed, how could you ever be sure you’re dealing with real insights and not random information?
The electronic lab notebook provides the missing infrastructure for data recording, 
retrieval and integrity.
An electronic lab notebook must be able to create, import, 
store and retrieve all important data types in digital format. 

https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5443717/
https://datamanagement.hms.harvard.edu/electronic-lab-notebooks

### Thing 12: Containers

In a scientific field we have most of the time deal with large amount of 
data that they have to be processed before the publication. 
One important aspect of the reproducibility challenge is ensuring computational analysis can be run reproducibly, even in different environments. 

https://www.cell.com/cell-systems/pdf/S2405-4712(18)30140-6.pdf
#### Exercise:
https://www.katacoda.com/courses/docker


### Thing 13: Blockchain for Life Science

This technology could be a technical solution to the 
current reproducibility crisis in science, and could "reduce waste and make more research results true"

https://hackernoon.com/mapping-the-blockchain-for-science-landscape-546b61bfbd1

https://www.researchgate.net/publication/306107836_Blockchain_for_science_and_knowledge_creation_-_A_technical_fix_to_the_reproducibility_crisis

https://zenodo.org/record/60223/files/ZenodoBlockchainforScienceKnowledgeCreation.pdf

Living document: 

https://www.blockchainforscience.com/2017/02/23/blockchain-for-open-science-the-living-document/




### Supplementary information:


Research Data Infrastructure for the Life Sciences (NFDI4Life) 

- NFDI4Life brings together research communities across the life sciences domain in the context of the planned National Research Data Infrastructure (NFDI). As a response to the increasing scientific and societal demand for data and data analysis, NFDI4Life brings together scientific communities and research data infrastructures broadly covering the life sciences with particular focus on the subdomains biology, medicine (with veterinary medicine), epidemiology, nutrition, agricultural and environmental science as well as biodiversity research.

    https://www.nfdi4life.de/ 

- Carpentries Community 

    The carpentries develops and teaches workshops on the fundamental data skills needed to conduct research. 

    https://carpentries.org/


- Go-FAIR-Initiative

    GO FAIR follows a bottom-up open implementation strategy for the European Open 
    Science Cloud (EOSC) as part of a broader global Internet of FAIR Data & Services. 
    
    https://eosc-portal.eu/ 
    
    https://www.go-fair.org/ 

- FAIRDOM

    FAIRDOM supports researchers, students, trainers, funders and publishers to make their data, operating procedures and models, Findable, Accessible, Interoperable and Reusable (FAIR).

    https://fair-dom.org/about-fairdom/



