---
title: "Biomedical Data Producers, Stewards, and Funders"
---

## Sprinters:

This document was created by [Lisa Federer](https://github.com/informationista), National Library of Medicine; Allissa Dillman, National Center for Biotechnology Information; Kenneth Wilkins, National Institute of Diabetes and Digestive and Kidney Diseases; Ishwar Chandramouliswaran, National Institute of Allergy and Infectious Diseases; Vivek Navale, NIH Center for Information Technology; Susan Wright, National Institute on Drug Abuse; and [Douglas Joubert](https://github.com/doujouDC), National Institutes of Health Library.

## Audience:

- Biomedical researchers
- Data [stewards](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6018669/)
- Funding organizations

# Things

## Thing 1: Metadata creation and curation

## Beginner Activity

1. Learn about the various types of metadata. DataOne defines metadata as "documentation about the data that describes the content, quality, condition, and other characteristics of a dataset. More importantly, metadata allows data to be discovered, accessed, and reused" [DataONE Education Module](https://www.dataone.org/education-modules).

1.
  - --Descriptive
  - --Technical
  - --Administrative
  - --Provenance
2. Work through the DataOne Metadata Educational Module: Lesson 7 - [Metadata](https://www.dataone.org/education-modules).
3. Explore the use of controlled vocabularies and Common Data Elements (CDE). A CDE is a &quot;data element that is [common to multiple data sets across different studies](https://www.nlm.nih.gov/cde/glossary.html#cdedefinition).&quot;. The NIH [Common Data Element (CDE) Resource Porta](https://www.nlm.nih.gov/cde/)l has identified CDEs for use in particular types of research or research domains after a formal evaluation and selection process.
  - --Take the NIH CDE [interactive tour](https://cde.nlm.nih.gov/home?tour=yes)to learn how to use the site.
  - --[Browse](https://cde.nlm.nih.gov/cde/search) the CDEs to explore how these might be used in your discipline.

## Intermediate Activity

1. Think about ways to standardized minimal/core metadata used across disciplines (or at least ability to [crosswalk](https://www.ands.org.au/online-services/rif-cs-schema/crosswalks-transform-your-metadata) between standards).
2. Automated metadata creation can &quot;[help improve efficiency in time and resource management within preservation systems, and alleviate the problems associated to the &quot;metadata bottleneck](http://www.dcc.ac.uk/resources/curation-reference-manual/completed-chapters/automated-metadata-extraction)&quot;.
  1. Review the  Digital Curation Centre (&quot;DCC&quot;)  [Automated Metadata Generation](http://www.dcc.ac.uk/resources/curation-reference-manual/completed-chapters/automated-metadata-extraction)primer page.
  2. Download the [DCC Digital Curation Reference Manual](http://www.dcc.ac.uk/webfm_send/1513), and think about ways you might be able to automate metadata creation at your organization.
  3. Watch the [ALCTS Session 1: Automating Descriptive Metadata Creation: Tools and Workflows](http://www.ala.org/alcts/events/ac/2016/vc-sess1) webinar which examine workflows for automating the creation of descriptive metadata.

## Thing 2: Use of standard data models

1. Explore the [OMOP Common Data Mode](https://www.ohdsi.org/data-standardization/the-common-data-model/)l (CDM), which allows for the systematic analysis of disparate observational databases to determine why you might want to use the OMOP CDM.
2. Review one of the [OMOP Community Meeting presentations](https://www.ohdsi.org/resources/presentations/community-meeting-presentations/) and think about how this might align to the work of your organization.
3. Familiarize yourself with one of the Observational Health Data Sciences and Informatics [GitHub repositories](https://github.com/OHDSI).

## Thing 3: Exploring unique, persistent identifiers

## Beginner Activity

[Globally unique and persistent identifiers](https://www.go-fair.org/fair-principles/f1-meta-data-assigned-globally-unique-persistent-identifiers/) remove ambiguity in the meaning of your published data by assigning a unique identifier to every element of metadata and every concept/measurement in your dataset (GOFAIR)

1. Explore the GO FAIR F1 [webpage](https://www.go-fair.org/fair-principles/f1-meta-data-assigned-globally-unique-persistent-identifiers/) to see examples of globally unique and persistent identifiers.
2. Learn how a Digital Object Identifier (DOI) can be used to create a unique reference to your data. Watch a [video](http://www.doi.org/driven_by_DOI.html) that explain what DOIs are and how they work, and how they benefit managers of digital content.
3. Read the [Digital Preservation Handbook](https://www.dpconline.org/handbook/technical-solutions-and-tools/persistent-identifiers) to learn about all of the elements that comprise a persistent identifier.

## Intermediate Activity

[ORCID](https://orcid.org/) allows you to create persistent digital identifiers for authors.

1. [Create](https://orcid.org/register) an ORCID ID.
2. Link your ORCID with [CrossRef](https://orcid.org/members/001G000001C8dNEIAZ-crossref) and [DataCite](https://orcid.org/members/001G000001G9QIUIA3-datacite).
3. Then, go through steps included in the [Getting Started with ORCID Integration](https://members.orcid.org/api/getting-started) guide.
  1. Test the [ORCID Application Programming Interface (API)](https://orcid.org/content/register-client-application-sandbox).
4. As a best practice, use ORCIDs from the start of data creation. For example, you can attach data creator name/ORCID to dataset as a metadata field. Include ORCIDs with datasets in repositories (e.g. in [Sequence Read Archive (SRA)](https://www.ncbi.nlm.nih.gov/sra), include the ORCID for the data creator).  This allows for the tracking of your research and enables citation of your data.

## Thing 4: Versioning and data &quot;retirement&quot;

## Beginning Activity

A [source-code repository](https://en.wikipedia.org/wiki/Comparison_of_source-code-hosting_facilities) is a file archive and web hosting facility where a large amount of source code, for software, web pages, and other resources, is kept, either publicly or privately (Wikipedia, not sure how to cite). Advantages of versioning include:

1. Persistence of identifiers pointing to different/earlier versions
2. Maintaining previous versions of code, software, and data.
3. Sharing various levels of processed data (primary, secondary, or raw/clean/processed, etc.).
4. De-accessioning of data that has reached the end of its life cycle

## Intermediate Activity

1. GitHub is one of the [most popular](https://en.wikipedia.org/wiki/List_of_most_popular_websites) options for code hosting. Explore alternative [ptions](https://opensource.com/article/18/8/github-alternatives) for code hosting.
2. Work through the [Library Carpentry Introduction to GitHub](https://librarycarpentry.org/lc-git/) module.

## Thing 5: Linking research objects

## Beginning Activity

1. Read the following article on managing [digital research objects](https://datascience.codata.org/articles/10.5334/dsj-2018-016/).
2. Read the [linking data](https://www.crossref.org/community/linking-data/) CrossRef page.

## Intermediate Activity

1. Using a code repository ([Github](https://github.com/) repo or [Zenodo](https://zenodo.org/)), try to find data that goes with a published paper. Then answer some of the following questions:
  1. Where is the data or code stored (for example, [Github](https://github.com/) repo or [Zenodo](https://zenodo.org/))?
  2. Who created the objects (ORCID)?
  3. Was there proper documentation for commercial software?

## Thing 6: Human and machine readability

1. Read about the [FAIR principle](https://www.force11.org/fairprinciples) for making your code both human and machine readable, and the [FAIR Guiding Principles](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4792175/) article.
2. Read the following report [Jointly designing a data FAIRPORT](https://www.lorentzcenter.nl/lc/web/2014/602/info.php3?wsid=602) from the Lorentz Center.
3. Having code that is both human and machine readable supports
  1. API access
  2. Allows for automatic integration of multiple datasets
  3. Use of standard formats widely accepted in the discipline

## Thing 7: Maintain/preserve entire research environment (e.g. software)

1. Familiarize yourself with best practices for scientific computing. Read [Good Enough Practices in Scientific Computing](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005510), and [Top 10 Metrics for Life Science Software Good Practices](https://f1000research.com/articles/5-2000/v1) to familiarize yourself with the topics of containers, software preservation, and software emulation.
2. Read more about the [Long-term preservation of biomedical research data](https://f1000research.com/articles/7-1353/v1).

## Thing 8: Indexing repositories to enable findability

1. [org](https://www.re3data.org/about) is a global registry of research data repositories that covers research data repositories from different academic disciplines. Register your dataset with re3data.org
2. [org](https://schema.org/) is a collaborative, community activity with a mission to create, maintain, and promote schemas for structured data.
  1. Read their [Getting Started Guide](https://schema.org/docs/gs.html) to get indexed with Google.
3. Link your ORCID account to [org](https://fairsharing.org/), verify your email address, and create a public profile.
  1. Familiarize yourself with their Standards, Databases, Policies, and Collections.

## Thing 9: Broad consent

Informed consent for human subjects should be broad enough to make reuse possible. See [Broad Consent for Research with Biological Samples: Workshop Conclusions](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4791589/). Also see, [Recommendations for Broad Consent Guidance](https://www.hhs.gov/ohrp/sachrp-committee/recommendations/attachment-c-august-2-2017/index.html) from the Office for Human Research Protections.

## Thing 10: Application of metrics to evaluate the FAIRness of (data) repositories

## Beginning Activity

1. Explore the work of the [FAIR Metrics Group](http://fairmetrics.org/). Explore their proposed [FAIR Metrics](https://github.com/FAIRMetrics/Metrics).
2. Read the following paper: [Evaluating FAIR-Compliance Through an Objective, Automated, Community-Governed Framework](https://www.biorxiv.org/content/biorxiv/early/2018/09/16/418376.full.pdf).
3. Explore a [design framework for exemplar metrics for FAIRness](https://www.nature.com/articles/sdata2018118)

## Intermediate Activity

1. Explore the Make Data Count Project, where you can learn about  [COUNTER Code of Practice](https://www.projectcounter.org/code-of-practice-sections/general-information/) as well as the [Code of Practice for Research Data Usage Metrics](https://peerj.com/preprints/26505/)
2. Learn how [Zenodo](http://blog.zenodo.org/2018/07/18/2018-07-18-usage-statistics/) and [DataONE](https://www.dataone.org/news/new-usage-metrics) have responded to the Make Data Count recommendations.

