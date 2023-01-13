## awesome GLAM semweb [![Awesome](https://awesome.re/badge.svg)](https://github.com/ncarboni/Awesome-GLAM-semweb)

A curated list of various semantic web and linked data resources for heritage, humanities and art history practitioners.  

The list is an extension of [the semantic web awesome list](https://github.com/semantalytics/awesome-semantic-web) specifically targeted for GLAM (Galleries, Libraries, Archive, Museum). The [the semantic web awesome list](https://github.com/semantalytics/awesome-semantic-web) is the reference for general SM solutions, while this list is specifically target to domain resources which do not belong to the general list (e.g ontologies, specific software widely used within the community, documentation targeting DH practitioners and point of contacts/exchanges). For the purpose of providing to the reader a complete and stand-alone resource, few elements of the [the semantic web awesome list](https://github.com/semantalytics/awesome-semantic-web) will be reported also here.  

The list is public and contributions are welcome.  

<!-- MarkdownTOC levels="2,3,4,5" -->

- [Semantic Web Standards & Recommendation](#semantic-web-standards--recommendation)
	- [RDF](#rdf)
	- [RDFS](#rdfs)
	- [OWL](#owl)
	- [Data Shape](#data-shape)
	- [SPARQL](#sparql)
	- [RDFa](#rdfa)
	- [Linked Data Fragments \(LDF\)](#linked-data-fragments-ldf)
	- [Linked Data Notifications](#linked-data-notifications)
	- [Linked Data Platform](#linked-data-platform)
- [Serialization](#serialization)
- [Ontologies](#ontologies)
	- [CIDOC-CRM](#cidoc-crm)
		- [CIDOC-CRM Official extensions](#cidoc-crm-official-extensions)
		- [CIDOC-CRM Unofficial extensions](#cidoc-crm-unofficial-extensions)
		- [CIDOC-CRM/FRBRoo Tutorials](#cidoc-crmfrbroo-tutorials)
		- [CIDOC-CRM Modelling examples and documentation](#cidoc-crm-modelling-examples-and-documentation)
	- [Gemeinsame Normdatei \(GND\)](#gemeinsame-normdatei-gnd)
	- [Europeana Data Model](#europeana-data-model)
	- [Dublin Core](#dublin-core)
	- [Open Archives Initiative Object Reuse and Exchange \(OAI-ORE\)](#open-archives-initiative-object-reuse-and-exchange-oai-ore)
	- [Encoded Archival Context for Corporate Bodies, Persons, and Families \(EAC-CPF\)](#encoded-archival-context-for-corporate-bodies-persons-and-families-eac-cpf)
	- [ICA Expert Group on Archival Description \(EGAD\)](#ica-expert-group-on-archival-description-egad)
	- [Metadata Object Description Schema \(MADS\)](#metadata-object-description-schema-mads)
	- [BIBFRAME \(Bibliographic Framework Initiative\)](#bibframe-bibliographic-framework-initiative)
	- [BIBO \(Bibliographic Ontology Specification\)](#bibo-bibliographic-ontology-specification)
	- [Resource Description Access Ontology](#resource-description-access-ontology)
	- [PREMIS](#premis)
	- [World Wide Web Consortium \(W3C\)](#world-wide-web-consortium-w3c)
	- [Others](#others)
	- [Where to find ontologies](#where-to-find-ontologies)
- [Mapping tools](#mapping-tools)
	- [X3ML](#x3ml)
	- [Karma](#karma)
	- [Ontop](#ontop)
- [Vocabularies and KOS](#vocabularies-and-kos)
	- [General](#general)
	- [France](#france)
	- [Italy](#italy)
	- [Where to find controlled vocabularies/thesauri](#where-to-find-controlled-vocabulariesthesauri)
- [Vocabulary / KOS Management](#vocabulary--kos-management)
	- [Vocabulary validation & conversion tools](#vocabulary-validation--conversion-tools)
- [Exchange and discussions](#exchange-and-discussions)
	- [Conferences](#conferences)
	- [Conference not specifically on Semantic Web, but with strong ties to the community](#conference-not-specifically-on-semantic-web-but-with-strong-ties-to-the-community)
	- [Discussion groups](#discussion-groups)
	- [Academic Journals](#academic-journals)
- [Knowledge Graph Management](#knowledge-graph-management)
	- [Linked Data Platform \(LDP\)](#linked-data-platform-ldp)
- [Books](#books)
- [Editors](#editors)
	- [TextMate](#textmate)
	- [Sublime Text](#sublime-text)
	- [BBedit](#bbedit)
	- [VIM](#vim)
	- [Emacs](#emacs)
	- [IntelliJ](#intellij)
- [Data Management](#data-management)
	- [OpenRefine Reconciliation services](#openrefine-reconciliation-services)
- [Data Validation](#data-validation)
- [IIIF](#iiif)
- [Misc](#misc)
	- [Prefix](#prefix)
	- [Ontology](#ontology)
		- [Documentation](#documentation)
		- [Management](#management)
	- [Alignment](#alignment)
	- [Conversion](#conversion)
	- [Visualisation](#visualisation)
	- [Images](#images)

<!-- /MarkdownTOC -->


## Semantic Web Standards & Recommendation

### RDF

- [RDF 1.1 Primer](https://www.w3.org/TR/rdf11-primer/)
- [RDF 1.1 Semantics](https://www.w3.org/TR/rdf11-mt/)
- [RDF 1.1 Concepts and Abstract Syntax](https://www.w3.org/TR/rdf11-concepts/)
- [RDF 1.1: On Semantics of RDF Datasets](https://www.w3.org/TR/rdf11-datasets/)
- [XSD Datatypes](https://www.w3.org/2011/rdf-wg/wiki/XSD_Datatypes)

### RDFS

- [RDF Schema 1.1](https://www.w3.org/TR/rdf-schema/)

### OWL

- [OWL 2 Web Ontology Language Document Overview](https://www.w3.org/TR/owl-overview/)
- [OWL 2 Web Ontology Language Primer](https://www.w3.org/TR/owl-primer/)

### Data Shape

- [SHACL Core](https://www.w3.org/TR/shacl/)
- [SHACL Advanced](https://www.w3.org/TR/shacl-af/)
- [SHex](http://shex.io)

### SPARQL

- [SPARQL 1.1 Overview](https://www.w3.org/TR/sparql11-overview/)
- [SPARQL 1.1 Query Language](https://www.w3.org/TR/sparql11-query/)
- [SPARQL 1.1 Update](https://www.w3.org/TR/sparql11-update/)
- [SPARQL 1.1 Service Description](https://www.w3.org/TR/sparql11-service-description/)
- [SPARQL 1.1 Federated Query](https://www.w3.org/TR/sparql11-federated-query/)
- [SPARQL 1.1 Query Results JSON Format](https://www.w3.org/TR/sparql11-results-json/)
- [SPARQL 1.1 Query Results CSV and TSV Formats](https://www.w3.org/TR/sparql11-results-csv-tsv/)
- [SPARQL 1.1 Query Results XML Format (Second Edition)](https://www.w3.org/TR/rdf-sparql-XMLres/)
- [SPARQL 1.1 Entailment Regimes](https://www.w3.org/TR/sparql11-entailment/)
- [SPARQL 1.1 Protocol](https://www.w3.org/TR/sparql11-protocol/)
- [SPARQL 1.1 Graph Store HTTP Protocol](https://www.w3.org/TR/sparql11-http-rdf-update/)

### R2RML

- [R2RML: RDB to RDF Mapping Language](https://www.w3.org/TR/r2rml/)

### RDFa

- [XHTML+RDFa 1.1 - Third Edition](https://www.w3.org/TR/xhtml-rdfa/)
- [RDFa Lite 1.1 - Second Edition](https://www.w3.org/TR/rdfa-lite/)
- [HTML+RDFa 1.1 - Second Edition](https://www.w3.org/TR/html-rdfa/)

### Linked Data Fragments (LDF)

- [Linked Data Fragments](http://linkeddatafragments.org)

### Linked Data Notifications

- [Linked Data Notifications](https://www.w3.org/TR/ldn/)

### Linked Data Platform

- [Linked Data Platform 1.0 Primer](https://www.w3.org/TR/ldp-primer/)
- [Linked Data Platform Best Practices and Guidelines](https://www.w3.org/TR/ldp-bp/)
- [Linked Data Platform 1.0](https://www.w3.org/TR/ldp/)
- [Linked Data Platform 1.0 Test Cases](https://dvcs.w3.org/hg/ldpwg/raw-file/tip/tests/ldp-testsuite.html)


## Serialization

| Format  | Description | Mime-type |
| :--- | :--- | :---: |
| [Turtle](https://www.w3.org/TR/turtle/) | Terse RDF Triple Language. | `text/turtle`, `application/x-turtle` |
| [TriG](https://www.w3.org/TR/trig/) | Plain text format for serializing named graphs and RDF Datasets. | `application/trig`, `application/x-trig` |
| [JSON-LD](https://json-ld.org/) | JSON-based Serialization for Linked Data. | `application/ld+json` |
| [RDF/JSON](https://www.w3.org/TR/rdf-json/) | RDF 1.1 JSON Alternate Serialization. | `application/rdf+json` |
| [N-Triples](https://www.w3.org/TR/n-triples/) | Line-based syntax for RDF datasets. |  `application/n-triples` |
| [N-Quads](https://www.w3.org/TR/n-quads/) | Line-based syntax for RDF datasets. | `application/n-quads`, `text/x-nquads`, `text/nquads` |
| [Notation3](https://www.w3.org/TeamSubmission/n3/) | Notation3 (N3): A readable RDF syntax. | `text/n3`, `text/rdf+n3` |
| [RDF/XML](https://www.w3.org/TR/REC-rdf-syntax/) | RDF/XML Syntax Specification. | `application/rdf+xml`, `application/xml` |
| [TriX](http://www.hpl.hp.com/techreports/2004/HPL-2004-56.html) | RDF Triples in XML. | `application/trix` |
| [HDT](https://www.w3.org/Submission/2011/03/) | Binary RDF Representation for Publication and Exchange. | `application/x-binary-rdf` |
| [aREF](https://gbv.github.io/aREF/aREF.html) | Another RDF Encoding Form. | |

 
## Ontologies

### CIDOC-CRM

- [Documentation](http://www.cidoc-crm.org/versions-of-the-cidoc-crm): Official website of the CIDOC-CRM
- [RDFS](http://www.cidoc-crm.org/versions-of-the-cidoc-crm) Official version of CIDOC-CRM available in RDF. *No direct link, you can use the latest version available in the page*
- [OWL](http://www.cidoc-crm.org/versions-of-the-cidoc-crm) OWL version of CIDOC-CRM. *No direct link, use the latest version available in the page*.
- [CIDOC-CRM Periodic Table](https://remogrillo.github.io/cidoc-crm_periodic_table/)  Visualize and search the CRM in a user-friendly interface. 

#### CIDOC-CRM Official extensions

- [CRMdig](http://www.cidoc-crm.org/crmdig): Model for provenance metadata
- [CRMsci](http://www.cidoc-crm.org/crmsci): Scientific observation model
- [CRMinf](http://www.cidoc-crm.org/crminf/): Argumentation model
- [FRBRoo](http://www.cidoc-crm.org/frbroo): Functional Requirement for Bibliographic Records
- [PRESSoo](http://www.cidoc-crm.org/pressoo/): Modelling of bibliographical information
- [CRMpc](http://www.cidoc-crm.org/versions-of-the-cidoc-crm): Modelling .1 properties in CRM as n-ary relationship. *no direct link download the CRM-PC file from the latest CRM version*
- [CRMgeo](http://www.cidoc-crm.org/crmgeo/): Spatiotemporal model
- [CRMba](http://www.cidoc-crm.org/crmba): Model for archaeological buildings
- [CRMtex](http://www.cidoc-crm.org/crmtex): Model for the study of ancient text
- [CRMarcheo](http://www.cidoc-crm.org/crmarchaeo/): Excavation model

#### CIDOC-CRM Unofficial extensions

- [VIR](http://w3id.org/vir): Model for visual and iconographical representations
- [DOREMUS](http://data.doremus.org/ontology/): Model for describing musical performances and recordings

#### CIDOC-CRM/FRBRoo Tutorials

- [Long Video Tutorial by Stephen Staad](http://old.cidoc-crm.org/cidoc_tutorial/index.html) - Require Flash
- [Short Video Tutorial by George Bruseker](https://youtu.be/lVQFciW7V4I)
- [FRBRoo Tutorial](http://83.212.168.219/FRBR_Tutorial/)

#### CIDOC-CRM Modelling examples and documentation

- [Official Website modelling](http://www.cidoc-crm.org/functional-units) and [Best Practices](http://www.cidoc-crm.org/best_practices)
- [Reference Data Models](https://docs.swissartresearch.net/instruction/) - Ready-Made data patterns for describing Person, Artwork, Documents, Events and more.
- [Consortium for Open Research Data in the Humanities](https://docs.cordh.net) - Basic shared pattern for interoperable CRM
- [Linked Art](https://linked.art) - Art Museum Application Profile for CRM in JSON-LD.
- [DOPHEDA](https://chin-rcip.github.io/collections-model/) - Project of the Canadian Heritage Information Network to foster the development of LOD in heritage institutions, including a Data Model based on CIDOC CRM


### Gemeinsame Normdatei (GND)

- [GND Ontology](https://d-nb.info/standards/elementset/gnd) for authority files

### Europeana Data Model

- [EDM](https://pro.europeana.eu/resources/standardization-tools/edm-documentation)

### Dublin Core

- [DCMI Metadata Terms](http://dublincore.org/documents/dcmi-terms/)

### Open Archives Initiative Object Reuse and Exchange (OAI-ORE)

- [Vocabulary](http://www.openarchives.org/ore/1.0/vocabulary)

### Encoded Archival Context for Corporate Bodies, Persons, and Families (EAC-CPF)

- [EAC-CPF Description Ontology for Linked Archival Data](https://labs.regesta.com/progettoReload/wp-content/uploads/2013/10/eac-cpf.html)

### ICA Expert Group on Archival Description (EGAD)

- [Records in Context - Conceptual Model (RiC-CM)](https://www.ica.org/en/egad-ric-conceptual-model)
- [Records in Context - Ontology](#)

### Metadata Object Description Schema (MADS)

- [Vocabulary](http://www.loc.gov/standards/mads/rdf/v1.html)

### BIBFRAME (Bibliographic Framework Initiative)

- [Model Overview](https://www.loc.gov/bibframe/docs/bibframe2-model.html)
- [Vocabulary](http://id.loc.gov/ontologies/bibframe.html)

### BIBO (Bibliographic Ontology Specification)

- [Vocabulary](http://bibliontology.com)

### Resource Description Access Ontology

- [RDA Registry](http://www.rdaregistry.info/rgAbout/rdaont/)

### PREMIS

- [Vocabulary](http://id.loc.gov/ontologies/premis-3-0-0.html) of digital preservation metadata

### World Wide Web Consortium (W3C)

- [Web Annotation Vocabulary](https://www.w3.org/TR/annotation-vocab/)
- [WGS84](https://www.w3.org/2003/01/geo/) - Basic Geo (WGS84 lat/long) Vocabulary.
- [skos](http://www.w3.org/2004/02/skos/core.html) - SKOS Simple Knowledge Organization System.
- [skos-xl](http://www.w3.org/TR/skos-reference/skos-xl.html) - SKOS Simple Knowledge Organization System eXtension for Labels.
- [vcard](https://www.w3.org/TR/vcard-rdf/) - vCard Ontology - for describing People and Organizations.
- [void](https://www.w3.org/TR/void/) - Describing Linked Datasets with the VoID Vocabulary.
- [time](https://w3c.github.io/sdw/time/) - Time Ontology in OWL.
- [org](https://www.w3.org/TR/vocab-org/) - The Organization Ontology.
- [dqv](http://www.w3.org/ns/dqv#) - Vocabulary for describing quality metadata.
- [PROV-O](https://www.w3.org/TR/prov-o/) - Represent provenance information.

### Others

- [foaf](http://www.foaf-project.org/) - Friend of a Friend (FOAF) ontology.  
- [obo-relations](http://obofoundry.org/ontology/ro.html) - Relation Ontology. Relationship types shared across multiple ontologies.  
- [RELATIONSHIP](http://vocab.org/relationship/) - Vocabulary for describing relationships between people.
- [BIO](http://vocab.org/bio/) - Vocabulary for describing biographical information.  
- [schema.org](https://schema.org/docs/datamodel.html) - Structured data on the Internet (Google, Microsoft, Yahoo and Yandex).
- [SPAR](http://www.sparontologies.net) - Semantic Publishing and Referencing Ontologies.  
- GeoSPARQL ([DOCS](https://www.opengeospatial.org/standards/geosparql)|[RDF](www.opengis.net/ont/geosparql))  
- [Creative Commons Rights Expression](https://creativecommons.org/ns)  
- [QUDT](http://www.qudt.org) Quantities, Units, Dimensions and Types Ontologies and Vocabularies  
- [Ontology of units of measure](http://www.ontology-of-units-of-measure.org) Dimensions and measurements ontology

### Where to find ontologies 

- [Linked Open Vocabularies](https://lov.linkeddata.es/)



## Mapping tools

Mapping tools for transforming your data (CSV, XML) into RDF

### X3ML

X3ML is a transformation engine developed by FORTH. It is perfected to work with CIDOC-CRM, however it does work greatly with other ontologies as well. It is available as web application (3M) and a stand alone app (X3ML). In both cases the input file has to be in XML (for transforming a CSV file to XML see [Mr Data Converter](https://shancarter.github.io/mr-data-converter/)). 

- [3M](http://139.91.183.3/3M/)
- [X3ML](https://github.com/isl/x3ml)

In order to transform the data it is necessary to create a X3ML declaration and a URI Mapping. Examples of both, together with the necessary commands are available at this addresses:

- [Consortium for Open Research Data in the Humanities](https://docs.cordh.net/tool/mapping/)

### Karma

[Karma](http://usc-isi-i2.github.io/karma/) is an information integration tool for aggregating, harmonising and transforming diverse data sources (CSV, XML, JSON, KML, Web APIs). The process is driven by an ontology and results in a transformation of the original data in RDF. A graphical user interface help the user map the data and, moreover, it is build to recognize the mapping of data to ontology classes and then uses the ontology to propose a model that ties together these classes. Karma does not only help the user transform the data but it can be used to normalise them too.

### Ontop
  
  [Ontop](https://ontop-vkg.org) is an application developed by, among others, the University of Bolzano for creating a virtual RDF Graph on top of your current data source. Mappings can be easily created using [Protege](http://protege.stanford.edu/) and results are queryable using SPARQL 1.1. Moreover, it supports reasoning ([OWL 2 QL](https://www.w3.org/TR/owl2-profiles/#OWL_2_QL)).
  
### Ontopic Studio

($) [Ontopic Studio](https://ontopic.ai/en/ontopic-studio/) is a mapping design application targeted at authoring large mappings without writing code. It is fully compliant with the [R2RML](#R2RML) standard.


## Vocabularies and KOS

### General

- [Getty Art and Architecture Thesaurus](http://vocab.getty.edu/aat/) 
- [Getty Union List of Artist Names](http://vocab.getty.edu/ulan/)
- [Thesaurus of Geographic Names](http://vocab.getty.edu/tgn/)
- Iconclass [keyword search](http://www.iconclass.org/rkd/9/) + [help LOD](http://www.iconclass.org/help/lod)
- [CERL Thesaurus](https://data.cerl.org/thesaurus/) for book heritage
- [Library Congress Subject Headings](http://id.loc.gov/authorities/subjects.html)
- [Thesaurus Graphical Materials](http://id.loc.gov/vocabulary/graphicMaterials.html)
- [Nomenclature for Museum Cataloging](https://www.nomenclature.info) + [help LOD](https://www.nomenclature.info/integration.app)

### France

- [Thésaurus de la désignation des objets mobiliers](http://data.culture.fr/thesaurus/page/ark:/67717/T69)
- [Liste d'autorité Actions pour l'indexation des archives locales](http://data.culture.fr/thesaurus/resource/ark:/67717/T2)
- [Liste d'autorité Contexte historique pour l'indexation des archives locales](http://data.culture.fr/thesaurus/resource/ark:/67717/T4)
- [Liste d'autorité Typologie documentaire pour l'indexation des archives locales](http://data.culture.fr/thesaurus/resource/ark:/67717/T3)
- [Nomenclatures HADOC](http://data.culture.fr/thesaurus/resource/ark:/67717/0404efce-2024-4694-bf80-eba4fc2b336c)
- [Techniques photographiques](http://data.culture.fr/thesaurus/resource/ark:/67717/T61)
- [Thésaurus de la désignation des œuvres architecturales et des espaces aménagés](http://data.culture.fr/thesaurus/resource/ark:/67717/T96)
- [Thésaurus-matières pour l'indexation des archives locales](http://data.culture.fr/thesaurus/resource/ark:/67717/Matiere)
- [Vocabulaire des activités des entités productrices d'archives](http://data.culture.fr/thesaurus/resource/ark:/67717/51232822-adac-4a33-aa14-29e2c701a5ee)
- [Vocabulaire des domaines d'action ou objets des entités productrices d'archives](http://data.culture.fr/thesaurus/resource/ark:/67717/f14e8183-5885-46d6-8fc9-17ebd8f3c27e)
- [Vocabulaire pour les techniques photographiques](http://data.culture.fr/thesaurus/resource/ark:/67717/2012b973-ddb2-4540-a775-9157c3c1d7fd)


### Italy

- [Thesaurus Portale della Cultural Italiana (PICO)](http://www.culturaitalia.it/pico/thesaurus/4.3/thesaurus_4.3.0.skos.xml#http://culturaitalia.it/pico/thesaurus/4.1%23beni_materiali_della_tradizione_e_del_folklore)
- [Soggettario Biblioteca Nazionale Centrale Firenze](http://thes.bncf.firenze.sbn.it/ricerca.php)

### China

- [Chinese Iconography Thesaurus (CIT)](https://chineseiconography.org/)

### Where to find controlled vocabularies/thesauri 

- [Bartoc](https://bartoc.org)

## Vocabulary / KOS Management

- [Skosmos](http://skosmos.org) Access SKOS vocabularies with SPARQL or API
- [VocBench](http://vocbench.uniroma2.it) Web-based, multilingual, collaborative platform for managing OWL, SKOS(/XL) and generic RDF datasets.
- [Ginco](https://github.com/culturecommunication/ginco) Collaborative management and alignment of vocabularies.
- [Opentheso](https://github.com/miledrousset/opentheso) Multilingual collaborative management of KOS
- [iqvoc](https://github.com/innoq/iqvoc) SKOS(-XL) Vocabulary Management System for the Semantic Web.
- [TemaTres](https://www.vocabularyserver.com) Manage, share, publish, and re-use SKOS vocabularies. 


### Vocabulary validation & conversion tools

- [Skosify](https://github.com/NatLibFi/Skosify) Validate, convert and improve SKOS vocabularies
- [qSKOS](https://github.com/cmader/qSKOS) Find quality issues in SKOS vocabularies.
- [SKOS Play](http://labs.sparna.fr/skos-play/) Render and visualise thesaurus, taxonomies or controlled vocabularies. Furthermore, convert Excel spreadsheets into SKOS files.


## Exchange and discussions 

### Conferences 

- [International Semantic Web Conference (ISWC 2019)](http://iswc2020.semanticweb.org)
- [European Semantic Web Conference (ESWC 2019)](https://2020.eswc-conferences.org)
- [CIDOC - ICOM International Committee for Documentation](http://network.icom.museum/cidoc/)
- [Workshop on Humanities in the Semantic Web (WHiSe)](http://whise.kmi.open.ac.uk)
- [Semantic Web in Libraries](http://swib.org)
- [LODLAM Summit](https://lod-lam.net/)

### Conference not specifically on Semantic Web, but with strong ties to the community

- [International Conference on Theory and Practice of Digital Libraries (TPDL)](http://www.tpdl.eu)
- [International Conference on Metadata and Semantics Research](http://www.mtsr-conf.org/home)
- [Code4Lib](https://code4lib.org/conference/)
- [European Library Automation Group](https://elag.org/)
- [Digital Heritage](#)
- [Europeana](#)


### Discussion groups

- [CIDOC-CRM SIG Mailing List](http://lists.ics.forth.gr/mailman/listinfo/crm-sig)
- [LODLAM - Linked Open Data in Libraries, Archives & Museum Community Group](https://groups.google.com/forum/#!forum/lod-lam)
- [w3c semantic web Mailing List](https://lists.w3.org/Archives/Public/semantic-web/)
- [w3c Linked Open Data Mailing List](https://lists.w3.org/Archives/Public/public-lod/)
- [GLAM–Wiki initiative](https://en.wikipedia.org/wiki/Wikipedia:GLAM)
- [Wikidata GLAM](https://www.wikidata.org/wiki/Wikidata:GLAM)
- [GLAM Wiki Facebook Group](https://www.facebook.com/groups/GLAMWikiGlobal/)

### Academic Journals

- [Semantic Web Journal](http://www.semantic-web-journal.net/)
- [Journal of Web Semantics](https://www.journals.elsevier.com/journal-of-web-semantics)
- [International Journal of Web and Semantic Technology](http://www.airccse.org/journal/ijwest/ijwest.html)

## Knowledge Graph Management

$ - Proprietary  
OS - OpenSource  
*f* - Free Version  

- [Researchspace](https://www.researchspace.org) - (OS) platform for managing, interacting and building entry points (template, graph authoring) for RDF Stores. Specifically targeting GLAM researchers and institutions.
- [Metaphacts](https://metaphacts.com) - (OS)($) platform for managing, interacting and building entry points (template, graph authoring) for RDF Stores.
- [WissKI](http://wiss-ki.eu) - (OS) Drupal-based platform to interact and build entry point for RDF Stores.
- [LinkedDataHub](https://atomgraph.com/products/linkeddatahub/) - (OS) collaborative data and information management for RDF data. 
- [GraphDB by Ontotext](https://www.ontotext.com/products/graphdb/) - ($)(*f*) RDF Database for Knowledge Graphs. 


### Linked Data Platform (LDP)

- [fedora](https://duraspace.org/fedora/) - Repository platform with native linked data support.
- [warp](https://github.com/linkeddata/warp) - Warp an LDP file manager.
- [Marmotta](https://github.com/apache/marmotta) - Apache linked data platform implementation.
- [Elda](https://github.com/epimorphics/elda) - Linked data platform from Epimorphics.
- [LDP4j](https://github.com/ldp4j/ldp4j)
- [gold](https://github.com/linkeddata/gold) - Linked Data server for Go.
- [CarbonLDP](https://github.com/CarbonLDP)
- [trellis](https://github.com/trellis-ldp/trellis)

## Books

- [Linked Data](https://www.manning.com/books/linked-data)
- [Explorer's Guide to the Semantic Web](https://www.manning.com/books/explorers-guide-to-the-semantic-web)
- [Semantic Web Programming](https://www.wiley.com/en-us/Semantic+Web+Programming-p-9781118080603)
- [Semantic Web for the Working Ontologist](http://workingontologist.org/)
- [Programming the Semantic Web](http://shop.oreilly.com/product/9780596153823.do)
- [Building Ontologies with Basic Formal Ontology](https://mitpress.mit.edu/books/building-ontologies-basic-formal-ontology)
- [Structures for Organizing Knowledge: Exploring Taxonomies, Ontologies, and Other Schema](https://www.amazon.com/Structures-Organizing-Knowledge-Taxonomies-Ontologies/dp/1555706991)
- [Validating RDF Data](http://book.validatingrdf.com/)
- [Demystifying OWL for the Enterprise](https://doi.org/10.2200/S00824ED1V01Y201801WBE017)
- [Learning SPARQL](http://learningsparql.com)
- [Knowledge Representation](http://www.jfsowa.com/krbook/)





## Editors

### TextMate

- [sparql/turtle extension](https://github.com/peta/turtle.tmbundle)

### Sublime Text

- [Turtle and SPARQL syntax highlighter](https://github.com/abcoates/sublime-text-turtle-sparql)
- [SPARQL 1.1, Turtle, TriG, N-Triples, N-Quads and Notation3 syntax highlighter](https://github.com/blake-regalia/linked-data.syntaxes)

### BBedit

- [Turtle syntax highlighter](https://github.com/njh/bbedit-turtle)

### VIM

- [sparql.vim](https://github.com/vim-scripts/sparql.vim) - SPARQL syntax highlighting.
- [vim-sparql](https://github.com/Omer/vim-sparql)
- [semweb.vim](https://github.com/seebi/semweb.vim)

### Emacs

- [sparql-mode](https://github.com/ljos/sparql-mode)

### IntelliJ

- [sparql4idea](https://github.com/mattnathan/sparql4idea) - SPARQL language plugin for IntelliJ IDEA.

## Data Management

- [Timbuctoo](https://timbuctoo.huygens.knaw.nl) Data management, enrichment and sharing
- [Openrefine](http://openrefine.org) Data cleaning and normalisation

### OpenRefine Reconciliation services

- [VIAF](https://viaf.org) & [ORCID](https://orcid.org) — OpenRefine reconciliation services for VIAF, ORCID, and Open Library available in [Github](https://github.com/codeforkjeff/conciliator). To make it work, it is necessary the launch a jar file for its use. After that the endpoint is available at: [http://localhost:8080/reconcile/viaf](http://localhost:8080/reconcile/viaf).  
- [Geonames](http://www.geonames.org) —  The OpenRefine reconciliation services is available in [GitHub](https://github.com/cmharlow/geonames-reconcile). To make it work, it is necessary to launch a python script. After that the endpoint is available at: [http://0.0.0.0:5000/reconcile](http://0.0.0.0:5000/reconcile).  
- [GND](https://lobid.org/gnd) — Reconciliation service offered by [lob-id](https://lobid.org). Endpoint for OpenRefine: [https://lobid.org/gnd/reconcile](http://services.getty.edu/vocab/reconcile/). Possible to "Add columns from reconciled values".  
- [SNAC](http://snaccooperative.org)— Social Networks and Archival Context. Endpoint for OpenRefine: [http://openrefine.snaccooperative.org](http://services.getty.edu/vocab/reconcile/)- [Nomisma](http://nomisma.org) — Nomisma provide stable digital representations of numismatic concepts. Endpoint for OpenRefine: [http://nomisma.org/apis/reconcile](http://nomisma.org/apis/reconcile).   
- [OpenCorporate](https://opencorporates.com/) — Open database of companies. Endpoint for OpenRefine: [https://opencorporates.com/reconcile](https://opencorporates.com/reconcile).  
- [Getty Research Institute](https://www.getty.edu/research/tools/vocabularies/obtain/openrefine.html) - OpenRefine reconciliation services for the Getty Vocabularies (ULAN, TGN, AAT).
- [Nomisma](http://nomisma.org) - OpenRefine reconciliation service for Nomisma. Endpoint for OpenRefine: [http://nomisma.org/apis/reconcile](http://nomisma.org/apis/reconcile). Documentation on their [website](https://numishare.blogspot.com/2017/10/nomisma-launches-openrefine.html)
- [Perio.do](https://test.perio.do) - The OpenRefine reconciliation services is available in [GitHub](https://github.com/periodo/periodo-reconciler).
- [Pleiades]() - OpenRefine reconciliation service for Pleiades. Endpoint for OpenRefine: [https://geocollider-sinatra.herokuapp.com/reconcile](https://geocollider-sinatra.herokuapp.com/reconcile). More information [here](http://geocollider-sinatra.herokuapp.com).
- [GODOT](https://godot.date/home) - OpenRefine reconciliation service for GODOT. Endpoint for OpenRefine: [https://godot.date/api/openrefine/reconcile](https://godot.date/api/openrefine/reconcile).

## Data Validation 

- [pySHACL](https://github.com/RDFLib/pySHACL) - a Python validator for SHACL.
- [SHaclEX](https://github.com/weso/shaclex) - Scala implementation of SHEX and SHACL. Possible to use a demo version from a web interface.
- [RDFUnit](http://rdfunit.aksw.org/) - RDF testing suite. Include but not limited to SHACL.
- [dotNetRDF SHACL](http://langsamu.net/shacl) - SHACL procecssor that can check conformance and validate data graphs against shapes graphs.
- [YASHE](http://www.weso.es/YASHE/) -  ShEx editor with examples
- [Shex validator](http://shex.io/webapps/shex.js/doc/shex-simple.html) - Simple Online Validator for ShEx

## IIIF

- [International Image Interoperability Framework](https://iiif.io/)
- [Awesome IIIF-related resources](https://github.com/IIIF/awesome-iiif)

## Misc


### Prefix 

- [prefix.cc](https://github.com/cygri/prefix.cc) - Source code to the prefix.cc website.

### Ontology

#### Documentation

- [LODE](http://www.essepuntato.it/lode) ontology documentation environment.
- [Widoco](https://github.com/dgarijo/Widoco) Ontology documentation (include LODE).

#### Management

- [OntoME](http://ontologies.dataforhistory.org) Ontology Management Environment
- [Grafo](https://gra.fo/) Collaborative and graphical ontology design

### Alignment

- [SILK](http://silkframework.org) Linked Data Integration Framework.
- [OnAGUI](https://github.com/lmazuel/onagui) Ontology alignment GUI.
- [Alignment API](http://alignapi.gforge.inria.fr) Tool for Expressing, generating and sharing ontology alignments

### Conversion

- [RDFConvert](https://sourceforge.net/projects/rdfconvert/) - RDFConvert is a simple command-line tool for converting RDF file betweeen different syntax formats.
- [RDF2RDF](http://www.l3s.de/~minack/rdf2rdf/) Java tool to converts RDF files from any format to any format.
- [marc2rdf](https://github.com/DOREMUS-ANR/marc2rdf) Takes as input INTERMARC-XML and UNIMARC-XML files and generates as output RDF.
- [ntcat](https://github.com/cgutteridge/ntcat) Command line tool for concatenating NTriples documents.
- [How to diff RDF](https://www.w3.org/2001/sw/wiki/How_to_diff_RDF)
- [grlc](https://github.com/CLARIAH/grlc) - Web APIs from SPARQL queries.


### Visualisation

- [Ontology Visualisation](https://github.com/usc-isi-i2/ontology-visualization) Python tool for visualising RDF. Convert rdf to .dot and use Graphviz for constructing a visual representation.

### Images

- [ImageSnippets](http://www.imagesnippets.com/glam/) - Platform to links RDF descriptions to images

