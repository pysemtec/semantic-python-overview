# Semantic Python Overview

This repository aims to collect and curate a list of projects which are related both to python and semantic technologies (RDF, OWL, SPARQL, Reasoning, ...). It is inspired by collections like [awesome lists](https://github.com/sindresorhus/awesome#readme). The list might be incomplete and biased, due to the limited knowledge of its authors. Improvements are very welcome. Feel free to file an issue or a pull request. Every section is alphabetically sorted.

Furthermore, this repository might serve as a **cristallization point for a community** interested in such projects – and how they might productively interact. See [this discussion](https://github.com/cknoll/semantic-python-overview/discussions/1) for more information.


## Established Projects

- [brickschema](https://github.com/BrickSchema/py-brickschema) – Brick Ontology Python package
    - Brick is an open-source effort to standardize semantic descriptions of the physical, logical and virtual assets in buildings and the relationships between them.
    - docs: https://brickschema.readthedocs.io/en/latest/
    - website: https://brickschema.org/
    - features:
        - basic inference with different reasoners
        - web based interaction (by means of [Yasgui](https://github.com/TriplyDB/Yasgui))
        - Translations from different formats (Haystack, VBIS)
- [Cooking with Python and KBpedia](https://www.mkbergman.com/cooking-with-python-and-kbpedia/)
    - Tutorial series on "how to pick tools and then use Python for using and manipulating the KBpedia knowledge graph"
    - [Material in form of Jupyter Notebooks](https://github.com/Cognonto/CWPK),
    - accompanying python package [cowpoke](https://github.com/Cognonto/cowpoke),
- [Eddy](https://github.com/obdasystems/eddy) - graphical ontology editor
  - website: https://www.obdasystems.com/eddy
  - features:
    - graphical ontology editing
    - uses bespoke Graphol format but has an OWL2 export
    - visualization built on PyQt5
  - literature references:
    - [*Lembo, D and Pantaleone, D and Santarelli, V and Savo, DF: **Eddy: A Graphical Editor for OWL 2 Ontologies**. IJCAI 2016; 4252-4253*](https://cs.unibg.it/savo/papers/LPSS-IJCAI-16.pdf)
- [fastobo-py](https://github.com/fastobo/fastobo-py): Python bindings for *fastobo* (rust library to parse OBO 1.4)
    - features:
        - load, edit and serialize ontologies in the OBO 1.4 format
- [FunOwl](https://github.com/hsolbrig/funowl) – functional OWL syntax for Python
  - features:
    - provide a pythonic API that follows the OWL functional model for constructing OWL
- [gizmos](https://github.com/ontodev/gizmos) – Utilities for ontology development
    - features:
        - modules for "export", "extract", "tree"-rendering
- [Jabberwocky](https://github.com/sap218/jabberwocky) – a toolkit for ontologies
    - features:
        - associated text mining using an ontology terms & synonyms
        - tf-idf for synonym curation then adding those synonyms into an ontology
- [Macleod](https://github.com/thahmann/macleod) – Ontology development environment for Common Logic (CL)
    - features:
        - Translating a CLIF file to formats supported by FOL reasoners
        - Extracting an OWL approximation of a CLIF ontology
        - Verifying (non-trivial) logical consistency of a CLIF ontology
        - Proving theorems/lemmas, such as properties of concepts and relations or competency questions
        - GUI (alpha state)
- [Morph-KGC](https://github.com/oeg-upm/morph-kgc) – Engine to create RDF knowledge graphs from heterogeneous sources with R2RML and RML
  - docs: https://github.com/oeg-upm/Morph-KGC/wiki
  - features:
    - support for relational databases, tabular files (e.g. CSV, Excel, Parquet) and hierarchical files (XML and JSON)
    - generates the RDF by running the engine through command line
    - can be used as a library to load the RDF knowledge graph to RDFlib
- [OntoPilot](https://github.com/stuckyb/ontopilot) – software for ontology development and deployment
  - docs: https://github.com/stuckyb/ontopilot/wiki
  - features:
    - support end users in ontology development, documentation and maintainance
    - convert spreadsheet data (one entity per row) to owl files
    - call a reasoner before triple-store insertion
- [ontospy](https://github.com/lambdamusic/Ontospy) – Python library and command-line interface for inspecting and visualizing RDF models
  - docs: http://lambdamusic.github.io/Ontospy/
  - features:
    - extract and print out any ontology-related information
    - convert different OWL syntax variants
    - generate html documentation for an ontology
- [ontor](https://github.com/felixocker/ontor) – Python library for manipulating and vizualizing OWL ontologies in Python
  - features:
    - tool set based on owlready2 and networkx
- [owlready2](https://bitbucket.org/jibalamy/owlready2/src/master/README.rst) – ontology oriented programming in Python
  - docs: https://owlready2.readthedocs.io/en/latest/index.html
  - features:
    - parse owl files (RDF/XML or OWL/XML)
    - parse SWRL rules
    - call reasoner (via java)
  - literature references:
    - [*Lamy, JB: Owlready: **Ontology-oriented programming in Python with automatic classification and high level constructs for biomedical ontologies**. Artificial Intelligence In Medicine 2017;80:11-28*](http://www.lesfleursdunormal.fr/_downloads/article_owlready_aim_2017.pdf)
    - [*Lamy, JB: **Ontologies with Python**, Apress, 2020*](https://www.apress.com/fr/book/9781484265512)
        - accompanying material: <https://github.com/Apress/ontologies-w-python>
- [Oxrdflib](https://github.com/oxigraph/oxrdflib) – Oxrdflib provides rdflib stores using pyoxigraph (rust-based)
    - could be used as drop-in replacements of the rdflib default ones
- [pronto](https://github.com/althonos/pronto): library to parse, browse, create, and export ontologies
    - features:
        -supports several ontology languages and formats
    - docs: https://pronto.readthedocs.io/en/latest/api.html
- [PyFuseki](https://github.com/yubinCloud/pyfuseki) – Library that interact with Jena Fuseki (SPARQL server):
    - docs: https://yubincloud.github.io/pyfuseki/
- [Pyoxigraph](https://oxigraph.org/pyoxigraph/stable/index.html) – Python graph database library implementing the SPARQL standard.
    - built on top of [Oxigraph](https://github.com/oxigraph/oxigraph) using [PyO3](https://pyo3.rs/)
    - docs: https://oxigraph.org/pyoxigraph/stable/index.html
    - two stores with SPARQL 1.1 capabilities. in-memory/disk based
- [PyRes](https://github.com/eprover/PyRes)
    - resolution-based theorem provers for first-order logic
    - focus on good comprehensibility of the code
    - Literature: [Teaching Automated Theorem Proving by Example](https://link.springer.com/chapter/10.1007/978-3-030-51054-1_9)
- [Quit Store](https://github.com/AKSW/QuitStore) – workspace for distributed collaborative Linked Data knowledge engineering ("Quads in Git")
    - features:
        - read and write RDF Datasets
        - create multiple branches of the Dataset
    - literature references:
        - [*Decentralized Collaborative Knowledge Management using Git*](https://natanael.arndt.xyz/bib/arndt-n-2018--jws)
by Natanael Arndt, Patrick Naumann, Norman Radtke, Michael Martin, and Edgard Marx in Journal of Web Semantics, 2018
[[@sciencedirect](https://www.sciencedirect.com/science/article/pii/S1570826818300416)] [[@arXiv](https://arxiv.org/abs/1805.03721)]


- [RaiseWikibase](https://github.com/UB-Mannheim/RaiseWikibase) – A tool for speeding up multilingual knowledge graph construction with Wikibase
    - fast inserts into a Wikibase instance: creates up to a million entities and wikitexts per hour
    - docs: https://ub-mannheim.github.io/RaiseWikibase/
    - ships with `docker-compose.yml` for Wikibase (Database, PHP-code)
    - publication: https://link.springer.com/chapter/10.1007%2F978-3-030-80418-3_11
- [Reasonable](https://github.com/gtfierro/reasonable) – An OWL 2 RL reasoner with reasonable performance
    - written in Rust with Python-Bindings (via [pyo3](https://pyo3.rs/))
- [rdflib](https://github.com/RDFLib/rdflib) – Python package for working with RDF
  - docs: https://rdflib.readthedocs.io/
  - graphical package overview: https://rdflib.dev/
  - features:
    - parsers and serializers for RDF/XML, NTriples, Turtle and more
    - a graph interface which can be backed by any one of a number of store implementations
    - store implementations for in-memory storage and persistent storage
    - a SPARQL 1.1 implementation – supporting SPARQL 1.1 Queries and Update statements

- [SPARQL kernel](https://github.com/paulovn/sparql-kernel) for Jupyter
    - features:
        - sending queries to an SPARQL endpoint
        - fetching and presenting the results in a notebook
- [WikidataIntegrator](https://github.com/SuLab/WikidataIntegrator) – Library for reading and writing to Wikidata/Wikibase
    - features:
        - high integration with the Wikidata SPARQL endpoint


## Probably Stalled or Outdated Projects

- [Athene](https://github.com/dityas/Athene) DL reasoner in pure python
    - "[C]urrent version is a beta and only supports ALC. But it can easily be extended by adding tableau rules."
    - Last update: 2017
- [cwm](https://en.wikipedia.org/wiki/Cwm_(software))
    - Self description: "\[cwm is a\] forward chaining semantic reasoner that can be used for querying, checking, transforming and filtering information".
    - Created in 2000 by Tim Berners-Lee and Dan Connolly, see [w3.org](https://www.w3.org/2000/10/swap/doc/cwm)
- [air-reasoner](https://github.com/mit-dig/air-reasoner)
    - Self description: "Reasoner for the AIR policy language, based on cwm"
    - based on cwm
    - Last update: 2013
- [FuXi](https://pypi.org/project/FuXi/)
    - Self description: "An OWL / N3-based in-memory, logic reasoning system for RDF"
    - based on cwm
    - Last update: 2013
    - see also <http://code.google.com/p/python-dlp/wiki/FuXi> <http://code.google.com/p/fuxi/source/browse/> (hg-repo)
- [pysumo](https://github.com/pySUMO/pysumo)
    - Ontology IDE for the Sugested Upper Merged Ontology (SUMO)
    - Docs: https://pysumo.readthedocs.io/
    - Last update: 2015


## Further Projects / Links

- [github-semantic-web-python](https://github.com/topics/semantic-web?l=python) – github project search with `topic=semantic-web` and `language=python`
- [Pywikibot](https://github.com/wikimedia/pywikibot)
    - Library to interact with Wikidata and Wikimedia API
    - see also: https://www.wikidata.org/wiki/Wikidata:Creating_a_bot#Pywikibot
- [semantic](https://github.com/crm416/semantic) – Python library for extracting semantic information from text, such as dates and numbers
- [Solving Einstein Puzzle](https://github.com/cknoll/demo-material/blob/main/expertise_system/einstein-zebra-puzzle-owlready-solution1.ipynb) – jupyter notebook demonstrating how to use owlready2 to solve a logic puzzle
- [W3C-Link-List1](https://www.w3.org/2001/sw/wiki/SemanticWebTools#Python_Developers) – link list "SemanticWebTools", section "Python_Developers" (wiki page)
  - might be outdated
- [W3C-Link-List2](https://www.w3.org/2001/sw/wiki/Python) – list of tools usable from, or with, Python (wiki page)
- [wikidata-mayors](https://github.com/njanakiev/wikidata-mayors)
    - Python code to ask wikidata for european mayors and where they where born
    - Article: https://towardsdatascience.com/where-do-mayors-come-from-querying-wikidata-with-python-and-sparql-91f3c0af22e2
- [yamlpyowl](https://github.com/cknoll/yamlpyowl) – read an yaml-specified ontology into python by means of owlready2 (experimental)
- [Notebook, which generates quiz questions from wikidata](https://gist.github.com/ak314/fc6c6f911cb4f39453b575854cdc4869)
    - [related presentation slides](https://www.slideshare.net/robertoturrin/how-to-turn-wikipedia-into-a-quiz-game)
