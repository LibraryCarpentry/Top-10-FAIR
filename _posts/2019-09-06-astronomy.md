# Top 10 FAIR Data and Software Things for Astronomy


# Sprinters:



*   Maria Cruz [https://orcid.org/0000-0001-9111-182X](https://orcid.org/0000-0001-9111-182X)
*   Chris Erdmann [https://orcid.org/0000-0003-2554-180X](https://orcid.org/0000-0003-2554-180X)
*   Kristina Hettne [https://orcid.org/0000-0002-4182-7560](https://orcid.org/0000-0002-4182-7560) 
*   Francoise Genova [https://orcid.org/0000-0002-6318-5028](https://orcid.org/0000-0002-6318-5028) 
*   Matthew Kenworthy [https://orcid.org/0000-0002-7064-8270](https://orcid.org/0000-0002-7064-8270)
*   Natalie Meyers [https://orcid.org/0000-0001-6441-6716](https://orcid.org/0000-0001-6441-6716)
*   Evert Rol [https://orcid.org/0000-0001-8357-4453](https://orcid.org/0000-0001-8357-4453)
*   Juande Santander-Vela [https://orcid.org/0000-0002-2660-510X](https://orcid.org/0000-0002-2660-510X)
*   Joanne Yeomans [https://orcid.org/0000-0002-0738-7661](https://orcid.org/0000-0002-0738-7661) 


# Brief description

Much has already been done in the area of Astronomy with regards to data management and software management. For example, the [International Virtual Observatory Alliance (IVOA)](http://www.ivoa.net) is the collegiate organisation that supports the Virtual Observatory as a federation of astronomical archives and datasets through the standardisation of data formats and data access protocols, and also underlying data models. The goal for the Virtual Observatory is that astronomical datasets and other resources should work together in a seamless whole. The IVOA develops and agrees on the standards underlying the Virtual Observatory. 

This document intends to connect a few of these efforts to the **FAIR** principles - **F**indable, **A**ccessible, **I**nteroperable and **R**eusable -  and introduce general activities that can be undertaken towards “FAIRness”. They can be used for researchers to become more FAIR aware, or by librarians or other research data support staff as an inspiration for training. The document is structured into informative small pieces of text (so-called “Things”) to jump-start activities a researcher can do to make their data and software more FAIR. They do not have to be followed in a particular order, you can just pick and choose. We have sorted the “Things” under the respective FAIR category they belong to. 

A related previous effort by the Australian National Data Service is the [10 Astronomy Things.](https://github.com/ADACS-Australia/10_Astronomy_Things/blob/master/10AstronomyThings.pdf)


# Audience

Early Career researchers, Research Data support staff


# Goals

The goals of this document are to raise awareness and give practical advice and exercises as a starting point towards “FAIRness”. The aim is not to be comprehensive, but to provide a teaser for those wanting to know more.


# Findable


## Thing 1: Finding and sharing data and software

_Relates to [F4: (Meta)data are registered or indexed in a searchable resource](https://www.go-fair.org/fair-principles/f4-metadata-registered-indexed-searchable-resource/)_

Astronomy has a long tradition of sharing and reusing data. Astronomical data can be found and accessed in many different forms and ways. Raw and processed data can be accessed from major observatory archives (e.g. the [ESO Archive](http://archive.eso.org/cms.html)). There are also collections of astronomical catalogues (e.g. [VizieR](http://vizier.u-strasbg.fr/index.gml)) providing tables and associated data published in academic journals, and databases (e.g. [SIMBAD Astronomical Database](http://simbad.u-strasbg.fr/simbad/)), providing information on astronomical objects of interest. The [Astrophysics Source Code Library (ASCL)](http://ascl.net/) is a free online registry for source codes of interest to astronomers and astrophysicists and lists codes that have been used in research and that have appeared in, or have been submitted to, peer-reviewed publications. 

**Activity 1:**

Go to the[ re3data.org](https://www.re3data.org/) registry of research data repositories and search for astronomical data or software repositories that may be relevant to your area of research. Try it out by typing “astronomy” into the search box. Compare the query form with the [web interface](http://dc.zah.uni-heidelberg.de/wirr/q/ui/fixed) of the IVOA registry of resources. The IVOA registry of resources is mostly to enable discovery of and access to data and services available through the Virtual Observatory by programmes.

**Activity 2:**

Learn how to search for data through [filtering your search](https://adsabs.github.io/help/search/filter) in the [NASA Astrophysics Data System (ADS)](https://ui.adsabs.harvard.edu/). Find out how you can navigate to data products for records/papers via the data/database icon in the ADS.

**Activity 3:**

Consider attending a [dotastronomy.com](https://www.dotastronomy.com) conference or an [AstroHackWeek](http://astrohackweek.github.io/) and learn about tools for collaboration and sharing. If not feasible, try perusing the conference videos of[ dotastronomy.com](http://dotastronomy.com), or those from the [AstroHackWeek 2015](https://www.youtube.com/channel/UC7BUtrXxvkaKn6QLWKdmzCw) or [2016](https://www.youtube.com/playlist?list=PLKW2Azk23ZtQSHmwOpObPEr58Pe1rpIdB).


## Thing 2: Metadata

_Relates to [F2: Data are described with rich metadata](https://www.go-fair.org/fair-principles/f2-data-described-rich-metadata/)_

Metadata is “data about your data”. It provides context about the actual data, makes the data more findable and categorizable, provides some idea about the quality of data, etc. (see [Wikipedia](https://en.wikipedia.org/wiki/Metadata#Definition) summary). For example, the license for the data is also metadata. Metadata often exists in headers of the actual data files. Additionally, metadata exists in the database of, for example, observatories or journals. If metadata is recorded in the file itself, it is still preserved even if the other metadata resources are not available.

The types of metadata will be dependent on the field, data format, used software tools, and possible related publications (or publishers). Separate them as necessary, and include relevant standards when possible (for example, in a data header, the metadata standard may be mentioned first, then a list of metadata), so that the meaning of keywords can be looked up. Avoid using filenames to record metadata: these can accidentally change, meaning that metadata will be lost.

The FITS format is widely used in astronomy, in particular for observational data. A FITS file contains data and the relevant metadata that describes, at a minimum, the instrument used and the observation parameters, such as its sky coordinates. Another example of how metadata are organised in astronomy is the standard description of a “catalogue” (a table or a set of tables) in VizieR, stored in the ReadMe file, which contains information about the dataset and for each table a description of the quantity contained in each column.

Specific astronomy-related types of metadata:



*   [IVOA standards](http://ivoa.net/documents/)
*   [FITS keyword dictionaries](https://fits.gsfc.nasa.gov/fits_dictionary.html)
*   [World Coordinate System](https://fits.gsfc.nasa.gov/fits_wcs.html)
*   Observatory, telescope & instrument information & configuration
*   [Astrophysical simulations](http://www.spase-group.org/data/)
*   [Astronomy Visualisation Metadata](https://www.virtualastronomy.org/avm_metadata.php)

**Activity 1:**

Verify that your current data contains at least the items listed in the Wikipedia section.

**Activity 2:**

Examine the ReadMe file of a VizieR “catalogue”, for instance [J/A+A/620/A89](http://cdsarc.u-strasbg.fr/viz-bin/cat/J/A+A/620/A89). The dataset is a table from a paper published in _Astronomy and Astrophysics_ (you can have a look at the paper from the catalogue page). Could you reuse a similar template to describe your own data, even if you are not an astronomer? (See Thing 5, Activity3 if you want a description of the template)

**Activity 3:**

[Sign up](http://mail.ivoa.net/mailman/listinfo/ivoa-news) for the [IVOA newsletter](http://www.ivoa.net/newsletter/index.html) to stay informed about recent developments


## Thing 3: Persistent identifiers

_Relates to [F1: (Meta)data are assigned globally unique and persistent identifiers](https://www.go-fair.org/fair-principles/f1-meta-data-assigned-globally-unique-persistent-identifiers/)_

Persistent identifiers prevent “link rot”, the process by which web links stop referring to the original sources over time, rendering these sources unavailable. If you store your data or software on your own or your institute’s website you are likely to fall foul of this problem. Assigning a globally unique, persistent identifier (such as a [DOI](https://www.doi.org/)) to your data, software, and their metadata is one of the first and most important steps towards FAIR, as it will make your research outputs findable and accessible to both humans and machines in the long term. It will also make it easier to cite your research outputs as independent citable objects and to link them to related publications.

Depositing your data and/or code in a repository that assigns a persistent identifier (e.g. [Zenodo](https://zenodo.org/)) is the easiest way to get one. Disciplinary repositories more and more provide persistent identifiers. Persistent identifiers usually come packaged with metadata — often following metadata standards, e.g. the [DataCite's Metadata Schema](https://schema.datacite.org/). And these metadata are usually registered or indexed in searchable resources, such as the [DataCite](https://datacite.org/search.html). 

**Activity 1:** 

Some major observatories, such as [ESO](https://www.eso.org/) and [MAST](http://archive.stsci.edu/), are starting to move to using DataCite DOIs. Read more about some of these initiatives to get familiar with the concept of assigning DOIs to datasets in the context of astronomy and astrophysics: [The ESO Digital Object Identifier Service](https://www.eso.org/sci/publications/messenger/archive/no.173-sep18/messenger-no173-38-39.pdf) and [About DOIs at MAST](https://archive.stsci.edu/doi/search/).

**Activity 2:**

Identifiers exist for researchers as well. [ORCID](https://orcid.org/) is a persistent digital identifier for researchers that helps connect research to researchers. It helps to distinguish you from every other contributor, particularly useful if you have a common name, and it supports automatic links between your various research outputs and activities. Go to the [ORCID website](https://orcid.org/) and create an ORCID profile if you do not have one already. Then learn how to [claim your papers using the NASA ADS](http://adsabs.github.io/help/orcid/claiming-papers).


# Accessible


## Thing 4: Access regulation

_Relates to [A1.2: The protocol allows for an authentication and authorisation when necessary](https://www.go-fair.org/fair-principles/a1-2-protocol-allows-authentication-authorisation-required/)_

It is crucial to know that the “[Accessible](https://www.go-fair.org/fair-principles/metadata-retrievable-identifier-standardised-communication-protocol/)” requirement in FAIR does not have to mean “open” or “free”. Or in other words, it can be “[as open as possible, as closed as necessary.](https://openscholarchampions.eu/opendata/champion/asopenaspossibleasclosedasnecessary/)” According to the [GO FAIR website](https://www.go-fair.org/fair-principles/a1-2-protocol-allows-authentication-authorisation-required/): _“Rather, it implies that one should provide the exact conditions under which the data are accessible. Hence, even heavily protected and private data can be FAIR.”_ The actual protocol for accessibility is often taken care of by the repositories and infrastructures that offer data storage and is less of a concern for individual researchers. However, as a researcher, you should think about _who_ can access the actual data and how, so that when you deposit your data you can pick the right level of access. 

Embargoes in astronomy are one way that data are not necessarily open from the start. Embargoes provide researchers who got observation time on a telescope in a competitive process with a proprietary period of time to work with the data they have obtained before it is opened to the general research community and public. See the ESO Archive Frequently Asked Questions: [Getting Data: How is the proprietary period of data regulated?](https://archive.eso.org/cms/faq/how-is-the-proprietary-period-of-service-mode-data-regulated.html)

**Activity:**

Read the [European Southern Observatory data access policy](https://archive.eso.org/cms/eso-data-access-policy.html). When do data become publicly available?


# Interoperable


## Thing 5: Data structuring and organization

_Relates to [I1: (Meta)data use a formal, accessible, shared, and broadly applicable language for knowledge representation](https://www.go-fair.org/fair-principles/i1-metadata-use-formal-accessible-shared-broadly-applicable-language-knowledge-representation/)_

Ensure the data is in an accessible format; standard file formats such as CSV, JSON, HDF5, FITS (astronomy only) work. Many tools exist that can read such files, even for data online. This makes the data Findable, potentially even by search engines, as well as Interoperable with (other) software. On the GO FAIR [home page](https://www.go-fair.org/fair-principles/i1-metadata-use-formal-accessible-shared-broadly-applicable-language-knowledge-representation/) the following data formats that satisfy the requirements for [Linked Data](https://en.wikipedia.org/wiki/Linked_data) are mentioned: Resource Description Framework (RDF) and JavaScript Object Notation for Linked Data (JSON LD). 

Ensure the data are logically structured: this may be within the data itself (multi-extension FITS files; HDF5 is inherently structured), or through the use of directories. This makes it easier (for humans, mainly) to find and use (parts of) the data. Be careful not to just rely on filenames, since these are (too) easy to change (see also Thing 2 about metadata).

Units should not be forgotten. Often, units will be indicated through the metadata, and when done according to relevant standards, tools and libraries should automatically use them. For FITS, section 4.3 of the [FITS standard](https://fits.gsfc.nasa.gov/standard40/fits_standard40aa-le.pdf) specifies the use of units. In HDF5, units are often defined using a separate (one-dimensional) dataset. For representation of units, see also the [IVOA units recommendation](http://www.ivoa.net/documents/VOUnits/).

Note: data published in a table in an article is _also_ data. Publish the table data separately in a standard file format (e.g., CSV); don’t rely on, say, just a LaTeX table, even if journals, [ADS](https://ui.adsabs.harvard.edu/), or [CDS](http://cdsweb.u-strasbg.fr/) are able to scrape and read this. Never forget that you should provide enough metadata with the file so that it is reusable and its origin is known (See Thing 2).

**Activity 1:**

Have a critical look at your own data files: are they well structured and in an interoperable format?

**Activity 2:**

Make a list of the different data formats that you are using, and try to see if they correspond to well (preferably online) documented formats, and collect those links.

**Activity 3:**

Look into your data/data tables. Do you have everything ready for them to be published? You can use a checklist such as this one from [VizieR table submission](http://vizier.u-strasbg.fr/vizier/submit.htx).


## Thing 6: Terminology

_Relates to [I1: (Meta)data uses vocabularies that follow the FAIR principles](https://www.go-fair.org/fair-principles/i2-metadata-use-vocabularies-follow-fair-principles/)_

The [Unified Astronomy Thesaurus (UAT)](http://astrothesaurus.org), a reference work that lists words grouped together according to similarity of meaning, builds on prior controlled vocabularies used in astronomy. The aim of the UAT is to create a high quality open, interoperable and community-supported thesaurus that is freely-available and formalizes astronomical concepts and their inter-relationships. The development and maintenance of the UAT is stewarded by a broad group of parties having a direct stake in it, including professional associations ([IVOA](http://ivoa.net/), [IAU](https://www.iau.org/)), learned societies ([AAS](https://aas.org/), [RAS](https://ras.ac.uk/)), publishers ([IOP](https://ioppublishing.org/), [AIP](https://publishing.aip.org/)), librarians and other curators working for major astronomy institutes and data archives. The goal of the UAT is to ultimately improve the discovery of astronomy research including papers, software, data products and services.

**Activity 1:**

[Explore the UAT](http://astrothesaurus.org/thesaurus/) and/or [select concepts](http://astrothesaurus.org/concept-select/) that you can use to describe your papers, software, and/or data.

**Activity 2:**

Learn more about the UAT by reading [Katie Frey and Alberto Accomazzi (2018): The Unified Astronomy Thesaurus: Semantic Metadata for Astronomy and Astrophysics](https://iopscience.iop.org/article/10.38a47/1538-4365/aab760/meta). 


## Thing 7: FAIR data modelling

_Relates to [I1: (Meta)data use formal, accessible, shared, and broadly applicable language for knowledge representation](https://www.go-fair.org/fair-principles/i1-metadata-use-formal-accessible-shared-broadly-applicable-language-knowledge-representation/), [R1: (Meta)data are described with a plurality of accurate and relevant attributes](https://www.go-fair.org/fair-principles/r1-metadata-richly-described-plurality-accurate-relevant-attributes/) and [R1.3: (Meta)data meet domain-relevant community standards](https://www.go-fair.org/fair-principles/r1-3-metadata-meet-domain-relevant-community-standards/)_

Data modelling is the process by which terminology and a framework for the terminology comes together. From [Juande Santander-Vela (2009)](https://arxiv.org/abs/0901.2520v1): _“Data models are the detailed description of the set of entities needed for information storage in a particular field, and specify both the data being stored, and the relationships between them. Data models are part of the hidden VO infrastructure astronomers would normally never be involved with, but knowledge of data models can enhance the opportunities for the exploitation of the VO.”_

The Virtual Observatory has two standards that have to do with data modelling: Universal Content Descriptors (UCDs) and UTypes. Universal Content Descriptors describe in general terms, by means of a restricted but expandable vocabulary, which kind of astronomical concept a particular value (and unit) corresponds to. For instance, a column in a table can have the UCD `pos.eq.ra`, indicating that a value corresponds to a right ascension in equatorial coordinates (one of the sky coordinate systems). If each row contains the position of multiple objects (for instance, of the Sun, the moon, and the target object ), additional UCDs can be composed, so that the more precise `pos.eq.ra; meta.main` can be used for the observed source’s Right Ascension, and the rest of the right ascensions are codified with just `pos.eq.ra`. The latest list of the UCD vocabulary is provided by [Andrea Preite Martinez et al. (2018)](http://www.ivoa.net/documents/UCDlistMaintenance/20180823/index.html). The CDS has a page with lots of [useful tools for UCDs](http://cdsweb.u-strasbg.fr/UCD/), such as those to decode UCDs, or to generate UCDs from natural language descriptions, among other things.

UTypes are a feature of the VOTable —see section 4.6 of [Ochsenbein et al. (2013)](http://www.ivoa.net/documents/latest/VOT.html)— which can indicate exactly to which piece of a given Data Model (expressed as an XML Schema) a particular metadata item refers to. This is much more technical than the UCD, but it can also be very useful in order to generate machine-readable astronomical datasets.

For **FAIR** data modelling it is important that the terms have resolvable, globally unique and persistent identifiers and that the framework is well-defined. See also Things 2, 5 and 6.

**Activity 1:**

Check out this [presentation on data modelling within the IVOA](https://wiki.ivoa.net/internal/IVOA/IvoaDataModel/Louys_Mireille_30876-AdassTalk.pdf) by M. Louys, which describes the work of the [IVOA Data Model Working group](https://wiki.ivoa.net/twiki/bin/view/IVOA/IvoaDataModel). Why is interoperability important for VO users?

**Activity 2:**

Go to the page of CDS’ [useful tools for UCDs](http://cdsweb.u-strasbg.fr/UCD/) and try to use it to build UCDs for different concepts, such as photometric magnitude in the _i_ band, or the difference in _g_-_i_ colours. Can you find concepts that are not easily expressed as UCDs? Can you imagine a similar tool in fields outside of astronomy?

**Activity 3**

On the  [GO FAIR home page](https://www.go-fair.org/fair-principles/i1-metadata-use-formal-accessible-shared-broadly-applicable-language-knowledge-representation/) the following formats are mentioned: [Resource Description Framework (RDF)](https://www.w3.org/RDF/), [W3C Web Ontology Language (OWL)](https://www.w3.org/OWL/), [DARPA Agent Markup Language (DAML+OIL)](http://www.daml.org/language/), [JavaScript Object Notation for Linked Data (JSON LD)](https://json-ld.org/). Note that RDF and JSON LD can be used to model the data as well as the metadata. Have a look at this document on [Vocabularies in the Virtual Observatory](http://www.ivoa.net/documents/latest/Vocabularies.html). Which format is recommended by the IVOA to use for modelling vocabularies?


# Reusable


## Thing 8: Licensing

_Relates to [R1.1: (Meta)data are released with a clear and accessible data usage license](https://www.go-fair.org/fair-principles/r1-1-metadata-released-clear-accessible-data-usage-license/)_

If you don’t apply a licence to your data telling people up front how they can use it, then you may have to deal with emails from people asking this question in the years to come. And if a future researcher doesn’t know how they can use your data, then they may not want to use it at all. This is especially important when it comes to software as others may wish to adapt and make derivatives of the original code which they legally cannot do without permission. For this reason it’s useful to apply a licence to improve the re-usability of your data and software.

 

Licences can be hand-written by anyone (although this is not recommended!) and you will commonly find such ‘licences’ on many existing websites for astronomy software and data. They are often not called a licence, and are often not complete from a legal standpoint. It may be, however, that by contributing to certain software you are agreeing to make it available without restriction, which is by implication, an open source or “all rights waived” licence. Astronomy has been sharing data openly, eventually after an embargo period, for decades, and even before the foundation of Creative Commons in 2001. In addition to the ‘hand-written licences’ provided in some cases, “data provided by others must be cited appropriately, even if obtained from a public database”, as stated in the [Ethics Statement of the American Astronomical Society](https://aas.org/about/policies/aas-ethics-statement). The absence of formal licence practices has not been an obstacle to widespread and mostly fair usage of shared data in the discipline, but the astronomy case cannot be generalised. 

 

The lack of clarity is why it’s advisable to use a pre-defined licence like those offered by Open Source Initiative or Creative Commons (CC). These are often written by legal experts and allow you to choose the terms that best match the conditions you wish to apply. 

 

**Activity 1:**

Take a look at this [comprehensive introduction to licensing research data from the Digital Curation Centre](http://www.dcc.ac.uk/resources/how-guides/license-research-data). How can you add a licence to your data?

**Activity 2:**

If you are developing software, read the blogpost on [“The Whys and Hows of Licensing Scientific Code”](https://www.astrobetter.com/blog/2014/03/10/the-whys-and-hows-of-licensing-scientific-code/).

**Activity 3:**

Journals are increasingly encouraging authors to archive the data behind their publications but the uptake amongst authors is slow. Licences are therefore something you may not realise you’ll need to think about. Take a look at some examples to see how others are doing it:



*   License file associated with the code at [https://github.com/omsharansalafia/radiogw17](https://github.com/omsharansalafia/radiogw17) 
*   Data and analysis script in Zenodo with licence indicated in the Zenodo metadata: [https://doi.org/10.5281/zenodo.1320054](https://doi.org/10.5281/zenodo.1320054) 
*   Open Source Initiative range of possible licences for software: [https://opensource.org/licenses](https://opensource.org/licenses)

**Activity 4:**

Bearing your own software and data in mind, which licence might you choose: [https://choosealicense.com](https://choosealicense.com) (mainly software) or [https://creativecommons.org/choose/](https://creativecommons.org/choose/) (data)?


## Thing 9: Data and software citation

_Relates to [R1.2: (Meta)data are associated with detailed provenance](https://www.go-fair.org/fair-principles/r1-2-metadata-associated-detailed-provenance/)_

A number of authors have found a citation advantage related to sharing astrophysical data. See [Sharing data increases citations](https://www.liberquarterly.eu/articles/10.18352/lq.10149/) and [Linking to Data: Effect on Citation Rates in Astronomy](http://adsabs.harvard.edu/abs/2012ASPC..461..763H). This is also the case outside of astronomy, for instance, see [Data reuse and the open data citation advantage](https://peerj.com/articles/175/). While data citation and linking has been more prevalent, a recent project called [Asclepias](https://asclepias.github.io/) aims to improve software citation across astronomy. The [Astrophysics Source Code Library](http://ascl.net/) is a good place to start to register your source code and to preserve and publish the code (via a DOI) using [GitHub to Zenodo](https://genr.eu/wp/cite/). See also the Top 10 FAIR Data & Software Things for [Research Software](https://librarycarpentry.org/Top-10-FAIR/2018/12/01/research-software/) and [Matthew Kenworthy's guide](https://github.com/mkenworthy/astrosoftware_howto) on how to submit your astronomy software and data reduction scripts for a more comprehensive look. 

The major journals in astronomy include information on data & software citation, for example, see [AAS Journal Reference Instructions](https://journals.aas.org/references/) and the [AAS Policy Statement on Software](https://journals.aas.org/policy-statement-on-software/). For citing and linking to data and software post publication, the NASA ADS has a section on  

[Data and Curation Frequently Asked Questions](http://adsabs.github.io/help/data_faq/) where abstract submissions or corrections can be made. 

One step in the process of linking papers to data and software is leveraging the “[Related Identifiers](https://authorcarpentry.github.io/dois-citation-data/01-register-doi.html)” feature when depositing data and software. The [Zenodo Sandbox](https://sandbox.zenodo.org/) is a helpful space to test this feature without depositing data or software permanently. 

Additionally, your institution might have a policy and instructions for citing data and software similar to the [Data Access Policy for ESO Data held in the ESO Science Archive Facility](https://archive.eso.org/cms/eso-data-access-policy.html). For example, this policy allows ESO to curate and add links post publication via the NASA ADS and their [Telescope Bibliography](http://telbib.eso.org/) repository.

**Activity 1:**

Examine how publications and data are linked in the ADS. For instance, find the link to telescope archives (XMM, HEASARC, CHANDRA) and the SIMBAD database for the paper [Advan et al., 2019](https://ui.adsabs.harvard.edu/abs/2019ApJ...875...68A/abstract).

**Activity 2:**

Learn how you can deposit, cite, and link your own data and/or software by exploring the [Zenodo Sandbox](https://sandbox.zenodo.org/).


## Thing 10: Data management plans

_This Thing is not related to a specific principle, but is the first step in the process to make data FAIR._

The purpose of a data management plan (DMP) is to document the management of data during a research project, from the time of data collection to their entry into permanent archives. The goal of a DMP is to consider the different aspects of data management including metadata generation, data preservation, and analysis so that the data are well managed from the start. Some of the main components for a DMP include:



*   The types of data
*   The standards to be used for data and metadata format and content
*   Policies for access and sharing
*   Policies and provisions for re-use
*   Plans for archiving data

Many of the main funding agencies require DMPs as part of the application process and/or provide guidance. For instance, see [Directorate of Mathematical and Physical Sciences Division of Astronomical Sciences (AST) Advice to PIs on Data Management Plans](https://www.nsf.gov/bfa/dias/policy/dmpdocs/ast.pdf).

There are tools available to assist researchers with developing DMPs such as the [DMPTool](https://dmptool.org/) and [DMPonline](https://dmponline.dcc.ac.uk/). Using tools like these are a good first step towards making your DMP more FAIR, but there is ongoing work to improve DMPs so that they are machine actionable. For instance, see [Ten principles for machine-actionable data management plans](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1006750) and [Ten Simple Rules for Creating a Good Data Management Plan](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4619636/).

**Activity 1:**

Review the [Data Management and Access Plan](https://www.rc.ufl.edu/wp-content/uploads/2012/08/NSF-DMP-UF-Astronomy.pdf) from the University of Florida Research Computing and determine if there are steps you can take to make this DMP more FAIR (based on the Ten Principles/Simple Rules).

**Activity 2:**

Using a tool such as the [DMPTool](https://dmptool.org/) or [DMPonline](https://dmponline.dcc.ac.uk/), try to identify the steps that would benefit from having the process documented in a FAIR way.
