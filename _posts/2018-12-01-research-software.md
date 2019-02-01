---
title: "Research Software"
---

## Sprinters
[Anna-Lena Lamprecht](https://www.uu.nl/staff/ALLamprecht), [Carlos Martinez Ortiz](https://github.com/c-martinez), [Chris Erdmann](https://github.com/libcce), [Leyla Garcia](https://github.com/ljgarcia), [Mateusz Kuzak](https://github.com/mkuzak), [Paula Andrea Martinez](https://github.com/orchid00/)

## Description:
The [FAIR data principles](https://www.go-fair.org/fair-principles/) are widely known and applied today. What the FAIR principles mean for (scientific) software is an ongoing discussion. However, there are some things on which there is already agreement that they will make software (more) FAIR. In this document, we go for some ‘low hanging fruit’ and describe 10 easy FAIR software things that you can do. To limit the scope, “software” here refers to scripts and packages in languages like R and Python, but not to other kinds of software frequently used in research, such as web-services, web platforms like myexperiment.org or big clinical software suites like OpenClinica.

A [poster](/Top-10-FAIR/files/poster_10things_FAIRsoftware.pdf) summarizing these 10 FAIR software things is also available.

## Audience:
* Researchers who develop software
* [Research Software Engineers](https://researchsoftware.org)

## Goals:
Translate FAIR principles to applicable actions for scientific software

### What is FAIR for software
In the context of this document, we use the following simple definition of FAIR for software:

**Findable**  
Software with sufficiently rich metadata and unique persistent identifier

**Accessible**  
Software metadata is in machine and human readable format.
Software and metadata is deposited in trusted community approved repository.

**Interoperable**  
Software uses community accepted standards and platforms, making it possible for users to run the software.

**Reusable**  
Software has clear licence and documentation

# Things

## Findability

### Thing 1: Create a description of your software
The name alone does not tell people much about your software. In order for other people to find out if they can use it for their purpose, they need to know what it does. A good description of your software will also help other people to find it.

**Activity:**  
Think of minimum set of information (metadata) which will help others find your software. This can include short descriptive text and meaningful keywords.

[Codemeta](https://codemeta.github.io/terms/) is a set of keywords used to describe software and way to structure them in machine readable way. For examples of Codemeta used in software packages see:

* [https://github.com/NLeSC/boatswain/blob/master/codemeta.json](https://github.com/NLeSC/boatswain/blob/master/codemeta.json)
* [https://github.com/datacite/maremma](https://github.com/datacite/maremma)

[Edam](http://edamontology.org/page) is an example of an ontology that provides terminology that can be used to describe bioinformatics software.

Take the [4OSS lesson episode about metadata and registries](https://softdev4research.github.io/4OSS-lesson/05-use-registry/index.html) and walk through the exercise.

This example: http://r-pkgs.had.co.nz/description.html#description

### Thing 2: Register your software in a software registry
People search for research software using search engines like Google. Registering your software in a dedicated registry will make it findable by search engines, because the registries take care about search engine optimization etc. The registries will usually ask you to provide descriptions (metadata) as above.

**Activity:**  
Think of the registries most used in your domain? Do you know about any?
How and where do you usually find software? What kind of keywords do you use when searching?

Here are some examples of research software registries:  
* [bio.tools](https://bio.tools/)
* [Research Software Directory](https://github.com/research-software-directory/research-software-directory) (check if your institution hosts one)
* [rOpenSci Project](https://ropensci.github.io/)
* [Zenodo](https://zenodo.org/)

[4OSS lesson episode about metadata and  registries](https://softdev4research.github.io/4OSS-lesson/05-use-registry/index.html)

### Thing 3: Get and use a unique and persistent identifier for your software
It will help others find and access the particular version of your software.
Unique means that the identifier will point on and only version and location of your software.
Persistent means that it will pointing to the same version and location for long, specified amount of time. For example, Zenodo provides you with a DOI (Digital Object Identifier) that will be resolvable for at least the next 20 years.
Recent initiatives, such as Software Heritage, propose to associate a permalinks as intrinsic SHA1 identifier to software (see example through the id: swh:1:dir:005bc6218c7a0a9ede654f9a177058adcde98a50 / permalinks: [https://archive.softwareheritage.org/swh:1:dir:005bc6218c7a0a9ede654f9a177058adcde98a50/](https://archive.softwareheritage.org/swh:1:dir:005bc6218c7a0a9ede654f9a177058adcde98a50/))

**Activity:**  
If you have registered your software in a registry, chances are good that they provide a unique and persistent identifier. If not, obtain an identifier from another organization. If you have multiple identifiers, choose one that you use as your main identifier. Make sure you use it consistently when referring to your software, e.g. on your own website, code repository or in publications.

[Making your code citable with Zenodo](https://guides.github.com/activities/citable-code/)

## Accessibility

### Thing 4: Make sure that people can download your software
In order for anyone to use your software, they need to be able to download an executable version along with documentation. For interpreted languages like Python and R, the code is also the executable version. For compiled languages like Java and C, the executable version is a binary file, and the code might not be accessible. Downloading the software and documentation is possible, for instance, from a project website, a git repository or from a software registry.

**Activity:**  
Using the identifier as your starting point, ask a colleague to try to get your software (binary/script). Can he/she download it? Does he/she also have access to the documentation? Is there anything preventing him/her from getting to it? Is it hosted on a reliable platform (long term persistent, such as Zenodo, PyPI, CRAN)?

## Interoperability

### Thing 5: Explain the functionality of your software
Your software performs one or more operations that take an input and transform it into the output. To help people use your software, provide a clear and concise description of the operations along with the corresponding input and output data types. For example, the [``wc``](http://man7.org/linux/man-pages/man1/wc.1.html) (word count) command line tool takes a text as input, counts the number of words in it and gives the number of words as output. The [``ClustalW``](https://www.genome.jp/tools-bin/clustalw) tool takes a set of (gene or protein) sequences as input, aligns them and returns a multiple sequence alignment as output.

**Activity:**  
List all operations that your software provides, and describe them along with corresponding input and output data types. If possible, use terms from a domain ontology like EDAM.

### Thing 6: Use standard (community agreed) formats for inputs and outputs
In order for people to use your software, they need to know how to feed data to it -- standard formats are easy ways to exchange data between different pieces of software. By sticking to standards, it is possible to use the output from another piece of software as an input to your software (or the other way around). For example, FASTA is a format for representing molecular sequences (DNA, RNA, protein, …) that most sequence analysis tools can handle. NetCDF is a standard file format used sharing of array-oriented scientific data.

**Activity:**  
What are the relevant standards in your field? Which are the groups/organizations that are responsible for standards in your field? Is there a place where you can find the relevant standards and a detailed description? What other tools use these standards? If possible, use such standard formats as input/output of your software and state which you are using. (Avoid to define your own standards! [http://imgs.xkcd.com/comics/standards.png](http://imgs.xkcd.com/comics/standards.png))

## Reusability

### Thing 7: Document your software
Your software should include sufficient documentation: instructions on how to install, run and use your software. All dependencies of your software should be clearly stated. Provide sufficient examples on how to execute the different operations your software offers, ideally along with example data. [Write the Docs page](https://www.writethedocs.org/guide/writing/beginners-guide-to-docs/) explains and gives examples of good documentation.

**Activity:**  
Ask a colleague to look at your software’s documentation. Is he/she able to install your software? Can he/she run it? Can he/she produce the expected results?

### Thing 8: Give your software a license
A license tells your (potential) users what they are allowed to do with your software (and what not to do), and can protect your intellectual property. Without a license people may spend time trying to figure out if they are allowed to use your software -- make things easy for them. Therefore, it is important that you choose a software license that meets your intentions. [Choose a license website](https://choosealicense.com/) provides a simple guide for picking the right license for your software.

**Activity:**  
* Follow [the 4OSS lesson](https://softdev4research.github.io/4OSS-lesson/03-use-license/index.html) to learn more about licenses and their implications.
* Read [4OSS paper](https://f1000research.com/articles/6-876/v1)

### Thing 9: State how to cite your software
You want to get credit for your work. By providing the citation guideline you will help users of your software to cite your work properly. There is no single right way to do it. Software Sustainability Institute website provides more information and discussion on this topic in a blog post [How to cite and describe software](https://www.software.ac.uk/how-cite-software).

**Activity:**  
Read “[Software citation principles](https://www.force11.org/software-citation-principles)” paper. Read documentation of [Citation File Format](https://citation-file-format.github.io/) and [create CFF file](https://citation-file-format.github.io/cff-initializer-javascript/) for your software.

### Thing 10: Follow best practices for software development
Reusability benefits from good quality of software. There are a number of actions you can take to improve the quality of your software: make your code modular, have code level documentation, provide tests, follow code standards, use version control, etc. There are several guidelines which you can use to guide you in the process such as the [eScience Center Guide](https://guide.esciencecenter.nl/), [the best practices](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.1001745) and [the good enough practices](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005510).

**Activity:**  
Familiarize yourself with the guides provided above. Have a look at your software and create a list of actions which you could follow to improve the quality of your software. Ideally, follow these practices from the very beginning.
