---
title: "Nanotechnology"
---

## Description: 
This brief guide is based on FAIR principles (findability, accessibility, interopera_bility, reusability) and describes data management in the field of nanotechnology. It consists of ten steps/chapters with information on data discovery and publication, practices and resources as well as activity ideas. 

## Audience: 
It is addressed to nanotechnology students, researchers, librarians and research support staff. 

## Sprinters:
- Elli Papadopoulou (Athena Research Center / OpenAIRE)  
[https://orcid.org/0000-0002-0893-8509](https://orcid.org/0000-0002-0893-8509)
- Emma Lazzeri (National Research Council of Italy / OpenAIRE)  
[https://orcid.org/0000-0003-0506-046X](https://orcid.org/0000-0003-0506-046X)
- Iryna Kuchma (EIFL / OpenAIRE)  
[https://orcid.org/0000-0002-2064-3439](https://orcid.org/0000-0002-2064-3439)
- Dr Leonidas Mouchliadis (FORTH-IESL, Laser and Applications Division)  
[https://orcid.org/0000-0001-7255-9397](https://orcid.org/0000-0001-7255-9397)
- Katerina Lenaki (Greek Ministry of Education, open science enthusiast)  
[https://orcid.org/0000-0001-7984-8888](https://orcid.org/0000-0001-7984-8888)
- Spyros Zoupanos (EPFL)  
[https://orcid.org/0000-0002-9262-7884](https://orcid.org/0000-0002-9262-7884)
- Danail Hristozov (Greendecision / GRACIOUS)  
[https://orcid.org/0000-0002-2386-7366](https://orcid.org/0000-0002-2386-7366)

## Contributors:
- Stella Stoycheva (Yordas Group / GRACIOUS)  
[https://orcid.org/0000-0001-8025-565X](https://orcid.org/0000-0001-8025-565X)
- Eleen Leenarts (DANS / OpenAIRE)  
[https://orcid.org/0000-0002-5589-756X](https://orcid.org/0000-0002-5589-756X)

## Acknowledgments: 
OpenAIRE Research Data Management Task Force

# Things

## Thing 1 - Nanotechnology: overview and current trends
Nanotechnology is part of the broader scientific discipline of material science and, particularly, it is the area of research in science, engineering and technology which deals with the manipulation and manufacturing of nano-dimensional materials at a scale of 10<sup>-9</sup>m.  Nanotechnology applies in diverse disciplines, such as but not limited to physics, chemistry, engineering, energy, medicine, space, agriculture, information, communication etc. 

“Some areas are more mature than others. For example, the entire semiconductor industry is now based on nanotechnology. Transistors with critical dimensions of 30nm are being built today and put together into circuits composed of over one billion devices, on one single chip, roughly the size of a thumbnail. In medicine, nanotechnology has led to the development of drug delivery vehicles and diagnostic devices for the detection and treatment of cancer. It is used in tissue engineering to repair damaged tissue and organs. There are advanced uses of nanotechnology in areas of storage, conversion, and renewal of energy – from LEDs to fuel cells to solar cells. Most high-tech information and communication devices use nanoscale production processes. Nanotechnology is also found in everyday consumer goods, such as stain-resistant fibers for clothes, tennis balls, running shoes, cosmetics, and numerous other day-to-day products” (Source: [https://nanohub.org/about/nano](https://nanohub.org/about/nano))

Depending on how nanomaterials are manufactured, they bear different properties, however the main attribute of nanoscale materials, structures, devices and systems is electricity production and binary information production, storage and transmission. Nanotechnology materials can be used in mobile applications and the emerging flexible electronics, in detectors/sensors of security systems and for health monitoring, in everyday objects to make them resilient and durable (e.g. baseball bats, tennis rackets) etc. 

Current research trends include the exploration of two dimensional (2D) materials’ surface capabilities, like graphene for use in the areas of flexible electronics and valleytronics. 2D materials are atomically thins, exhibit remarkable surface properties and capabilities and their output vary when compiled by different angles.

In addition to the processes of materials manipulation and manufacturing, there is research around nanotechnology which concerns complementary aspects such as risk assessment and governance, physicochemical characterization, (eco)toxicity testing, exposure, life-cycle impact assessment and decision support for sustainability of nanotechnologies among others. In fact, the European project [GRACIOUS](https://www.h2020gracious.eu/) aims to provide the means to more efficiently assess risk and obtain safety information for the diverse in size, morphology and surface characteristics nanomaterials/nanoforms to ultimately develop a grouping framework.

**Activity 1 - Discussion**  
*   Which is the scientific field/ discipline of primary focus of your nanotechnology research endeavours? What is the application of the outputs of your nanotechnology research?
*   Are you manipulating or manufacturing nanoscale materials, structures, devices, systems or both? What are the nanomaterials’ properties that you most commonly come across?

## Thing 2 - Workflow and Methods
Nanotechnology research is based on hypotheses (theory) and experiments. Hypotheses explore ways of producing structures that are 2D and simulations confirm or deny these hypotheses[^1]. Theoretical and experimental researchers work together to produce new materials and their communication is bidirectional:

*   Experimentals might notice properties that are different from the expected outcome after running the simulation
*   Theoreticians can propose alternative ways of proceeding with the hypothesis.

There are different methods for the sample preparation and characterization. The former mainly focus on the thin-film deposition of single crystals and include, but are not limited to,  Molecular-Beam Epitaxy (MBE) and Chemical Vapor Deposition (CVD). The latter include a  variety of characterization methods such as Raman and TEM spectroscopy, atomic force microscopy (AFM) and nonlinear microscopy (second harmonic generation (SHG) and two-photon photoluminescence (2p-PL)).

In addition there are free access packages for the calculation of the electronic, optical, mechanical and thermal properties of 2D materials, based on first principle calculations. The most widely used packages are [Quantum espresso](https://www.quantum-espresso.org/), [VASP](https://www.vasp.at/), [Yambo](http://www.yambo-code.org/) and [Wien2K](http://susi.theochem.tuwien.ac.at/).[IATA](http://www.oecd.org/chemicalsafety/risk-assessment/iata-integrated-approaches-to-testing-and-assessment.htm) (Integrated Testing and Assessment Strategy) usually defines which methods and hypotheses could be used for the given purpose.

**Activity 1 - Discussion**  
Based on your field of application and your experience, what kind of workflows seem to work best? Why?

## Thing 3 - Data types, outputs and formats
As already addressed, nanotechnology is a multidisciplinary scientific field by nature. It can be applied to many disciplines and thus, the types of data produced by nanotechnology research can be from simulations to chemical data and more. Some data types are, but are not limited to, the following:

1. chemical data on intrinsic properties you measure the properties: aspect ratio, chemical composition, size, surface area, surface properties, coating
2. chemical data on extrinsic properties : particle interacting within the environment
3. crystallographic data about the real space positions of the atoms in 2D crystals such as graphene, transition metal dichalcogenides, hexagonal boron nitride and black phosphorous.
4. data related to stratified structures comprising the same (homostructures) or different (heterostructures) 2D materials[L1] , such as the number of layers and the relative orientation (twist angle, poire patterns)
5. output data of the density functional theory, e.g. band structure, direct and indirect band gaps,  excitonic resonances

Open and standardised file formats are essential for accessing data by providing freely available specification documents necessary to open and read their corpus. Most common file formats used in Nanotechnology are CIF[^2], UPF[^3].

**Activity 1 - Defining your data discussion**
*   Where does your data come from? What types of data do you produce or consume? Can you find it in the list above? What formats are your data in? How often do you get new data? How much data do you generate? 
*   Where would these data be useful?

**Activity 2 - Other uses for your data**
Would you data be of use in any other research?

## Thing 4 - Describing data: Metadata
Metadata is data about data and is an essential set of information describing scientific outputs, in the form of either physical or digital objects, in a machine-readable format. According to the expected use, metadata can be given different attributes. Most common type which enables discovery and identification are _descriptive metadata._ Descriptive metadata contain information about key aspects needed to search for and successfully find a given scientific output, e.g. by its title, author/creator, abstract, keywords. Moreover, metadata may be used for describing a service or a scientific instrument.

Depending on the area of focus, in nanotechnology there are few metadata standards, vocabularies and ontologies to facilitate standardised interpretation. 

*   [NeXus](http://www.nexusformat.org/)

“NeXus is an international standard for the storage and exchange of neutron, x-ray, and muon experiment data. The structure of NeXus files is extremely flexible, allowing the storage of both simple data sets, such as a single data array and its axes, and highly complex data and their associated metadata, such as measurements on a multi-component instrument or numerical simulations. NeXus is built on top of the container format HDF5, and adds domain-specific rules for organizing data within HDF5 files in addition to a dictionary of well-defined domain-specific field names.”[^4]

*   [ISA-TAB-Nano](https://wiki.nci.nih.gov/display/ICR/ISA-TAB-Nano) 

“ISA-TAB-Nano specifies the format for representing and sharing information about nanomaterials, small molecules and biological specimens along with their assay characterization data (including metadata, and summary data) using spreadsheet or TAB-delimited files.”[^5]

*   [NanoParticle Ontology](http://www.nano-ontology.org)

“NanoParticle Ontology “represents the basic knowledge of physical, chemical and functional characteristics of nanotechnology as used in cancer diagnosis and therapy.”[^6]

Apart from metadata records describing datasets, documentation is equally essential when writing code. As the minimum example, a README file helps ensure that your data can be correctly interpreted and reanalysed by others. A README plain text file should contain the following information:

For each filename, a short description of what data it includes, optionally describing the relationship to the tables, figures, or sections within the accompanying publication; for tabular data: definitions of column headings and row labels; data codes (including missing data); and measurement units; any data processing steps, especially if not described in the publication, or provenance file, that may affect interpretation of results; a description of what associated datasets are stored elsewhere, if applicable; whom to contact with questions, read more[ https://datadryad.org//pages/readme](https://datadryad.org/pages/readme).

**Activity 1**  
Go to the [Research Data Alliance Metadata Directory](https://rd-alliance.github.io/metadata-directory/) and search for a metadata standard relevant to the focus of your nanotechnology work. Is there any relevant to your focus? 

**Activity 2**  
Have a look at the metadata record for the [7T Magnetom instrument ](https://researchdata.ands.org.au/7t-magnetom/1305790)at Research Data Australia. It contains simple but important public metadata and a persistent identifier. How could this record be enhanced to assist you as a researcher?

**Activity 3**  
Go to [OpenAIRE ](https://www.openaire.eu/)and search with a keyword about your research interests. What are the nanotechnology projects you find? How many publications, data or software did you get? What are some of the projects associated with these outputs?

## Thing 5 - Identifiers 
Persistent and/or Permanent Identifiers (PIDs) uniquely identify objects, people, organisations and activities and can ensure that the scientific output is accessible even when the URL of the website has changed. PIDs can be assigned to research outputs including publications, data and software/code. PIDs can also be assigned to  researchers, samples, organisations and projects. A PID may be connected to a metadata record describing an item rather than the item itself.

The repository used for data or software deposit should make use of a PID service and assign PIDs to its outputs, also in compliance with the FAIR principles. PIDs can be resolved by the use of tools, such as the [DOI Resolver](https://dx.doi.org/).

PIDs used in research include:  

*   Digital Object Identifier ([DOI](http://www.doi.org/))
*   [Persistent Uniform Resource Locator ](http://www.purlz.org/)(PURL)
*   Uniform Resource Name (URN)
*   Archival Resource Key (ARK)
*   [Handle](http://handle.net/)
*   [Research Activity Identifier](https://www.raid.org.au/) (RAID).
*   [Open Research and Contributor Identifier](https://orcid.org) (ORCID)
*   [International Geo Sample Number](http://www.igsn.org/) (IGSN)

To learn more about persistent identifiers visit [Go-FAIR F1 Principle](https://www.go-fair.org/fair-principles/f1-meta-data-assigned-globally-unique-persistent-identifiers/).

**Activity 1**  
Search for papers and data in nanotechnology and observe the use of ORCIDs. Is it widely known in your community? Why do you think that is?

**Activity 2**  
(Read 5 min) OpenAIRE/FREYA/ORCID guide for researchers “[How can identifiers improve the dissemination of your research outputs?](https://www.openaire.eu/how-can-identifiers-improve-the-dissemination-of-your-research-outputs)” 

**Activity 3** 
(Watch 4 min) [Six Ways to Make Your ORCID iD Work for You](https://orcid.org/blog/2018/07/27/six-ways-make-your-orcid-id-work-you)! If you already have an ORCID, check this video [https://www.youtube.com/watch?v=h92bUZ5T_vA](https://www.youtube.com/watch?v=h92bUZ5T_vA) to link publications to your ORCID profile.

**Activity 4** 
(Discuss in pairs 5 min) [The Joint Declaration of Data Citation Principles](https://www.force11.org/datacitationprinciples) from FORCE11.

## Thing 6 - Interoperability

Interoperability enables data and metadata to flow between different systems with the use of standard vocabularies and references to other data and metadata. That is why standardised formats of protocols are important. In nanotechnology, you may find protocols for:

*   different surfaces to interoperate
*   the preparation of multilayered structures: The preparation of functional multilayered structures comprising different kind of 2D materials, entails complex procedures and fine treatment both mechanically and chemically. These recipes are encoded into protocols that are available to the entire community of sample manufacturers and allow the repetition and improvement of the sample preparation procedure and methodologies.

In materials science, as researchers create independent materials databases, much can be gained from retrieving data from multiple databases. However, the retrieval process is difficult if each database has a different API which is a common  case. To address this challenge, there are initiatives such as the [Open Databases Integration for Materials Design (OPTiMaDe)](http://www.optimade.org/) consortium which aim to make materials databases interoperational by developing a common REST API.

**Activity 1**  
[Protocol Exchange ](https://protocolexchange.researchsquare.com)from Nature Protocols is an open repository of community-contributed protocols. Search for nanotechnology protocols publicly shared.

## Thing 7 - Licenses and provenance of data for reusability
Licenses grant specific permissions for researchers other than the owner to use scientific output, such as publication, data or software following following each time the specified set of exploitation requirements/recommendations tied with the license.

OpenAIRE Guide for Researchers “[How do I license my research data?](https://www.openaire.eu/how-do-i-license-my-research-data)” provides information about licenses for research data and how to apply them. You could also check OpenAIRE Guide for researchers “[Can I reuse someone else’s research data?](https://www.openaire.eu/can-i-reuse-someone-else-research-data)” and “[How do I know if my research data is protected?](https://www.openaire.eu/how-do-i-know-if-my-research-data-is-protected)”. 

You may find useful information about specific licenses for data and software/code below:

*   [Open Source Initiative](https://opensource.org/licenses/) variety of open licenses for free and open source software  
*   [Creative Commons](https://creativecommons.org/)  a set of widely-used machine-, human-, and lawyer-readable licenses appropriate for use with data

Some tools which assist selection processes when applying licenses to your outputs are:

*   [OpenMinted Compatibility Matrix tool](https://services.openminted.eu/support/licenseCompatibilityMatrix): understand the use of licenses in software, services and other works, and check the outcome of combination of multiple licenses. 
*   [EUDAT licence selector](https://ufal.github.io/public-license-selector/) helps to choose the right licence for your data and/or software by answering simple questions or using the search to find the license you want. 

One of the key challenges of the materials science domain is the need to automatically prepare, execute and monitor workflows of calculations as well as to transparently retrieve and store the results in a format which is easy to browse and query. [AiiDA](http://www.aiida.net/)’s design is based on directed graphs to track the provenance of data, and ensure preservation and searchability. Last, complex sequences of calculations can be encoded into scientific workflows. Sharing capabilities of AiiDA have greatly helped scientific repositories like [Materials Cloud](https://www.materialscloud.org/).

**Activity 1**  
Select a dataset or code you have been working on lately and choose a license from the list. What did you choose? Why? Have discussions with your team members about licensing and sharing.

**Activity 2**  
Go to AiiDA and load a calculation that you have recently created or that you are currently working on. What do you see? Make some changes. Can you find the previous version? Can you find the first set of calculations that you did in this sequence?

## Thing 8 - Services and tools to store, publish and analyse data
Open science for nanotechnology, means open resources, databases and other platforms. Scientific output is often hosted in public and interoperable infrastructures to use, ideally freely available, but sometimes with a small /reasonable reproduction cost resulting from creating, maintaining and publishing data. So, nanotechnology data may be published and stored in a laboratory website or repository, an institutional website or repository, subject specific databases, servers or repositories or it may be collocated with the publication/ journal article it relates to. 

Indicative resources:

Registries:

*   [Re3data.org](https://www.re3data.org/) Registry of generic and thematic Research Data Repositories
*   [Nanomaterial Registry](http://www.nanomaterialregistry.org) The Nanomaterial Registry is an authoritative, fully curated resource that archives research data on nanomaterials and their biological and environmental implications. The data is curated from a variety of data sources, including public databases, manufacturers, regulatory and standards agencies, published literature

Hubs:

*   [nanoHUB ](https://nanohub.org/)  nanoHUB.org is a place for computational nanotechnology research, education, and collaboration. The site hosts a rapidly growing collection of [simulation](https://nanohub.org/resources/tools) tools for nanoscale phenomena that run in the cloud and are accessible through a web browser. In addition, nanoHUB provides [online presentations](https://nanohub.org/resources/onlinepresentations), cutting-edge [nanoHUB-U short courses](https://nanohub.org/groups/u), [animations](https://nanohub.org/resources/animations), [teaching materials](https://nanohub.org/resources/teachingmaterials), and more. 

Databases:

*   [Nanotechnology knowledge base](https://nanodata.echa.europa.eu/) Database by the European Chemicals Agency (ECHA)
*   [Crystallography Open Database](http://www.crystallography.net/cod/) Open-access collection of crystal structures of organic, inorganic, metal-organics compounds and minerals, excluding [biopolymers](http://www.rcsb.org/).
*   [Bilbao Crystallographic Server ](http://www.cryst.ehu.es/) Database offering crystallographic and solid state programs and utilities
*   [Enanomapper](http://www.enanomapper.net/data) prototype database is part of the computational infrastructure for toxicological data management of engineered nanomaterials, funded by the EC and is used to collect and openly share data among researchers.

Repositories:

*   [Zenodo](https://zenodo.org/) a generic purpose repository for publications, data, software.
*   [Materials Cloud](https://www.materialscloud.org/) , adopts the “repository of repositories” model of Github et al. It aims at creating an ecosystem supporting researchers in various tasks faced with during their work. Sections include educational material, tools to generate and analyze data via the browser and interfaces to facilitate the FAIR sharing of simulation data.
*   [NOMAD](https://nomad-repository.eu/), a data repository that collects a large number of individual computational materials science calculations in one place making them available for a longer period. It enables the confirmatory analysis of materials data, their reuse, and repurposing. NOMAD makes scientific data citable as one can request digital object identifiers.

_Several platforms integrate centralized data repositories with software frameworks used to compute data such as:_

*   [AFLOWlib](http://aflowlib.org/), with Aflow (Automatic Flow). Aflow is a software framework for high-throughput calculation of crystal structure properties of alloys, intermetallics and inorganic compounds.
*   [OQMD (Open Quantum Materials Database)](http://oqmd.org/) is a database of DFT-calculated thermodynamic and structural properties based on qmpy, a toolkit for storing crystal structure data, automating calculations, handing computational resources and performing thermodynamic analysis.
*   [Open Materials Database](http://openmaterialsdb.se/) with the [high-throughput toolkit (httk)](http://httk.openmaterialsdb.se/). httk is a toolkit for preparing and running calculations, analyzing the results, and storing the results and outcome in a global and/or in a personalized database.

Educational Resources:

*   [nanoHUB ](https://nanohub.org/) nanoHUB provides [online presentations](https://nanohub.org/resources/onlinepresentations), cutting-edge [nanoHUB-U short courses](https://nanohub.org/groups/u), [animations](https://nanohub.org/resources/animations), [teaching materials](https://nanohub.org/resources/teachingmaterials), and more.
*   The typical research cycle which starts from learning to simulating and finally to publishing the final and curated results is mirrored in [Materials Cloud](https://www.materialscloud.org/) via its five main sections: LEARN, WORK, DISCOVER, EXPLORE and ARCHIVE. At the learning section, users can find educational materials and videos. Moreover, simulation services, turnkey solutions and data analytics tools are provided in other sections helping the scientists to perform their simulations.

**Activity 1 - re3data**  
Go to re3data and search for a data repository based on your area and nanotechnology focus. What are the additional information provided by their functions? Are they useful to you? Are they relevant to the FAIR principles?

**Activity 2**  
Looking after your data: Where do you usually store your data? Do you identify any major differences with those repositories listed in re3data for example?

**Activity 3**  
Archiving your data: What data should be kept or destroyed after the end of your project? For how long should data be kept after the end of your project? Where will the data you keep be archived? When will data be moved into the archive? Who is responsible for moving data to the archive and maintaining them?

**Activity 4**  
Sharing your data: Who else has a right to see or use this data during the project? What data should or shouldn’t be shared openly and why? Who should have access to the final dataset and under what conditions? How will you share your final dataset?

## Thing 9 - Nanotechnology and High Performance Computing (HPC)
In physics, there are two methods used for manipulation of nano-materials:

*   <span style="text-decoration:underline;">Models:</span> that use specific parameters, have the same results but are not that precise in terms of accuracy in measuring quantities
*   <span style="text-decoration:underline;">First principle calculation:</span> where analysis takes place directly on the atoms that are concerned and more precisely than with models

The most popular method is the first principle calculation, however it is computationally intensive and is best undertaken within HPC environments.

In Europe, there are initiatives aiming to tackle big data and intensive analysis issues in a uniform way, such as [HELIX](https://hellenicdataservice.gr/main/) (Hellenic Data Service) in Greece, a convergence e-infrastructure with Virtual Machines, cloud computing and HPC capabilities which lowers expected time for analysis to just a few minutes. The [European Open Science Cloud](https://www.eosc-portal.eu/) (EOSC) which is currently under development, will eventually become a complete and trusted environment of such services and infrastructures serving the whole research lifecycle.

**Activity 1**  
Discussion Have you experienced any challenges when managing and analysing your data relevant to the time of analysis required to take place? How did you overcome them?

## Thing 10 - More best practices
These are some additional best practices to follow in order to improve data and software reusability by others, including oneself when accessing data that have been generated long time ago. Adding terms and conditions of accessibility is an option to consider when data can’t be shared completely open. To share data, consult Thing 8 - Services and tools to store, publish and analyse data. To get started, some issues to consider are:

**Data structures:** Keep consistent file and folder naming conventions across linked projects.

**Containerisation:** For data processing pipelines

*   [Singularity](https://singularity.lbl.gov/)
*   [Docker](https://www.docker.com/)
*   Or use Virtual environments provides, such as the[ Characterisation Virtual Lab](https://www.cvl.org.au/)

**Activity 1**  
How do you structure and name your folders and files? How do you manage different versions of your files? What additional information is required to understand the data?

**Activity 2 - Discussion + Action**  
What Can You Do?

*   Release some or all of the project metadata – your call, as a simple rule, the more the better!
*   Curate existing datasets to make available in the future - you set the upload schedule.
*   Contribute your scripts/code
*   Have discussions with your team members about licensing and sharing.
*   Create a data management plan.

**Activity 2 - Questions**  
Go through the questions from the [Horizon2020 guide to create a FAIR Data Management Plan](http://ec.europa.eu/research/participants/data/ref/h2020/grants_manual/hi/oa_pilot/h2020-hi-oa-data-mgt_en.pdf) and see if you can already answer many of them. Then check the [NanoCommons Data Management Plan](https://www.nanocommons.eu/wp-content/uploads/2018/07/NanoCommons_D10.1-Initial-draft-of-data-management-plan.pdf) and compare with your responses. Do you identify any differences?

Recommended extra reading [Ten Simple Rules for Creating a Good Data Management Plan](https://doi.org/10.1371/journal.pcbi.1004525),[ Ten Simple Rules for Reproducible Computational Research](https://doi.org/10.1371/journal.pcbi.1003285) and[ Ten principles for machine-actionable data management plans](https://doi.org/10.1371/journal.pcbi.1006750), these papers will help you connect all the concepts that you have learned so far.

## Notes
[^1]:
     Check also p.44 “B. Life Cycle of Nanomaterials” in _CODATA-VAMAS Working Group On the Description of Nanomaterials, ., & Rumble, J. (2016, June 30). Uniform Description System for Materials on the Nanoscale, Version 2.0. Zenodo. [http://doi.org/10.5281/zenodo.56720](http://doi.org/10.5281/zenodo.56720)_

[^2]:
     Crystallographic Information Framework (CIF) “A well-established standard file structure for the archiving and distribution of crystallographic information, CIF is in regular use for reporting crystal structure determinations to Acta Crystallographica and other journals. Sponsored by the International Union of Crystallography, the current standard dates from 1997. As of July 2011, a new version of the CIF standard is under consideration.” More information, tools and use cases are available here: [https://rd-alliance.github.io/metadata-directory/standards/cif-crystallographic-information-framework.html](https://rd-alliance.github.io/metadata-directory/standards/cif-crystallographic-information-framework.html)

[^3]:
     UPF stands for "Unified Pseudopotential Format" and it is used to describe pseudopotentials (initial values to facilitate the simulations performed on e.g. crystal structures that can be described in a e.g. CIF file). UPF is widely used by the nanotechnology community. Recent developments on the format structure show that there are efforts in converting UPF to XML: [http://www.quantum-espresso.org/pseudopotentials/unified-pseudopotential-format](http://www.quantum-espresso.org/pseudopotentials/unified-pseudopotential-format)

[^4]:
     [https://rd-alliance.github.io/metadata-directory/standards/](https://rd-alliance.github.io/metadata-directory/standards/) 

[^5]:
     [https://doi.org/10.25504/FAIRsharing.njqq5b](https://doi.org/10.25504/FAIRsharing.njqq5b) 

[^6]:
     [https://doi.org/10.25504/FAIRsharing.vy0p71](https://doi.org/10.25504/FAIRsharing.vy0p71) 

