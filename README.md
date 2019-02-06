## Welcome to our GSoC 2019 Idea List
Here you can find our Idea List for the Google Summer of Code (GSoC). Check the [GSoC main site](http://code.google.com/soc) for general information about the program, how to apply, timeline, faq, and more. 

### How to get in touch with us
If you are interested in one of the topics write us to our mailing list: bexis-support AT uni-jena.de

### Who we are
Most of us are working in the [fusion chair](http://fusion.cs.uni-jena.de/fusion/) of the University of Jena, Germany. We develop (not only) BEXIS 2 which serves as data manangement platform for a [couple of research projects](http://bexis2.uni-jena.de/community/partners-instances/) in Germany. We work on semantic technologies. We do data management for several biodiversity research programms in Germany.

![BEXIS2](http://bexis2.uni-jena.de/wp-content/themes/theme-BexisTheme/images/logo.jpg) is a free and open source software supporting researchers in managing their data throughout the entire data life cycle. [BEXIS 2](http://bexis2.uni-jena.de/) has a lot of core data management [features](http://bexis2.uni-jena.de/bexis2-software/features/) supporting the [FAIR data principles](https://www.go-fair.org/fair-principles/) and first [modules](https://github.com/bexis) enhancing it with additional components.

To strenghten the operation of BEXIS 2 within the data community we propose a set of ideas and would be very happy to welcome new collaborators. 

# Idea List
**1. Dataset Findability**  
Finding relevant data is getting more and more important for scholars. Apart from conventional data portals, external search providers such as Google also offer first search applications over datasets. In order to better find and index BEXIS 2 data, the idea of this project is to enrich BEXIS2 metadata with additional information based on vocabulary such as schema.org, bioschema.org, DCAT, … That will allow external search providers to index and display open BEXIS 2 data properly and enhance the visibility of that datasets.  
- Outcomes: Enriched html for every dataset page
- Skillset: Html, JavaScript, MarkupLanguages
- Possible mentors: Martin, Felicitas
- Project complexity: Easy

**2.	Data Visualization**  
The scientific data stored in BEXIS 2 differs in structure and content. Currently, the data is displayed in a plain table. A visual representation of the data would on the one hand help scientists and data curators to analyze data in their entirety, detect outliers or clean the data to improve the data quality and on the other hand it would help users to more easily explore the dataset.The aim of the project is to develop a module for BEXIS 2, which can display the data in different graphs using a meaningful JavaScript framework. Large dataset should be considered as a possible input for the framework. Therefore strategies to deal with it needs be developed and implemented. Furthermore topics like precompiling of graphs for the visualizations of defined variables or an automated selection of meaningful visualization types can also be addressed within this project.  
- Outcomes: A set of viz for the end user
- Skillset: Html, CSS, JavaScript, C#, MVC
- Possible mentors: Sirko, Martin
- Project complexity: Medium

**3.	Connect to Omic Archives:**  
As next generation sequencing (NGS) technology continues to improve, the amount of data generated per run grows exponentially. This results in a huge amount of raw data which are independently stored in public repositories such as GenBank, EMBL, EBI. Other related data forming teh omics ecosystem counts here too. However, some project-related data repositories, such as BEXIS 2 2, requires the access to such data to perform integrated analysis for the same project related data. Thus, accessing and extracting such raw data (sequence data) from public repositories to be available for local repositories is required. A preliminary need is viral to link the data from those portals to our data system since it stores the analysis of the raw data. The link should cover all the public archives that can be retrieved from an assertion number or a project identifier. Further instruction is to adapt BEXIS 2 to those public sequencing data portals. The adaption should cover the structure, the hierarchy and the ability to combine visualization of data from both portals.  
- Outcomes: Omics archives harvester (to fill metadata) 
- Skillset: ASP.Net, C#, MVC5, SQL, HTML, Javascript/JQuery, CSS
- Possible mentors: Felicitas, Hamdi
- Project complexity: Medium

**4.	Results Presentation**  
As an information system for scientific data, BEXIS 2 must present the datasets in a usefull manner to the end users. The main access point for users is the search. Currently, the results of a dataset search in our system are listed within a grid including typical functions, e.g. sorting, filtering and paging. But this representation does not to work well for a lot of scientists. They prefer a list view with designed elements. We would like to enhance the usability and user acceptance by offering both representations side-a-side. Based on the requirements of our partners that use BEXIS 2, this enhancement must work with heterogeneous metadata schemas within a single instance and needs to be configurable at runtime.
- Outcomes: Designed search represantation
- Skillset: Html, JavaScript, CSS, C#, ASP.NET, MVC 5
- Possible mentors: Sven, David, Neha
- Project complexity: Medium

**5.	Enhance Search:  Geographic Visualization of Research Data**  
BEXIS2 provides a faceted search on metadata. However, research data within BEXIS 2 often includes spatial information (e.g. bounding box or coordinates) which is currently not considered for the search and filtering of dataset. 
Within this project geographic visualization techniques together with an advanced search and filtering facility using spatial information should be developed and implemented. 
- Outcomes: BEXIS2 module wich offers different viz to the end user
- Skillset: Html, JavaScript, CSS, C#, ASP.NET, MVC 5
- Possible mentors: Sven Roman, Franziska
- Project complexity: Medium

**6.	Web Mapping Integration for Graphical Research Area Management Module**  
The representation of all elements (dead or alive trees, research area for a field experiment, traps for insects …) within a defined study site is managed with the Graphical Research Area Management module in BEXIS 2. Thus it helps to support fieldwork coordination by providing functions to generate Cartesian maps of study sites as plots and subplots. It allows planning of the study design and to keep track of the fieldwork history. To simplify orientation during fieldwork these maps should be visualized on a web map together with supplemental information. Standard CRUD operations should be possible. 
- Outcomes: Extended BEXIS2 module
- Skillset: Web mapping framework (OpenLayers, Leaflet), JavaScript, CSS, C#, ASP.NET, MVC 5
- Possible mentors: Franziska, Andreas
- Project complexity: Easy to Medium

**7.	Provenance Management Support of Datasets and Scripts**  
Provenance of a data product is the description of the sequences of steps together with the data and the parameters that led to its creation. Scientists use scripts to perform data analysis and data exploration tasks and connect the results obtained from multiple tools together. This project module aims to develop a provenance management support in BEXIS to connect the scripts and datasets together. This module aims to integrate JupyterHub which provides a collaborative environment for scientists in BEXIS. The scripts which used and generated the datasets uploaded in BEXIS will be connected together to provide the provenance of the experiments. The provenance of these experiments will be further supported by a visualization module.
- Outcomes: BEXIS2 module
- Skillset: Python, Javascript, HTML, CSS
- Possible mentors: Sheeba, David
- Project complexity: Medium

**8. Multi-lingual indexing and search**  
Many datasets are produced in different languages. Their structural and conceptual information is based on the domain experts' knowledge and expertise that may differ from country to country. So having some ontologies applied to integrate these kinds of varieties would make the search and discovery more natural. For example, an English scientist may search a German repository using her domain concepts and natural language (English here). The search engine would convert the domain concepts to the German domain as well as the English search terms to their German equivalent, performs the search, and presents the result with augmented information so that the scientist understands the result. It seems to be a big work package, but for the summer camp, it can be kept small and experimental.
- Outcomes: Ontology, annotation, search index, index files
- Skillset: Protege, Lucene, Solr, Java or .Net, Html
- Possible mentors: Javad, Alsayed, Jan Martin, Sirko
- Project complexity: Hard




