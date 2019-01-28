---
title: "Oceanography"
---

# Top 10 FAIR data things for Oceanography

##### UC San Diego Sprinters: Reid Otsuji, Stephanie Labou, Ryan Johnson, Guilherme Castelao, Bia Villas Boas

##### Version 1.0 (December, 2019)

## Table of contents

### Findable

[Thing 1: Data repositories](#thing-1-data-repositories)  
[Thing 2: Metadata](#thing-2-metadata)  
[Thing 3: Permanent Identifiers](#thing-3-permanent-identifiers)  
[Thing 4: Citations](#thing-4-citations)  

### Accessible

[Thing 5: Data formats](#thing-5-data-formats)  
[Thing 6: Data Organization and Management](#thing-6-data-organization-and-management)  
[Thing 7: Re-usable data](#thing-7-re-usable-data)  

### Interoperability

[Thing 3: Permanent Identifiers](#thing-3-permanent-identifiers)  
[Thing 6: Data Organization and Management](#thing-6-data-organization-and-management)  
[Thing 2: Metadata](#thing-2-metadata)  
[Thing 10: APIs and Apps](#thing-10-apis-and-apps)

### Reusable

[Thing 8: Tools of the trade](#thing-8-tools-of-the-trade)  
[Thing 9: Reproducibility](#thing-9-reproducibility)  
[Thing 10: APIs and Apps](#thing-10-apis-and-apps)

---

### Brief Description

Oceanographic data encompasses a wide variety of data formats, file sizes, and states of data completeness. Data of interest may be available from public repositories, collected on an individual basis, or some combination of these, and each type has its own set of challenges. This “10 things” guide introduces 10 topics relevant to making oceanographic data FAIR: findable, accessible, interoperable, and reusable.

### Audience

* Library staff and programers who provide research support
* Oceanographers
* Oceanography data stewards
* Researchers, scholars and students in Oceanography

### Lesson Goals

The goal of this lesson is to introduce oceanographers to FAIR data practices in their research workflow through 10 guided activities.

---

## Thing 1: Data repositories

There are numerous data repositories for finding oceanographic data. Many of these are from official “data centers” and generally have well-organized and well-documented datasets available for free and public use.

* [NSF / Earth Cube](http://www.nsf.gov/geo/earthcube/)  
* [CLIVAR - CCHDO](http://cchdo.ucsd.edu/)  
* [CLIVAR - Hawaii ADCP](http://ilikai.soest.hawaii.edu/sadcp/clivar.html)  
* [CLIVAR - JODC ADCP Data](http://www.jodc.go.jp/goin/adcp.html)  
* [NOAA - NODC](http://www.nodc.noaa.gov/)  
* [NOAA - NCDC](http://www.ncdc.noaa.gov/oa/ncdc.html)  
* [NOAA - NGDC](http://www.ngdc.noaa.gov/)  
* [NSIDC](http://nsidc.org/)  
* [CDIAC](http://cdiac.ornl.gov/)  
* [BCODMO](http://bcodmo.org/)  
* [GEOTRACES](http://www.geotraces.org/)  
* [R2R](http://www.rvdata.us/)  
* [SAMOS](http://samos.coaps.fsu.edu/html/)  
* [ARGO Data](http://www.argo.ucsd.edu/Argo_data_and.html)  
* [NASA - PO.DAAC](https://podaac.jpl.nasa.gov/)  
* [World Ocean Database (WOD)](https://www.nodc.noaa.gov/OC5/WOD/pr_wod.html)  
* [Spray Underwater Glider](https://spraydata.ucsd.edu/)  

At some point, you may want or need to deposit your own data into a data repository, so that others may find and build upon your work. Many funding agencies now require data collected or created with the grant funds to be shared with the broader community. For instance, the National Science Foundation (NSF) Division of Ocean Sciences (OCE) [mandates sharing of data](https://www.nsf.gov/pubs/2017/nsf17037/nsf17037.jsp) as well as metadata files and any derived data products. Finding the “right” repository for your data can be overwhelming, but there are resources available to help pick the best location for your data. For instance, OCE has a list of [approved](https://www.nsf.gov/geo/oce/oce-data-sample-repository-list.jsp) repositories in which to submit final data products.

### Activity 1

* Go to [re3data.org](https://www.re3data.org/) and search for a data repository related to your research subject area. How many results did you get? Which of these repositories looks most relevant to your research area? Is it easy to find a dataset in those repositories that covered the California coast (or any other region of your choice) during the last year?

### Activity 2

* What is the next journal you would like to publish in? (Alternatively: what is a top journal in your field?) Can you find the data submission requirements for this journal?

---

## Thing 2: Metadata

High quality metadata (information about the data, such as creator, keywords, units, flags, etc.) significantly improves data discovery. While metadata is most often for the data itself, metadata can also include information about machines/instruments used, such as make, model, and manufacturer, as well as process metadata, which would include details about any cleaning/analysis steps and scripts used to create data products.

Using controlled vocabularies in metadata allows for serendipitous discovery in user searches. Additionally, using a metadata schema to mark up a dataset can make your data findable to the world.

### Activity 1

* Using [schema.org](https://schema.org/) markup, look at the metadata elements pertaining to  scholarly articles: https://schema.org/ScholarlyArticle. Imagine you have an article you have hosted on your personal website, and you would like to add markup so that it could be more readily indexed by [Google Dataset Search](https://toolbox.google.com/datasetsearch). What metadata elements would be most important to include? (This resource will help you: [https://developers.google.com/search/docs/data-types/dataset](https://developers.google.com/search/docs/data-types/dataset))

### Activity 2

* OpenRefine example for making data FAIR.

Read this walkthrough of how to “FAIRify” a dataset using the data cleaning tool OpenRefine: [https://docs.google.com/document/d/1hQ0KBnMpQq93-HQnVa1AR5v4esk6BRlG6NvnnzJuAPQ/edit#heading=h.v3puannmxh4u](https://docs.google.com/document/d/1hQ0KBnMpQq93-HQnVa1AR5v4esk6BRlG6NvnnzJuAPQ/edit#heading=h.v3puannmxh4u)

### Discussion

* If you had _thousands_ of keywords in a dataset you wanted to associate with a controlled vocabulary relevant to your field, what would be your approach? What tools do you think would best automate this task?

---

## Thing 3: Permanent identifiers

Permanent identifiers (PIDs) are a necessary step for keeping track of data. Web links can break, or “rot”, and tracking down data based on a general description can be extremely challenging. A permanent identifier like a [digital object identifier (DOI)](https://www.doi.org/) is a unique ID assigned to a dataset to ensure that properly managed data does not get lost or misidentified. Additionally, a DOI makes it easier to cite and track the impact of datasets, much like cited journal articles.

Identifiers exist for researchers as well: [OCRID](https://orcid.org/) is essentially a DOI for an individual researcher. This ensures that if you have a common name, change your name, change your affiliation, or otherwise change your author information, you still get credit for your own and maintain a full, identifiable list of your scientific contributions.

### Activity 1

Go to re3data.org and search for a data repository related to your research subject area. From the repository you choose, pick a dataset. Does it have a DOI? What is? Who is the creator of that dataset? What is the ORCID of the author?

### Activity 2

You’ve been given this DOI: **10.6075/J03N21KQ**

* What would you do to find the dataset this DOI references?
* Using the above approach you just identified, what is associated with this DOI? Who was the creator of this dataset? When was that published? Who funded that research?

### Activity 3

* Go to the [ORCID website](https://orcid.org/) and create an ORCID if you do not have one already. Can you identify the creator associated with the DOI on the activity 1?

### Discussion

* What would be a positive benefit for having a personal persistent ID such as ORCID?  Are there any drawbacks or concerns?

---

## Thing 4: Citations

Citing data properly is equally as important as citing journal articles and other papers. In general, a data citation should include: author/creator, date of publication, title of dataset, publisher/organization (for instance, NOAA), and unique identifier (preferably DOI).

### Activity 1

* Read through this [overview](https://www.dataone.org/citing-dataone) of citing data from DataONE. This has information application to any data citations, as well as guidelines specific to DataONE.
* Think of the last dataset you worked with. Is it something you collected, or was it from a public repository? How would you cite this data?
* Websites/data repositories will often provide the text of preferred citation, but you may have to search for it. How would you cite the [World Ocean Database](https://www.nodc.noaa.gov/OC5/WOD/pr_wod.html)? How would you cite data from the Multibeam Bathymetry Database?

### Discussion

Long-term data stewardship is an important factor for keeping data open and accessible for the long term.

* After completing the last activity, discuss how Open is data in the discipline? Are there long-term considerations and protocols for the data that is produced?

#### Tip: Resources that can help make your data more open and accessible or to protect your data

* [Open Science Framework](https://osf.io)  
* [Figshare](https://figshare.com/)
* [Oceanographic data centers](#thing-1-data-repositories)

---

## Thing 5: Data Formats

Oceanographic data can include everything from maps and images to high dimensional numeric data. Some data are saved as common, near-universal formats (such as csv files), while others require specialized knowledge and software to open properly (e.g., netCDF).  Explore the Intrinsic characteristics of the dataset that  influence the choice of the format, such as a time series versus a regular 3-D grid of temperature varying on time;  robust ways to connect the data with metadata; size factors, binary versus ASCII file; and think about why a format to store/archive data is not necessarily the best way to distribute data.

#### Discussion 1

* what are the most common data formats used in your field? What level of technical/domain knowledge is required to open, edit, and interactive with these data types?  

#### Discussion 2

* What are the advantages and disadvantages of storing in plain ASCII, like a CSV file versus a binary, like netCDF? Does the characteristics of the data influence that decision, i.e. the prefered format for a time series would be different than a numerical model output, or a gene sequence?

---

## Thing 6: Data organization and management

Good data organization is the foundation of your research project.  Data often has a longer lifespan than the project it is originally associated with and may be reused for follow-up projects or by other researchers. Data is critical to solving research questions, but lots of data are lost or poorly managed.  Poor data organization can directly impact the project or future reuse.  

### Activity 1

#### Considerations for basic data organization and management

### Group Discussion 1

* Is your data file structure something that a new lab member could easily learn, or are datasets organized in a more haphazard fashion?
* Do you have any documentation associated describing how to navigate your data structures?

### Group Discussion 2

* Talk about where/how you are currently storing data you are working with. Would another lab member be able to access all your data if needed?

### Activity 2

#### Identifying vulnerabilities

* **Scenario 1:** Your entire office/lab building burns down overnight. No one is harmed, because no on was there, but all electronics in the building perish beyond hope of repair. The next morning, can you access any of your data?
* **Scenario 2:** The cloud server you use (everything from Google Drive to GitHub) crashes. Can you still access your most up to date data?

### Discussion

* From either of the two scenarios, can your data survive a disaster? What some of the things that you think you are doing incorrectly to prevent data loss?

### Discussion

* Think about a time when you had or potentially had a data disaster - how could the disaster have been avoided? What, if anything, have you changed about your data storage and workflow as a result?

### The Data Management Plan (DMP)

Some research institutions and research funders now require a Data Management Plan (DMP) for new research projects. Let's talk about the importance of a DMP and what should a DMP cover.  Think about it you would you be able to create create a DMP?

### What is a DMP?
A Data Management Plan (DMP) documents how data will be managed, stored and shared during and after a research project. Some research funders are now requesting that researchers submit a DMP as part of their project proposal.

### Activity 1

* Start by watching [The DMPTool: A Brief Overview 90 second video](https://youtu.be/xT1by-p5jUw) to see what the DMPTool can do for researhers and data managers.
* Next, review this short [introduction to Data Management Plans](https://www.ands.org.au/working-with-data/data-management/data-management-plans).
* Now browse through some public DMPs from the [DMPTool](https://dmptool.org/public_plans), choose one or two of the DMPs related to oceanography and read them to see the type of information they capture.

### Activity 2

There are many Data Management Plan (DMP) templates in the DMPTool.

* Choose one DMP funder template you would potentially use for a grant proposal in the DMPTool. Spend 5-10 minutes starting to complete the template, based on a research project you have been involved with in the past.

### Discussion

* You will have noticed that DMPs can be very short, or extremely long and complex. What do you think are the two or three pieces of information essential to include in every DMP and why?
* After completing the second activity, what are strengths and weaknesses of your chosen template?

---

## Thing 7: Re-usable data

There are two aspects to reusability: reusable data, and reusable derived data/process products.

### Reusable data
Reusable data is the result of successful implementation of the other “things” discussed so far. Reusable data (1) has a license which specifies reuse scenarios, (2) is in a domain-suitable format and an “open” format when possible, and (3) is associated with extensive metadata consistent with community and domain standards.

### Process/derived data products
What is often overlooked in terms of reusability are the products created to automate research steps. Whether it’s using the command line, Python, R, or some other programming platform, automation scripts in and of themselves are a useful output that can be reused. For example, data cleaning scripts can be reapplied to datasets that are continually updated, rather than starting from scratch each time. Modeling scripts can be re-used and adapted as parameters are updated. Additionally, these research automation products make any data-related decision you made explicit: if future data users have questions about exclusions, aggregations, or derivations, the methodology used is transparent in these products.

### Discussion 1

* How many people have made public or shared part of their research automaton pipeline? If you haven’t shared this, what prevented you from sharing?

### Discussion 2

* Are there instances where your own research would have been improved if you had access to other people’s process products?

---

## Thing 8: Tools of the trade

When working with your data, there are a selection of proprietary and open source tools available to conduct your research analysis.  

### Why open source tools?
Open source tools are software tools developed, in which the source code is openly available and published for use and/or modification by any one free of charge. There are many advantages to using open source tools:

* Low software costs
* Low hardware costs
* Wide community development support
* Interoperable with other open source software
* No vendor control
* Open source licensing

**Caution: be selective with the tools you use**  
There are additional benefits you may hear about using open sources tools which are:

* Higher quality software
* Greater security
* Frequent updates

Keep in mind, in an ideal world these three ideas are what we all wish for, however not every open source tool satisfies these benefits.  When selecting an open source tool, choose a package with a large community of users and developers that proves to have long-term support.

### Things to consider when using open source tools

#### Benefits

* Open source tools often have active development community.  Quality for end users is usually higher because the community are users of the software being developed.  In turn, open source costs for development are cheaper.  
* With a larger community of development, security problems and vulnerabilities are discovered and fixed quickly. Another major advantage of open source is the possibility to verify exactly which procedures are being applied, avoiding the use of "black-boxes" and allowing for a thorough inspection of the methods.

#### Issues

* Open sources tools are only as good as the community that supports it. Unlike commercial software there is no official technical support.  Additionally, not all open source licenses are permissive.
* Training time can be significant.

If Open source tools are not an option and commerical sfotware is necessary for your project, there are benefits and issues to consider when using proprietary or commercial software tools.

#### Benefits

* This type of software often comes with official technical support such as a customer service phone number or email.

#### Issues

* Proprietary or commercial tools are often quite expensive at the individual level.
* Universities may have campus-wide licenses, but if you move institutions, you may find yourself without the software you had been using.

### Discussion

* Think about the tools you use for conducting data clean up, analysis, and for creating visualizations and reports for publications.  What were the deciding factors for selecting the applications you used or are using for your project?

---

## Thing 9: Reproducibility

### Can you or others reproduce your work?
Reproducibility increases impacts credibility and reuse.

Read through the following best practices to make your work reproducible.

### Best practices
Making your project reproducible from the start of the project is ideal.  

* Documenting each step of your research - from collecting or accessing data, to data wrangling and cleaning, to analysis - is the equivalent of creating a roadmap that other researchers can follow. Being explicit about your decisions to exclude certain values or adjust certain model parameters, and including your rationale for each step, help eliminate the guesswork in trying to reproduce your results.
* Consider open source tools. This allows anyone to reproduce research more easily, and helps with identifying who has the right license for the software used.

This is useful not only for anyone else who wants to test your analysis - often the primary beneficiary is you!

Research often takes months, if not years, to complete a certain project, so by starting with reproducibility in mind from the beginning, you can often save yourself time and energy later on.

### Discussion

Think about a project you have completed or are currently working on.  

* What are some of the best practices you have adopted to make your research reproducible for others?
* Was there any pain points that you encounter or are dealing with now?
* Is there something you can do about it now?
* What are the most relevant "things" previously mentioned in this document that you could use to make your research more reproducible?

---

## Thing 10: APIs and Apps

APIs (Application Programming Interfaces) allow programmatic access to many databases and tools. They can directly access or query existing data, without the need to download entire datasets, which can be very large.

Certain software platforms, such as R and Python, often have packages available to facilitate access to large, frequently used database APIs. For instance, the [R package “rnoaa”](https://ropensci.org/tutorials/rnoaa_tutorial/) can access and import various NOAA data sources directly from the R console. You can think of it as using an API from the comfort of a tool you’re already familiar with. This not only saves time and computer memory, but also ensures that as databases are updated, so are your results: re-running your code automatically pulls in new data (unless you have specified a more restricted date range).

### Activity

On the ERDDAP server for [Spray Underwater Glider data](https://spraydata.ucsd.edu/erddap/tabledap/binnedCUGN90.html), select temperature data for the line 90 ([https://spraydata.ucsd.edu/erddap/tabledap/binnedCUGN90.html](https://spraydata.ucsd.edu/erddap/tabledap/binnedCUGN90.html)).

* Restrict it to measurements at 25 m or shallower.
* Choose the format of your preference, and instead of submit the request, generate an URL.
* Copy and paste the generated URL in your browser.

### Discussion

* Think about the last online data source you accessed. Is there an API for this data source? Is there a way to access this data from within your preferred analysis software?

---

## References

1. [ANDS 23 (Research Data) Things]( https://www.ands.org.au/working-with-data/skills/23-research-data-things/all23)  
2. [Top 10 FAIR Data Things lessons](http://librarycarpentry.org/Top-10-FAIR/)
