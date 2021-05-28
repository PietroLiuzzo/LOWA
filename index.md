# Linked Open Data for Written Artefacts

**Hamburg 26/5–28/5 2021 (Zoom)**

The training will introduce participants to basic Linked Open Data technologies and show techniques to produce, store, visualize, query, reuse, and share data as Linked Open RDF Data.

Based mainly on the experience of the Beta Maṣāḥǝft project the training will use examples from epigraphy, codicology, and papyrology and will welcome further diverse datasets to be connected.

Trainer: [Pietro Liuzzo](https://orcid.org/0000-0001-5714-4011)


## Preliminary Information and General Introductions from other Courses

These video introductions touch on similar contents, in limited time, and are very useful to get into the themes. The theory is introduced in clear and simple ways. There are related activities and exercises which can be used as how-to.

- Sunoikisis DC LOD sessions
  - [Session 7: Ontologies and Data Modelling](https://github.com/SunoikisisDC/SunoikisisDC-2016-2017/wiki/Session-7:-Ontologies-and-Data-Modelling)
  - [https://github.com/SunoikisisDC/SunoikisisDC-2017-2018/wiki/Linked-Ancient-World-Data](https://github.com/SunoikisisDC/SunoikisisDC-2017-2018/wiki/Linked-Ancient-World-Data)
  - [https://github.com/SunoikisisDC/SunoikisisDC-2018-2019/wiki/Session-6.-Linked-Open-Data-for-Cultural-Heritage](https://github.com/SunoikisisDC/SunoikisisDC-2018-2019/wiki/Session-6.-Linked-Open-Data-for-Cultural-Heritage)
- [Introduction to the Principles of Linked Open Data | Programming Historian](https://programminghistorian.org/en/lessons/intro-to-linked-data)

## Data

Viaf [http://viaf.org/viaf/data/](http://viaf.org/viaf/data/)

Pleiades [https://pleiades.stoa.org/downloads](https://pleiades.stoa.org/downloads)

EDH Data (latin inscriptions) [https://edh-www.adw.uni-heidelberg.de/data](https://edh-www.adw.uni-heidelberg.de/data)

Beta maṣāḥǝft Endpoint (Ethiopian manuscripts) [https://betamasaheft.eu/sparql](https://betamasaheft.eu/sparql)

Papyri.info (documentary papyri) see each entry, links at the bottom of the page

Nomisma (coins and numismatics) [http://nomisma.org/](http://nomisma.org/)

IDEA Community (Zenodo) [https://zenodo.org/communities/eagle-idea?page=1&amp;size=20](https://zenodo.org/communities/eagle-idea?page=1&amp;size=20)

Arachne (Archeological data) [https://arachne.uni-koeln.de/drupal/](https://arachne.uni-koeln.de/drupal/)

Data hub [https://old.datahub.io/dataset?q=CIDOC-CRM](https://old.datahub.io/dataset?q=CIDOC-CRM) (including British Museum)

Wikidata [https://www.wikidata.org/wiki/Wikidata:Main\_Page](https://www.wikidata.org/wiki/Wikidata:Main_Page)

Dbpedia [https://wiki.dbpedia.org/](https://wiki.dbpedia.org/)

Europeana [https://pro.europeana.eu/page/linked-open-data](https://pro.europeana.eu/page/linked-open-data)

PeriodO [PeriodO – Periods, Organized](https://perio.do/en/)

GODOT [https://godot.date/about](https://godot.date/about)

## Useful resources for doing RDF and LOD

[Apache jena](https://jena.apache.org/index.html)

[prefix.cc: namespace lookup for RDF developers](http://prefix.cc/)

[Linked Open Vocabularies (LOV)](https://lov.linkeddata.es/dataset/lov/)

[Ontology Management Environment](https://ontome.dataforhistory.org/)

[Web Protégé](https://webprotege.stanford.edu/)

[Protégé documentation](http://protegeproject.github.io/protege/)

## Programme

### Wednesday 26 May 2021 - The Semantic Web of Data

#### Morning 9–11 _RDF_

9–9.15 Introduction to the training

9.15–10 Wonder me breakout session

10–11 Presentations

- [Introduction to RDF](https://docs.google.com/presentation/d/e/2PACX-1vQVszVZfiQJzf5jfBoeijFQeH-3ks8ixQMAgVDEiYe-xSt9RbFk1eNKkU4aR-f4xHanbd3WCNx4LUAw/pub?start=false&amp;loop=false&amp;delayms=3000)

##### Exercise

Creating an ontology is not easy. Not because of the data or the code, but because of the ontology. Knowledge modelling is not easy. The data models used to represent knowledge need to be easy and are. In this exercise we will try this out.

**Instructions**

Download and install Protege [https://protege.stanford.edu/products.php#desktop-protege](https://protege.stanford.edu/products.php#desktop-protege) or login to use [Web Protégé](https://webprotege.stanford.edu/) online.

Step 1. You will design your ontology from scratch. We do not want to build the one which will be used, but the one which represents our understanding. Examples in the wild include pizzas, movies, cars, etc. We will model &quot; **Books**&quot;. Feeling Lucky? Try &quot;Manuscripts&quot;. Get started how you want. Imagine the user scenario you want. A library, a book shop, your own library, a reading list... Pick the side of representation which you want and model it. Which Classes do you need? Which Properties to connect them? Which vocabularies to point to?

Step 2. Check out which resources you already know (FRBR(oo), Wikidata, Dbpedia, Viaf, etc.) and look for existing ontologies. How and what to align? Perhaps it would have been better to start from this instead?

#### Afternoon 14–16 _SPARQL_

- [OWL and Ontology design basics (RDFS, RDF Plus)](https://docs.google.com/presentation/d/e/2PACX-1vSfPx6OkspZdJSqcVIzCbw6V7prm1_KmjbLPcqKRdwal37FEJQPYXSJ1t7ryw_IOqabkGhzqrdKHb0b/pub?start=false&amp;loop=false&amp;delayms=3000)
- [SPARQL queries and responses](https://docs.google.com/presentation/d/e/2PACX-1vTOA5GP3vdAD2yFj54VmWpSuV-ykf6KOwjaM_O3IPOWAQmdGLhxe-Ibs6O1u7JEruA_d2GGSGI2uwfm/pub?start=false&amp;loop=false&amp;delayms=3000)

##### Exercise

Questions come before Answers. It is way more important to be able to build a query than to read the results. In SPARQL the result&#39;s format is defined with the query. In this exercise you will practice with the formal language to build your queries. You will need to look at the data, and think of the result format.

**Instructions**

First try to reproduce in the [Wikidata query service](https://query.wikidata.org/) a query from the [examples](https://www.wikidata.org/wiki/Wikidata:SPARQL_query_service/queries/examples).

Now produce _your own_ SPARQL query to one of the Endpoints listed in the presentation. You may stay on Wikidata, if you wish and you have identified relevant data for you. You may simply modify one of the examples.

Share your query [here](https://docs.google.com/document/d/1Zrdtr2wWFlFRWe7UyW5vsH2KfIc3UBQoRdn8l3goauA/edit?usp=sharing). An example (the one below) is provided.

Now try to get a map of the current location of &quot;written artefacts&quot; from Wikidata.

You can start from this example query
`````sparql
#defaultView:Map

# Map of Codices in Wikidata at their location (Q213924)

SELECT \*

WHERE {

?manuscript wdt:P31 wd:Q213924 ;

rdfs:label ?itemLabel .

OPTIONAL{?manuscript wdt:P276 ?location .

?location wdt:P625 ?coordinates .}

}
`````
Try and navigate the superclasses of Q213924 and investigate, by navigating an example (e.g. [Q204221](https://www.wikidata.org/wiki/Q204221)), the location property. What do you think?

#### Evening Lecture 16:00 - Irene Vagionakis (UNIBO) on [_EFES and RDF_](https://docs.google.com/presentation/u/0/d/16RoH32CBSX9nC7OoYNohXvmlsQm9YkMvQQJqyrJggmU/edit)

###


### Thursday 27 May 2021 - Using RDF data and reusing it

#### Morning **9–**** 10** Triplestores and annotations

- [Apache Jena Fuseki](https://docs.google.com/presentation/d/e/2PACX-1vS6pI2RguLUncogkU7i4Any_7EdypWMWJHUmuxK3XtgnMlOAOUazR7P2-IbOSUGA8ZrYJNXlu6cLN2t/pub?start=false&amp;loop=false&amp;delayms=3000) [practical demonstration]
- Wikidata, Recogito, Hypothes.is Annotations and data reuse [practical demonstration]
- Practical applications of LOD: FRBR, Lemon and the Lexicon of Ancient Ethiopic

##### Exercise

We want to use the linked data which is available. Finding and getting the data is not the simplest of things. To play with your data, start by setting up your own triplestore.

**Instructions**

Set up a [Fuseki](https://jena.apache.org/download/index.cgi) Triplestore locally (slides have been presented). If you do not like Fuseki, you can consider [Blazegraph](https://github.com/blazegraph/database/wiki/Main_Page). For this I do not have hints regarding configuration, I have never used it, it is however the tool of choice of the edition of Bufalini&#39;s book object of [this article](#_8nlc3hdlttbu).

You can enrich existing data directly, by editing Wikidata. Beta Maṣāḥǝft would love it if you added a few identifiers from the project to Wikidata Entities! Or make annotations with Hypothes.is which use tags pointing to Beta Maṣāḥǝft resources. Make an account and add statements.

You can use software which does the management of things for you.

Annotate with Hypothes.is, based on Web Annotation standard, within the workshop&#39;s group.

Use the URI of the annotations in your own triples.

You can also try and produce with a tool some Linked Open Data and reuse it. For example, log in to [Recogito](https://recogito.pelagios.org/), upload a document or an image and annotate it. Click the download button and download your annotations as RDF.

You can also try this Interoperability test, which aims at getting linked resources, one connection for each. Here I am suggesting some datasets, you can of course check out your own.

- Periplus [RDF from Beta Masaheft](https://betamasaheft.eu/rdf/works/LIT2170Peripl.rdf) [here you have a link on a landing page to get the RDF]
- [Periplus Data from Wikidata](https://www.wikidata.org/wiki/Special:EntityData/Q664162.rdf) (linking to the previous via Beta Maṣāḥǝft ID property) [you have to know how to get the RDF data from Wikidata, the link is set for you]
- Canvas of image from[IIIF manifest ad Heidelberg HEIDI](https://digi.ub.uni-heidelberg.de/diglit/iiif/cpgraec398/manifest.json) (linked from BM data)
- Recogito Annotations of the image of Topographia Christiana map with link to Pleiades Aksum, named and annotated also in the BM dataset
- Pleiades record for [Aksum](https://pleiades.stoa.org/places/39303/turtle) linked from annotations in Recogito

Import all the pieces you have collected into your Fuseki instance. Query!

#### Afternoon 14–16 SKOS and other models

- [Introduction to SKOS](https://docs.google.com/presentation/d/e/2PACX-1vRYCd82LVg-hHgAyOUK4d8zYwb8nDiYscggq7GC4Cd-7GrYB-zJCYGnrCqf1qKRT_8DIEQ3_sG45bPy/pub?start=false&amp;loop=false&amp;delayms=3000)
- How-To examples: [Extracting RDF from TEI/XML with XSLT and XQuery](https://docs.google.com/presentation/d/e/2PACX-1vS2nuF1PCKKjykvh-Pqm_UYGt0a_CH5zrOnij3_JsEj5IqCm-kq40Za88iWpinFw-zoQkxpNf0air5s/pub?start=false&amp;loop=false&amp;delayms=3000)
- Linked Data and Ancient Documents (examples of usage for specific purposes)

##### Exercise

Interacting with controlled vocabularies is as intuitive as it is easy to do wrong (but no worries, no one is going to die!). Try and believe.

**Instructions**

Look at the Language of Bindings Thesaurus (LoB), [https://www.ligatus.org.uk/lob/](https://www.ligatus.org.uk/lob/)

- Download the data
- Store it in Fuseki

Pick a manuscript from Beta Masaheft, look at the images and put together some triples with any editor, which would build up a description of the binding using the Ligatus vocabulary. Note the RDF representation of the manuscripts, containing URIs, which is provided at the bottom of each page. Do not know how to model these? Perhaps [this](#_zajiqcclul5n) article can help.

Do not like manuscripts? Why not download some RDF for a Papyrus from Papyri.info instead? Instead of Ligatus you may link some of the information present in the metadata to the EAGLE Vocabularies or the Getty Art &amp; Architecture Thesaurus.

#### Evening Lecture 16:00 - Tom Gheldof (KULeuven) on [_Trismegistos and LOD_](https://drive.google.com/file/d/18R8WoykrGY3EBjcY45IkIzQ4GcdMr_6c/view?usp=sharing)

###


### Friday 28 May 2021 - Modeling RDF and visualizing Linked Open Data

#### Morning 9–11 Applications

- Modeling Epigraphy with an Ontology: from the state of the art to a community based model
- Mapping existing ontologies, an Example: Work for the Epigraphic Ontology
- Working with APIs: IIIF and DTS
- [Frequently used models and ontologies for ancient documents](https://docs.google.com/presentation/d/e/2PACX-1vSCxwgxli69-oJqAnM7w6OOuhbPLrWgGV8Rax69WM-bshHVFJLWvmXiUDaJ07uGDsGj67zjc2qIuRzf/pub?start=false&amp;loop=false&amp;delayms=3000) and written artefacts

##### Exercise

In Day 1 we have modelled with Web Protégé a generic domain of Books. Now that you know where to look at, try and imagine how to model your own data, not all of it, just a piece which is more immediately interesting to you. Use a flexible and accessible tool: pen and paper.

**Instructions**

- What do you want to achieve?
- What should your model know? (competences questions)
- Which steps do you think you need to take?
- Let&#39;s start with a model for a specific feature.
- Model the ontology and add some test individuals to it using Web Protégé, but do not make up Classes and Properties unless you do not find anything in the known models!
- It is useful to think in terms of how the data would look like to begin with
- Which controlled vocabularies could you use?
- Which resources do you need to publish and maintain in your own domain?

#### Afternoon 14–16 Tools

- [Publishing tools, long term storage and services](https://docs.google.com/presentation/d/e/2PACX-1vSBVdqkTjS1rheienCkKM7wBY0eA1tOm1fwGR3bdvaWZ3ocQNjPsZcchPQRyw815KMcHluGA_In38bf/pub?start=false&amp;loop=false&amp;delayms=3000)(Xtriples, Zenodo, w3id.org)

##### Exercise

It would not be linked open data if we did not use it to reach out. We will try and put together what we have done and see if something can come out of it. Store your outputs in your favourite repository and share in [this document](https://docs.google.com/document/d/1Zrdtr2wWFlFRWe7UyW5vsH2KfIc3UBQoRdn8l3goauA/edit?usp=sharing) what you can and would like to share.

#### Evening Lecture 16:00 - Massimo Magnani (UNIPR) on _Digital Editions and their impact on methodology_

## Commented Readings List

Below you can find a chronologically ordered list of publications which I have read and I think can be useful for you. Because some are lengthy and one cannot read them all, I have added for each a short introductory paragraph with my comments in relation to the content of the training. These, I hope, will help you choose what is more relevant for you.

### 2009

#### Hitzler, Pascal, Markus Krotzsch, and Sebastian Rudolph. _Foundations of Semantic Web Technologies_. Boca Raton: Chapman and Hall/CRC, 2009.

This is really what it says. The foundation of Semantic Web Technologies. You will also find exercises and further readings for each chapter. Worth as reading and introduction, although any one of us is likely only to deal with one or the other of the chapters. But that is part of what the Semantic Web is about, extreme modularity. Be ready for more maths and logic than you are used to.

### 2013

#### Swartz, Aaron. &#39;Aaron Swartz&#39;s A Programmable Web: An Unfinished Work&#39;. _Synthesis Lectures on the Semantic Web: Theory and Technology_ 3, no. 2 (28 February 2013): 1–64.[https://doi.org/10.2200/S00481ED1V01Y201302WBE005](https://doi.org/10.2200/S00481ED1V01Y201302WBE005).

A provocative and really in progress set of notes, starting very critically against Semantic Web and ending up with a positive take to SPARQL endpoints... Aaron Swartz, one of the heroes of the Web as we know it, also gives an introduction to the overall architecture of the Web which is synthetic and colloquial. This short booklet is a quite useful overview to understand how the Web actually works. And start worrying about the enormous amount of overhead on any digital effort in terms of sustainability. Read this and some detailed report on data centers energy consumption, as well as some additional post-colonial minimal computing efforts and you will soon start wondering if it is not better to simply turn all off and write on paper only.

### 2014

#### Tupman, Charlotte, and Anna Jordanous. &#39;Sharing Ancient Wisdoms across the Semantic Web Using TEI and Ontologies&#39;. In _Analysis of Ancient and Medieval Texts and Manuscripts: Digital Approaches_, edited by T. Andrews and Caroline Macé, 213–28. Lectio: Studies in the Transmission of Texts &amp; Ideas 1. Turnhout: Brepols, 2014.

The SAWS ontology is one of the most interesting applications for research purposes of owl formalisms. It is a bit hard to find the code and its documentation, but this does not make of it a lesser achievement. I find [this page](https://ancientwisdoms.ac.uk/media/ontology/SAWS_relationship_types.html) to be a very useful complement to the presentation and the contents of some of the videos above. This is also, as far as I know, the origin of a very productive practice of using the \&lt;relation\&gt; element to include additional statements as triples in a TEI description.

### 2015

#### Felicetti, Achille, Francesca Murano, Paola Ronzino, and Franco Niccolucci. &#39;CIDOC CRM and Epigraphy: A Hermeneutic Challenge&#39;. In _Extending, Mapping and Focusing the CRM 2015. Proceedings Workshop EMF-CRM2015, Poznań, Poland, September 17, 2015_, edited by Paola Ronzino, 55–68, 2015.[https://www.academia.edu/19633265/CIDOC\_CRM\_and\_Epigraphy\_a\_Hermeneutic\_Challenge](https://www.academia.edu/19633265/CIDOC_CRM_and_Epigraphy_a_Hermeneutic_Challenge).

The modeling of Texts as linguistic objects in CRMtex is a good example of a fine effort which is as much useful as it is unused. Engineers may think of that as a non-positive result, I think it is a matter of time. Before this was in place it could not be used. Now that it is, we know where to look at to model some core features for written artefacts (not only epigraphy, I would claim).

#### Gippert, Jost. &#39;Digital Approaches to Oriental Manuscript Studies&#39;. In _Comparative Oriental Manuscript Studies: An Introduction_, edited by Alessandro Bausi, Pier Giorgio Borbone, Françoise Briquel-Chatonnet, Paola Buzi, Jost Gippert, Caroline Macé, Marilena Maniaci, et al., 12–26. Hamburg: COMSt, 2015.

The entire COMST manual is a must read for opening up the perspective from more abundant or more european manuscript traditions. This contribution by Gippert makes a point about the &quot;digital approaches&quot;.

#### Lincoln, Matthew. &#39;Using SPARQL to Access Linked Open Data&#39;. Edited by Fred Gibbs. _The Programming Historian_, no. 4 (24 November 2015).[https://doi.org/10.46430/phen0047](https://doi.org/10.46430/phen0047).

One interesting (and concerning) thing about this quite useful introduction is that it is retired. It does not work any more in some respect. I think it is an experience we are better start to get used to, that of writing about things which will decay in a timespan which is much shorter than anything we imagined. The article introduces to RDF using some of the resources we have also described. The fact that some do not work may prompt you to try on those resources which you are interested in.

### 2016

#### Oldman, Dominic, Martin Doerr, and Stefan Gradmann. &#39;Zen and the Art of Linked Data: New Strategies for a Semantic Web of Humanist Knowledge&#39;. In _A New Companion to Digital Humanities_, edited by Susan Schreibman, Ray Siemens, and John Unsworth, 251–73. Blackwell Companions to Literature and Culture 93. Malden, MA–Oxford–Carlton: Wiley-Blackwell, 2016.

Start from this, to have a solid introduction to why Linked Data is important. One statement is all it takes to make a difference! CIDOC is introduced here by its creators and a positive argument is made against a quite wide spread absurdity, that is that of opposing as alternative TEI encoding and LOD practices. These are done differently and for different purposes, they go hand in hand, they are not alternatives neither as views of the world or digital practices, etc.

#### Kuczera, Andreas, Thorsten Wübbena, and Thomas Kollatz. &#39;Die Modellierung des Zweifels – Schlüsselideen und -konzepte zur graphbasierten Modellierung von Unsicherheiten. Zur Einführung in diesen Band&#39;. _Zeitschrift für digitale Geisteswissenschaften_, 2016.[http://dx.doi.org/10.17175/sb004\_013](http://dx.doi.org/10.17175/sb004_013).

One of the easiest to encode, yet most concerning parts of the digital work for scholars in the humanities is that of representing various forms of doubt and uncertainty. How often do we feel that one or the other model wants us to state a fact which we are actually not ready to state? Even stating that with doubt may be not what we want to do. The volume collects several contributions which address from different angles this fundamental issue. I would like to suggest that inference is another area where this is exponentially problematic.

### 2017

#### Calvanese, Diego, Benjamin Cogrel, Sarah Komla-Ebri, Roman Kontchakov, Davide Lanti, Martín Rezk, Mariano Rodriguez-Muro, and Guohui Xiao. &#39;Ontop: Answering SPARQL Queries over Relational Databases&#39;. _Semantic Web_ 8 (11 February 2016).[https://doi.org/10.3233/SW-160217](https://doi.org/10.3233/SW-160217).

SPARQL and Semantic Web technologies can be used to map on the fly &quot;traditional&quot; SQL databases and aggregate them without having to do much more than a properly standardized mapping. Since we hope SQL databases which have been curated for decades will remain with us, this is indeed a valuable way to bring them into the game of the present and future, which is that of Semantic web. Ontop does this, and works very well.

#### Winesmith, Keir. &#39;Against Linked Open Data&#39;. Medium, 30 June 2017.[https://drkeir.medium.com/against-linked-open-data-502a53b62fb7](https://drkeir.medium.com/against-linked-open-data-502a53b62fb7).

It is very easy to find prophets of LOD, it is thus important to hear some other bell. This short reading makes in my opinion a very simple and clear point: purpose is at the heart of what we do, so let us do LOD and RDF if we are using it, not just to do it because it is good or because Sir Tim Berners-Lee said it is good for us to do so.

#### Blaney, Jonathan. &#39;Introduction to the Principles of Linked Open Data&#39;. _Programming Historian_, 7 May 2017.[https://programminghistorian.org/en/lessons/intro-to-linked-data](https://programminghistorian.org/en/lessons/intro-to-linked-data).

This theoretical introduction is an accessible reading to get started. Eventually, I hope you will not need it, but it may be useful as a refresher in a couple of years if you do not use for the moment any of this and then, e.g. get funding and need to get started again.

### 2018

#### Magnani, Massimo. &#39;The Other Side of the River Digital Editions of Ancient Greek Texts Involving Papyrus Witnesses&#39;. _Digital Papyrology II_. De Gruyter, 2018.[https://www.degruyter.com/document/doi/10.1515/9783110547450-005/html](https://www.degruyter.com/document/doi/10.1515/9783110547450-005/html).

The article discusses the impact of digital tools on digital editions and their use by philologists. Examples are taken from Euripides Scholia and Homer Multitext. The latter project is one that challenges all together the notion of critical edition opposing to it a new paradigm, that of a multitext edition. The author (and we have also heard directly from him in the evening presentation) discusses some defining aspects and challenges a rather positivistic rhetoric of the digital champions.

### 2019

#### Velios, Athanasios and Pickwoad, Nicholas (2019). &#39;Versioning Materiality: Documenting Evidence of Past Binding Structures&#39;. In: Bleier, Roman, Sean M. Winslow, Elisa Nury, Martina Scholger, Richard Breen, Christian Thomas, Athansios Velios, et al. _Versioning Cultural Objects: Digital Approaches_. Edited by Roman Bleier and Sean M. Winslow. Vol. 13. Norderstedt: BoD, 2019.[http://www.uni-koeln.de/](http://www.uni-koeln.de/).

Here the authors discuss the use of the CIDOC-CRM (in theory) to record information on changes of the binding through time. The examples are linked to the LoB Vocabulary, providing a good example of how to connect models and specific vocabularies. The use of graphs instead of readable CURI based makes the access to information a bit more challenging. The authors make an important point about prioritizing observation and recording to deduction and unpacking that information.

#### Daquino, Marilena, Francesca Giovannetti, and Francesca Tomasi. &#39;Linked Data per le edizioni scientifiche digitali. Il workflow di pubblicazione dell&#39;edizione semantica del quaderno di appunti di Paolo Bufalini&#39;. _Umanistica Digitale_, no. 7 (18 December 2019).[https://doi.org/10.6092/issn.2532-8816/9091](https://doi.org/10.6092/issn.2532-8816/9091).

This article offers an example of how to work with features of a digital edition, the modelling of which benefits from linked data structures and builds further compared to the document-centred models. It gives also an example of use of w3id.org for the stable identification and long term support of URIs, which however must be in conjunction with server side support for the resolution of these. Integration of the data model with SPAR ontologies is also presented with examples and further references. The citation structures using Web Annotation models may be integrated with DTS API presentations for example.

#### Cayless, Hugh A. &#39;Sustaining Linked Ancient World Data&#39;. In _Digital Classical PhilologyAncient Greek and Latin in the Digital Revolution_, Vol. 10. Berlin, Boston: De Gruyter Saur, 2019.[https://doi.org/10.1515/9783110599572-004](https://doi.org/10.1515/9783110599572-004).

If you work with Digital Classicists you will soon meet the work of Hugh Cayless. We have seen for example the LAWD ontology, which he put together. In this article he points out some uses of RDF and Linked Data for classicists and also gives some historical details on the development of resources like Pleiades, Papyri.info and opencontext, with a view at sustainability and complexity. I strongly suggest this reading also to understand some of the risks involved in this kind of work (over encoding, to name one).

#### Liuzzo, Pietro Maria. _Digital Approaches to Ethiopian and Eritrean Studies_. Supplement to Aethiopica 8, 2019. [https://doi.org/10.2307/j.ctvrnfr3q](https://doi.org/10.2307/j.ctvrnfr3q)

In my book, especially in Chapters 2, 4, and 7, you will find a number of SPARQL queries with explanation and several other examples of XQuery and XSLT in action. This is all applied to Ethiopian manuscripts but entirely applicable to any other context.

### 2020

#### Hendler, James, and D. Allemang. _Semantic Web for the Working Ontologist: Effective Modeling in RDFS and OWL._ 2nd ed. Morgan Kaufmann, 2011. (third edition 2020)[http://www.nhmnc.info/wp-content/uploads/fbpdfs2014/Semantic-Web-for-the-Working-Ontologist-Second-Edition-Effective-Modeling-in-RDFS-and-OWL-by-James-Hendler-Excellent-Source-Of-Semantic-Web-Information-.pdf](http://www.nhmnc.info/wp-content/uploads/fbpdfs2014/Semantic-Web-for-the-Working-Ontologist-Second-Edition-Effective-Modeling-in-RDFS-and-OWL-by-James-Hendler-Excellent-Source-Of-Semantic-Web-Information-.pdf).

I have learned more from this book (the third edition) than from any other scattered resource. Unfortunately examples are all out of scope, but still they are clear and understandable by anyone. If you plan to work with RDF and Semantic Web technologies, I would recommend this.

### 2021

#### &#39;Semantic Web - Volume 12, Issue 2 - Journals&#39;. _Semantic Web_ 12, no. 2. [https://content.iospress.com/journals/semantic-web/12/2](https://content.iospress.com/journals/semantic-web/12/2).

This is a special issue on Semantic Web for cultural heritage. Let alone the fact that hard sciences need to cluster all of us into something which is way too big to be of any relevance, the issue contains various interesting contributions. I would in particular point out the one on Gravsearch for implementers and the contributions about CRMtex, the execution technique modeling and the narrative ontology.

#### Bond, Sarah, Paul Dilley, and Ryan Horne, eds. _Linked Open Data for the Ancient Mediterranean: Structures, Practices, Prospects_. ISAW Papers 20, n.d.[http://hdl.handle.net/2333.1/gqnk9kz2](http://hdl.handle.net/2333.1/gqnk9kz2).

Also this volume, as the previous, is a collection of contributions on several aspects of Linked Data. Why the Mediterranean was picked for the title, I do not know. The resources and ontologies described reach far away from the &quot;lake&quot;. Look at the contribution about PeriodO, which has a global scope. [Sebastian Heath&#39;s contribution](http://dlib.nyu.edu/awdl/isaw/isaw-papers/20-13/#footnote-reference-12) will also walk you through using SPARQL and adding visualization straight into a &#39;live&#39; IPython Notebook.

#### The CIDOC CRM Special Interest Group. &#39;Volume A: Definition of the CIDOC Conceptual Reference Model&#39;, March 2021.[http://www.cidoc-crm.org/version/version-7.1](http://www.cidoc-crm.org/version/version-7.1).

The latest version of the CIDOC-CRM. The most important part is the one which lists changes from previous versions. Some rather important ones are in place now. No standard is ever closed or finished, no resource is, but this is a reference work which should be always on your desk(top), when doing linked data. For those who think this is more complex than TEI, print the TEI Guidelines, which should also be kept on the desktop, and let me know what goes better in terms of reading. Both these resources are a basic reading for anyone doing digital work.

#### &#39;Modeling Epigraphy with an Ontology&#39;. Zenodo, 26 March 2021.[https://doi.org/10.5281/zenodo.4639508](https://doi.org/10.5281/zenodo.4639508).

The Epigraphy.info Ontology Working group produced this document as a collaborative effort over the last few years. No one uses it yet. It attempts at going through the various types of information needed for epigraphy in the same way this was done in Nomisma for coins. It additionally uses a list of previously existing vocabularies specific to amphoric epigraphy for example, and an implementation of the CRMtex which did not exist before.



## Learning outcomes

At the end of the training, participants will have received initial training to be able to

− Understand RDF structured data, query RDF with SPARQL, and visualize data returned from a SPARQL Query

− Know the main standards (IIIF, CIDOC CRM, DTS) and guidelines used in the field of interest and know where to retrieve further documentation

− Know basic tools available to produce RDF and OWL data (Protégé, Atom)

− Transform data to RDF (Xtriples) and store it (Fuseki)

− Use with ease some simple reference materials (Wikibase) and annotation tools (Hypothes.is, Zenodo)

− Apply simple models to their data to produce RDF and use it to answer simple questions

− Analyse inquisitively the results of the process

− Understand the scientific processes and workflows involved with the modeling and querying of RDF data

− Understand and apply to their own needs the best practices of Linked Open Data.


Linked Open Data for Written Artefacts Program © 2021 by [Pietro Liuzzo](https://orcid.org/0000-0001-5714-4011)is licensed under [Attribution-NonCommercial 4.0 International](http://creativecommons.org/licenses/by-nc/4.0/?ref=chooser-v1)

Part of the Project [Bridging the \&lt;gap\&gt; in Ancient Writing Cultures: ENhance COmpetences in the Digital Era](https://site.unibo.it/encode/it)

![](RackMultipart20210528-4-16n7qud_html_d4dc1ab4a76490c3.png)
