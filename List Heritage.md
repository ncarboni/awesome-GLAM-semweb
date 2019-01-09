## Semantic Web List for Digital (Humanities | Heritage | Art History)

A curated list of various semantic web and linked data resources for heritage, humanities and art history practitioners.  

The list is an extension of [the semantic web awesome list](https://github.com/semantalytics/awesome-semantic-web) specifically targeted for Digital Humanities and its various flavours (Digital Art History, Digital (Cultural?) Heritage, Cultural Computing, etc.). The [the semantic web awesome list](https://github.com/semantalytics/awesome-semantic-web) is the reference for general SM solutions, while this list is specifically target to domain resources which do not belong to the general list (e.g ontologies, specific software widely used within the community, documentation targeting DH practitioners and point of contacts/exchanges). For the purpose of providing to the reader a complete and stand-alone resource, few elements of the [the semantic web awesome list](https://github.com/semantalytics/awesome-semantic-web) will be reported also here.  

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
		- [CIDOC-CRM Tutorial](#cidoc-crm-tutorial)
		- [CIDOC-CRM Modelling examples and documentation](#cidoc-crm-modelling-examples-and-documentation)
	- [Gemeinsame Normdatei \(GND\)](#gemeinsame-normdatei-gnd)
	- [Europeana Data Model](#europeana-data-model)
	- [Dublin Core](#dublin-core)
	- [Open Archives Initiative Object Reuse and Exchange \(OAI-ORE\)](#open-archives-initiative-object-reuse-and-exchange-oai-ore)
	- [ICA Expert Group on Archival Description \(EGAD\)](#ica-expert-group-on-archival-description-egad)
	- [Metadata Object Description Schema \(MADS\)](#metadata-object-description-schema-mads)
	- [BIBFRAME \(Bibliographic Framework Initiative\)](#bibframe-bibliographic-framework-initiative)
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
- [Misc](#misc)
	- [Data Management](#data-management)
	- [Prefix](#prefix)
	- [Ontology](#ontology)
		- [Documentation](#documentation)
		- [Management](#management)
	- [Alignment](#alignment)
	- [Conversion](#conversion)
	- [Visualisation](#visualisation)

<!-- /MarkdownTOC -->


<a id="semantic-web-standards--recommendation"></a>
## Semantic Web Standards & Recommendation

<a id="rdf"></a>
### RDF

- [RDF 1.1 Primer](https://www.w3.org/TR/rdf11-primer/)
- [RDF 1.1 Semantics](https://www.w3.org/TR/rdf11-mt/)
- [RDF 1.1 Concepts and Abstract Syntax](https://www.w3.org/TR/rdf11-concepts/)
- [RDF 1.1: On Semantics of RDF Datasets](https://www.w3.org/TR/rdf11-datasets/)
- [XSD Datatypes](https://www.w3.org/2011/rdf-wg/wiki/XSD_Datatypes)

<a id="rdfs"></a>
### RDFS

- [RDF Schema 1.1](https://www.w3.org/TR/rdf-schema/)

<a id="owl"></a>
### OWL

- [OWL 2 Web Ontology Language Document Overview](https://www.w3.org/TR/owl-overview/)
- [OWL 2 Web Ontology Language Primer](https://www.w3.org/TR/owl-primer/)

<a id="data-shape"></a>
### Data Shape

- [SHACL Core](https://www.w3.org/TR/shacl/)
- [SHACL Advanced](https://www.w3.org/TR/shacl-af/)
- [SHex](http://shex.io)

<a id="sparql"></a>
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

<a id="rdfa"></a>
### RDFa

- [XHTML+RDFa 1.1 - Third Edition](https://www.w3.org/TR/xhtml-rdfa/)
- [RDFa Lite 1.1 - Second Edition](https://www.w3.org/TR/rdfa-lite/)
- [HTML+RDFa 1.1 - Second Edition](https://www.w3.org/TR/html-rdfa/)

<a id="linked-data-fragments-ldf"></a>
### Linked Data Fragments (LDF)

- [Linked Data Fragments](http://linkeddatafragments.org)

<a id="linked-data-notifications"></a>
### Linked Data Notifications

- [Linked Data Notifications](https://www.w3.org/TR/ldn/)

<a id="linked-data-platform"></a>
### Linked Data Platform

- [Linked Data Platform 1.0 Primer](https://www.w3.org/TR/ldp-primer/)
- [Linked Data Platform Best Practices and Guidelines](https://www.w3.org/TR/ldp-bp/)
- [Linked Data Platform 1.0](https://www.w3.org/TR/ldp/)
- [Linked Data Platform 1.0 Test Cases](https://dvcs.w3.org/hg/ldpwg/raw-file/tip/tests/ldp-testsuite.html)


<a id="serialization"></a>
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

 
<a id="ontologies"></a>
## Ontologies

<a id="cidoc-crm"></a>
### CIDOC-CRM

- [Documentation](http://www.cidoc-crm.org/versions-of-the-cidoc-crm): Official website of the CIDOC-CRM
- [RDFS](http://www.cidoc-crm.org/versions-of-the-cidoc-crm) Official version of CIDOC-CRM available in RDF. *No direct link, you can use the latest version available in the page*
- [OWL](http://www.cidoc-crm.org/versions-of-the-cidoc-crm) OWL version of CIDOC-CRM. *No direct link, use the latest version available in the page*.

<a id="cidoc-crm-official-extensions"></a>
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

<a id="cidoc-crm-unofficial-extensions"></a>
#### CIDOC-CRM Unofficial extensions

- [VIR](http://w3id.org/vir): Model for visual and iconographical representations
- [DOREMUS](http://data.doremus.org/ontology/): Model for describing musical performances and recordings

<a id="cidoc-crm-tutorial"></a>
#### CIDOC-CRM Tutorial

- [Long Video Tutorial by Stephen Staad](http://old.cidoc-crm.org/cidoc_tutorial/index.html) - Require Flash
- [Short Video Tutorial by George Bruseker](https://youtu.be/lVQFciW7V4I)

<a id="cidoc-crm-modelling-examples-and-documentation"></a>
#### CIDOC-CRM Modelling examples and documentation

- [Official Website modelling](http://www.cidoc-crm.org/functional-units) and [Best Practices](http://www.cidoc-crm.org/best_practices)
- [Consortium for Open Research Data in the Humanities](https://docs.cordh.net)
- [Swiss Art Research Infrastructure docs](https://docs.swissartresearch.net)
- [Linked Art](https://linked.art)

<a id="gemeinsame-normdatei-gnd"></a>
### Gemeinsame Normdatei (GND)

- [GND Ontology](https://d-nb.info/standards/elementset/gnd) for authority files

<a id="europeana-data-model"></a>
### Europeana Data Model

- [EDM](https://pro.europeana.eu/resources/standardization-tools/edm-documentation)

<a id="dublin-core"></a>
### Dublin Core

- [DCMI Metadata Terms](http://dublincore.org/documents/dcmi-terms/)

<a id="open-archives-initiative-object-reuse-and-exchange-oai-ore"></a>
### Open Archives Initiative Object Reuse and Exchange (OAI-ORE)

- [Vocabulary](http://www.openarchives.org/ore/1.0/vocabulary)


<a id="ica-expert-group-on-archival-description-egad"></a>
### ICA Expert Group on Archival Description (EGAD)

- [Records in Context - Conceptual Model (RiC-CM)](https://www.ica.org/en/egad-ric-conceptual-model)
- [Records in Context - Ontology](#)

<a id="metadata-object-description-schema-mads"></a>
### Metadata Object Description Schema (MADS)

- [Vocabulary](http://www.loc.gov/standards/mads/rdf/v1.html)

<a id="bibframe-bibliographic-framework-initiative"></a>
### BIBFRAME (Bibliographic Framework Initiative)

- [Model Overview](https://www.loc.gov/bibframe/docs/bibframe2-model.html)
- [Vocabulary](http://id.loc.gov/ontologies/bibframe.html)

<a id="world-wide-web-consortium-w3c"></a>
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

<a id="others"></a>
### Others

- [foaf](http://www.foaf-project.org/) - Friend of a Friend (FOAF) ontology.
- [obo-relations](http://obofoundry.org/ontology/ro.html) - Relation Ontology. Relationship types shared across multiple ontologies.
- [schema.org](https://schema.org/docs/datamodel.html) - Structured data on the Internet (Google, Microsoft, Yahoo and Yandex).
- [SPAR](http://www.sparontologies.net) - Semantic Publishing and Referencing Ontologies.
- GeoSPARQL ([DOCS](https://www.opengeospatial.org/standards/geosparql)|[RDF](www.opengis.net/ont/geosparql))
- [Creative Commons Rights Expression](https://creativecommons.org/ns)
- [QUDT](http://www.qudt.org) Quantities, Units, Dimensions and Types Ontologies and Vocabularies
- [Ontology of units of measure](http://www.ontology-of-units-of-measure.org) Dimensions and measurements ontology

<a id="where-to-find-ontologies"></a>
### Where to find ontologies 

- [Linked Open Vocabularies](https://lov.linkeddata.es/)



<a id="mapping-tools"></a>
## Mapping tools

Mapping tools for transforming your data (CSV, XML) into RDF

<a id="x3ml"></a>
### X3ML

X3ML is a transformation engine developed by FORTH. It is perfected to work with CIDOC-CRM, however it does work greatly with other ontologies as well. It is available as web application (3M) and a stand alone app (X3ML). In both cases the input file has to be in XML (for transforming a CSV file to XML see [Mr Data Converter](https://shancarter.github.io/mr-data-converter/)). 

- [3M](http://139.91.183.3/3M/)
- [X3ML](https://github.com/isl/x3ml)

In order to transform the data it is necessary to create a X3ML declaration and a URI Mapping. Examples of both, together with the necessary commands are available at this addresses:

- [Consortium for Open Research Data in the Humanities](https://docs.cordh.net/tool/mapping/)

<a id="karma"></a>
### Karma

[Karma](http://usc-isi-i2.github.io/karma/) is an information integration tool for aggregating, harmonising and transforming diverse data sources (CSV, XML, JSON, KML, Web APIs). The process is driven by an ontology and results in a transformation of the original data in RDF. A graphical user interface help the user map the data and, moreover, it is build to recognize the mapping of data to ontology classes and then uses the ontology to propose a model that ties together these classes. Karma does not only help the user transform the data but it can be used to normalise them too.

<a id="ontop"></a>
### Ontop
  
  [Ontop](https://ontop.inf.unibz.it) is an application developed by the University of Bolzano for creating a virtual RDF Graph on top of your current data source. Mappings can be easily created using [Protege](http://protege.stanford.edu/) and results are queryable using SPARQL 1.0. Moreover, it support reasoning.
  
  


<a id="vocabularies-and-kos"></a>
## Vocabularies and KOS

<a id="general"></a>
### General

- [Getty Art and Architecture Thesaurus](http://vocab.getty.edu/aat/) 
- [Getty Union List of Artist Names](http://vocab.getty.edu/ulan/)
- [Thesaurus of Geographic Names](http://vocab.getty.edu/tgn/)
- Iconclass [keyword search](http://www.iconclass.org/rkd/9/) + [help LOD](http://www.iconclass.org/help/lod)
- [CERL Thesaurus](https://data.cerl.org/thesaurus/) for book heritage
- [Library Congress Subject Headings](http://id.loc.gov/authorities/subjects.html)
- [Thesaurus Graphical Materials](http://id.loc.gov/vocabulary/graphicMaterials.html)

<a id="france"></a>
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


<a id="italy"></a>
### Italy

- [Thesaurus Portale della Cultural Italiana (PICO)](http://www.culturaitalia.it/pico/thesaurus/4.3/thesaurus_4.3.0.skos.xml#http://culturaitalia.it/pico/thesaurus/4.1%23beni_materiali_della_tradizione_e_del_folklore)
- [Soggettario Biblioteca Nazionale Centrale Firenze](http://thes.bncf.firenze.sbn.it/ricerca.php)

<a id="where-to-find-controlled-vocabulariesthesauri"></a>
### Where to find controlled vocabularies/thesauri 

- [Bartoc](https://bartoc.org)

<a id="vocabulary--kos-management"></a>
## Vocabulary / KOS Management

- [Skosmos](http://skosmos.org) Access SKOS vocabularies with SPARQL or API
- [VocBench](http://vocbench.uniroma2.it) Web-based, multilingual, collaborative platform for managing OWL, SKOS(/XL) and generic RDF datasets.
- [Ginco](https://github.com/culturecommunication/ginco) Collaborative management and alignment of vocabularies.
- [Opentheso](https://github.com/miledrousset/opentheso) Multilingual collaborative management of KOS
- [iqvoc](https://github.com/innoq/iqvoc) SKOS(-XL) Vocabulary Management System for the Semantic Web.
- [TemaTres](https://www.vocabularyserver.com) Manage, share, publish, and re-use SKOS vocabularies. 


<a id="vocabulary-validation--conversion-tools"></a>
### Vocabulary validation & conversion tools

- [Skosify](https://github.com/NatLibFi/Skosify) Validate, convert and improve SKOS vocabularies
- [qSKOS](https://github.com/cmader/qSKOS) Find quality issues in SKOS vocabularies.
- [SKOS Play](http://labs.sparna.fr/skos-play/) Render and visualise thesaurus, taxonomies or controlled vocabularies. Furthermore, convert Excel spreadsheets into SKOS files.


<a id="exchange-and-discussions"></a>
## Exchange and discussions 

<a id="conferences"></a>
### Conferences 

- [International Semantic Web Conference (ISWC 2019)](http://iswc2019.semanticweb.org)
- [European Semantic Web Conference (ESWC 2019)](https://2019.eswc-conferences.org)
- [CIDOC - ICOM International Committee for Documentation](http://icom-kyoto-2019.org)
- [Workshop on Humanities in the Semantic Web (WHiSe)](http://whise.kmi.open.ac.uk)
- [Semantic Web in Libraries](http://swib.org)
- [LODLAM Summit](#)

<a id="conference-not-specifically-on-semantic-web-but-with-strong-ties-to-the-community"></a>
### Conference not specifically on Semantic Web, but with strong ties to the community

- [International Conference on Theory and Practice of Digital Libraries (TPDL)](http://www.tpdl.eu)
- [International Conference on Metadata and Semantics Research](http://www.mtsr-conf.org/home)
- [Code4Lib](https://code4lib.org/conference/)
- [European Library Automation Group](https://elag.org/)
- [Digital Heritage](#)


<a id="discussion-groups"></a>
### Discussion groups

- [CIDOC-CRM SIG Mailing List](http://lists.ics.forth.gr/mailman/listinfo/crm-sig)
- [LODLAM - Linked Open Data in Libraries, Archives & Museum Community Group](https://groups.google.com/forum/#!forum/lod-lam)
- [w3c semantic web Mailing List](https://lists.w3.org/Archives/Public/semantic-web/)
- [w3c Linked Open Data Mailing List](https://lists.w3.org/Archives/Public/public-lod/)

<a id="academic-journals"></a>
### Academic Journals

- [Semantic Web Journal](http://www.semantic-web-journal.net/)
- [Journal of Web Semantics](https://www.journals.elsevier.com/journal-of-web-semantics)
- [International Journal of Web and Semantic Technology](http://www.airccse.org/journal/ijwest/ijwest.html)

<a id="knowledge-graph-management"></a>
## Knowledge Graph Management

$ - Proprietary  
OS - OpenSource  

- [Metaphacts](http://metaphacts.com) - (OS)($) platform to to use, interact and build up entry point for RDF Stores.
- [WissKI](http://wiss-ki.eu) - (OS) Drupal-based platform to interact and build entry point for RDF Stores.


<a id="linked-data-platform-ldp"></a>
### Linked Data Platform (LDP)

- [fedora](https://duraspace.org/fedora/) - Repository platform with native linked data support.
- [warp](https://github.com/linkeddata/warp) - Warp an LDP file manager.
- [Marmotta](https://github.com/apache/marmotta) - Apache linked data platform implementation.
- [Elda](https://github.com/epimorphics/elda) - Linked data platform from Epimorphics.
- [LDP4j](https://github.com/ldp4j/ldp4j)
- [gold](https://github.com/linkeddata/gold) - Linked Data server for Go.
- [CarbonLDP](https://github.com/CarbonLDP)
- [trellis](https://github.com/trellis-ldp/trellis)

<a id="books"></a>
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





<a id="editors"></a>
## Editors

<a id="textmate"></a>
### TextMate

[sparql/turtle extension](https://github.com/peta/turtle.tmbundle)

<a id="sublime-text"></a>
### Sublime Text

- [Turtle and SPARQL syntax highlighter](https://github.com/abcoates/sublime-text-turtle-sparql)

<a id="bbedit"></a>
### BBedit

- [Turtle syntax highlighter](https://github.com/njh/bbedit-turtle)

<a id="vim"></a>
### VIM

- [sparql.vim](https://github.com/vim-scripts/sparql.vim) - SPARQL syntax highlighting.
- [vim-sparql](https://github.com/Omer/vim-sparql)
- [semweb.vim](https://github.com/seebi/semweb.vim)

<a id="emacs"></a>
### Emacs

- [sparql-mode](https://github.com/ljos/sparql-mode)

<a id="intellij"></a>
### IntelliJ

- [sparql4idea](https://github.com/mattnathan/sparql4idea) - SPARQL language plugin for IntelliJ IDEA.


<a id="misc"></a>
## Misc

<a id="data-management"></a>
### Data Management

- [Timbuctoo](https://timbuctoo.huygens.knaw.nl) Data management, enrichment and sharing
- [Openrefine](http://openrefine.org) Data cleaning and normalisation

<a id="prefix"></a>
### Prefix 

- [prefix.cc](https://github.com/cygri/prefix.cc) - Source code to the prefix.cc website.

<a id="ontology"></a>
### Ontology

<a id="documentation"></a>
#### Documentation

- [LODE](http://www.essepuntato.it/lode) ontology documentation environment.
- [Widoco](https://github.com/dgarijo/Widoco) Ontology documentation (include LODE).

<a id="management"></a>
#### Management

- [OntoME](http://ontologies.dataforhistory.org) Ontology Management Environment

<a id="alignment"></a>
### Alignment

- [SILK](http://silkframework.org) Linked Data Integration Framework.
- [OnAGUI](https://github.com/lmazuel/onagui) Ontology alignment GUI.
- [Alignment API](http://alignapi.gforge.inria.fr) Tool for Expressing, generating and sharing ontology alignments

<a id="conversion"></a>
### Conversion

- [RDFConvert](https://sourceforge.net/projects/rdfconvert/) - RDFConvert is a simple command-line tool for converting RDF file betweeen different syntax formats.
- [RDF2RDF](http://www.l3s.de/~minack/rdf2rdf/) Java tool to converts RDF files from any format to any format.
- [marc2rdf](https://github.com/DOREMUS-ANR/marc2rdf) Takes as input INTERMARC-XML and UNIMARC-XML files and generates as output RDF.
- [ntcat](https://github.com/cgutteridge/ntcat) Command line tool for concatenating NTriples documents.
- [How to diff RDF](https://www.w3.org/2001/sw/wiki/How_to_diff_RDF)
- [grlc](https://github.com/CLARIAH/grlc) - Web APIs from SPARQL queries.


<a id="visualisation"></a>
### Visualisation

- [Ontology Visualisation](https://github.com/usc-isi-i2/ontology-visualization) Python tool for visualising RDF. Convert rdf to .dot and use Graphviz for constructing a visual representation.