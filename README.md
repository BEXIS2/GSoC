## Welcome to our GSoC 2019 Idea List
Here you can find our Idea List for the Google Summer of Code (GSoC). Check the [GSoC main site](http://code.google.com/soc) for general information about the program, how to apply, timeline, faq, and more. 

### How to get in touch with us
If you are interested in one of the topics write us to our mailing list: bexis-support AT uni-jena.de

### Who we are
Most of us are working in the [fusion chair](http://fusion.cs.uni-jena.de/fusion/) of the University of Jena, Germany. We develop (not only) BEXIS 2 which serves as data manangement platform for a [couple of research projects](http://bexis2.uni-jena.de/community/partners-instances/) in Germany. We work on semantic technologies. We do data management for several biodiversity research programms in Germany.

### About [BEXIS 2](http://bexis2.uni-jena.de/)
![BEXIS2](http://bexis2.uni-jena.de/wp-content/themes/theme-BexisTheme/images/logo.jpg) is a free and open source software supporting researchers in managing their data throughout the entire data life cycle. BEXIS 2 has a lot of core data management [features](http://bexis2.uni-jena.de/bexis2-software/features/) supporting the [FAIR data principles](https://www.go-fair.org/fair-principles/) and first [modules](https://github.com/bexis) enhancing it with additional components.

To strenghten the operation of BEXIS 2 within the data community we propose a set of ideas and would be very happy to welcome new collaborators. 

## Idea List
**1. Dataset Findability**  
Finding relevant data is getting more and more important for scholars. Apart from conventional data portals, external search providers such as Google also offer first search applications over datasets. In order to better find and index BEXIS 2 data, the idea of this project is to enrich BEXIS2 metadata with additional information based on vocabulary such as schema.org, bioschema.org, DCAT, … That will allow external search providers to index and display open BEXIS 2 data properly and enhance the visibility of that datasets.  
- Outcomes: Enriched html for every dataset page
- Skillset: Html, JavaScript, MarkupLanguages
- Possible mentors: Martin, Felicitas
- Project complexity: Easy

**2.	Data Visualization**  
The scientific data stored in BEXIS 2 differs in structure and content. Currently, the data is displayed in a plain table. A visual representation of the data would on the one hand help scientists and data curators to analyze data in their entirety, detect outliers or clean the data to improve the data quality and on the other hand it would help users to more easily explore the dataset.The aim of the project is to develop a module for BEXIS 2, which can display the data in different graphs using a meaningful JavaScript framework. Large dataset should be considered as a possible input for the framework. Therefore strategies to deal with it needs be developed and implemented. Furthermore topics like precompiling of graphs for the visualizations of defined variables or an automated selection of meaningful visualization types can also be addressed within this project.  
- Outcomes: BEXIS2 module
- Skillset: Html, CSS, JavaScript, C#, MVC
- Possible mentors: Sirko, Martin
- Project complexity: Medium

**3.	Connect to Omic Archives:**  
As next generation sequencing (NGS) technology continues to improve, the amount of data generated per run grows exponentially. This results in a huge amount of raw data which are independently stored in public repositories such as GenBank, EMBL, EBI. However, some project-related data repositories, such as BEXIS 2, requires the access to such data to perform integrated analysis for the same project related data. Thus, accessing and extracting such raw data (sequence data) from public repositories to be available for local repositories is required. A preliminary need is viral to link the data from those portals to our data bank since it stores the analysis of the samples. The link should cover all the public archives that can be retrieved from an assertion number or a project identifier.  Further instruction is to adapt BEXIS 2 to those public sequencing data portals. The adaption should cover the structure, the hierarchy and the ability to combine visualization of data from both portals.  
- Outcomes: BEXIS2 module
- Skillset: ASP.Net, C#, MVC5, SQL, HTML, Javascript/JQuery, CSS
- Possible mentors: Felicitas (Connection to GFBIO), Hamdi
- Project complexity: Medium

**4**

**7** are planned at least






