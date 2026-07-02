---
permalink: teaching.html
title: "Teaching"
author_profile: true
---

## 👩‍🎓👨‍🎓 Students (current)
* **[2025- ]** Thesis co-director of [Carmelle Meli Sunguon](https://www.eurecom.fr/fr/people/meli-songuon-carmelle) for her PhD co-supervised with [Raphaël Troncy](https://www.eurecom.fr/~troncy/) ([EURECOM](http://www.eurecom.fr)), "Integration and Traceability of Knowledge in a GraphRAG-based Question-Answering System"
* **[2024- ]** Apprenticeship supervisor of Léna Abel at [UTBM](https://www.utbm.fr/), "Développement d’outils de construction de graphes de connaissances d’entreprise". Co-supervision with Frédéric Deuzé.
* **[2023- ]** Member of the supervisory committee of [Duo Yang](https://www.kuleuven.be/wieiswie/en/person/00162181) for his PhD on Automated Knowledge Graph construction at KU Leuven
* **[2024- ]** Member of the supervisory committee of [Jean Meunier-Pion](https://www.jmpion.com/) for his PhD on Failure-awareness learning for the design of resilient infrastructures using natural language processing at Université Paris-Saclay

## 👩‍🎓👨‍🎓 Students (past)
* **[2023-2026]** Thesis co-director of [Lucas Jarnac](https://scholar.google.com/citations?user=O24FhxkAAAAJ&hl=fr) for his PhD co-supervised with [Miguel Couceiro](https://members.loria.fr/mcouceiro/) ([LORIA](https://www.loria.fr/en/)), "Reconciling uncertain knowledge to improve knowledge graphs"
  Here are the four main contributions of his PhD in few words + links:
  * A first key contribution is an extensive survey of KG construction under uncertainty, published in TGDK. It covers open and enterprise KG construction, knowledge extraction methods, and downstream tasks (completion, alignment, fusion), and proposes a knowledge integration pipeline under uncertainty with metrics to assess the quality of the resulting KG. [Paper](https://drops.dagstuhl.de/entities/document/10.4230/TGDK.3.1.3)
  * KG construction can be seen as an iterative process starting from a high-quality nucleus, refined by knowledge extraction in a virtuous loop. Such a nucleus can come from an open KG like Wikidata, but integrating it as a whole raises relevance and scalability issues; the proposed approach starts from seed entities of interest and decides which neighboring entities to keep or prune. [Paper](https://dl.acm.org/doi/10.1145/3583780.3615030), [Code](https://github.com/Orange-OpenSource/analogical-pruning)
   * WikiConflict, a benchmark for data fusion under real-world complexity. Building KGs at scale means pulling data from multiple sources with varying quality, conflicting values, and differences in granularity — a reality most existing fusion benchmarks fail to capture. Built from Wikidata's revision history, WikiConflict challenges fusion models on three concrete, underrepresented problems: differences in specificity between sources, heterogeneity of data types, and long-tail entities. [Paper](https://dl.acm.org/doi/pdf/10.1145/3731443.3771371), [Code](https://github.com/Orange-OpenSource/trustfuse)
   * A final contribution is Telegraph, an approach to validate triples from multiple sources. It relies on a GNN that captures both the context provided by the KG and the context of the subgraphs formed by the triples to be validated. Prediction scores are calibrated into confidence scores, enabling an integration strategy driven by confidence. (Publication forthcoming)
* **[2024]** Co-supervision (main supervisor: [Lucas Jarnac](https://scholar.google.com/citations?user=O24FhxkAAAAJ&hl=fr)) of Carmelle Meli Songuon for his final year internship at [INP-ENSIMAG](https://ensimag.grenoble-inp.fr/), "Développement d'outils d'extraction textuels pour l'enrichssement de graphes de connaissances"
* **[2020-2024]** Thesis co-director of [Lionel Tailhardat](https://genears.github.io/) for his PhD co-supervised with [Raphaël Troncy](https://www.eurecom.fr/~troncy/) ([EURECOM](http://www.eurecom.fr)), "Synergy between knowledge graphs and machine learning for the detection of anomalies"
  Here are the four main contributions of his PhD in few words + links:
   * A first key contribution is the NORIA-O ontology to model an ICT infrastructure, network topology, logs, events and alarms raised by equipment and operators, procedures to remedy to anomalies. [Paper](https://link.springer.com/chapter/10.1007/978-3-031-60635-9_2), [Code](https://github.com/Orange-OpenSource/noria-ontology)
   * A complete pipeline comes with NORIA-O to automatically build a knowledge graph out of dozens of data sources (static and dynamic). ETL is massively used, with declarative mappings developed in RML. Several open source contributions have been made to community software projects (see [here](https://yoanchabot.github.io/code.html) for more info)
   * Various synergistic reasoning approaches to detect anomalies. For example, SPARQL queries corresponding to rule patterns leading to anomalies can be tested. Another kind of reasoning performs Process Mining and is implemented using Petri Net. Finally, statistical learning can of course be used. Hence, RDF2Vec embeddings can be computed to feed a classifier that will predict the category of an incident based on the full context. [Paper](https://dl.acm.org/doi/10.1145/3600160.3604991)
   * A final contribution is a fully fledged User Interface enabling to browse the knowledge graph as well as execute AI algorithms to detect anomalies and run the various synergistic reasoning methods. [Paper](https://raw.githubusercontent.com/yoanchabot/papers/main/grasec_2024.pdf)
* **[2024-Discontinued]** Thesis co-director of [Camille Barboule](https://camillebrl.github.io/) for his PhD co-supervised with [Benjamin Piwowarski](https://www.piwowarski.fr/) ([ISIR](https://www.isir.upmc.fr/)), "Information Extraction in Long Multimodal Documents". 
* **[2024]** Supervision of Boumediene Sari for his final year internship at [University of Montpellier](https://www.umontpellier.fr/), "Développement de robots pour l'enrichissement de graphe de connaissances d'entreprise"
* **[2023]** Co-supervision (main supervisor: [Lionel Tailhardat](https://genears.github.io/)) of [Benjamin Stach](https://benjaminstach.com/) for his final year internship at [UTBM University of Technology](https://www.utbm.fr/), "Development of a solution for collecting and annotating activity traces for an illicit activity detection platform using knowledge engineering and machine learning techniques"
* **[2023]** Co-supervision (main supervisor: Antoine Py) of Yassine Trabelsi for his final year internship at [Esprit School of engineering](https://esprit.tn/), "Développement d'outils web de visualisation et d'interrogation de graphes de connaissances"
* **[2020-2023]** Thesis co-director of [Jixiong Liu](https://www.yansera.com/) for his PhD co-supervised with [Raphaël Troncy](https://www.eurecom.fr/~troncy/) ([EURECOM](http://www.eurecom.fr)), "Production and valorization of semantic annotation on structured datasets through a recommendation process based on graph embedding techniques"
   Here are the three main contributions of his PhD in few words + links:
   * [This journal](https://www.sciencedirect.com/science/article/abs/pii/S1570826822000452) providing a fine grained classification of table types that one can harvest in the wild, on the Web and tools to pre-process them
   * A system for automatically interpreting tables based on a target knowledge graph. DAGOBAH has won the last 2 editions of the SemTab challenge. [API avalaible here](https://developer.orange.com/apis/table-annotation/overview)
   * A plugin system that leverages knowledge graph embeddings for improving the disambiguation step. [Open source](https://github.com/Orange-OpenSource/radar-station)
* **[2020]** Supervision of Antoine Py for his final year internship at [University De Franche-Comté](http://www.univ-fcomte.fr/), "Development of a Web application for annotation and semantic integration of tabular data"
* **[2019]** Supervision of [Jixiong Liu](https://www.yansera.com/) for his final year internship at [ESIGELEC Rouen](http://www.esigelec.fr/), "Implementation of a prototype for annotating tabular data using semantic models"
* **[2018]** Supervision of Nicolas Geist for his final year internship at [INSA Lyon](https://www.insa-lyon.fr/), "Development of a platform for detecting illegal activities using knowledge engineering and machine learning"

## 👨‍🏫 Courses
* **[2014-2015]**
  * Demonstrator at [University of Burgundy](http://www.ubfc.fr/): Data structures and Algorithmics
* **[2013-2014]**
  * In charge of a Javascript course at [University of Burgundy](http://www.ubfc.fr/)
  * Demonstrator at [University of Burgundy](http://www.ubfc.fr/): Man-Machine Interface
  * Tutor at the Computer Science Support Center at [University College Dublin](https://www.ucd.ie/)
* **[2012-2013]**
  * Demonstrator at [University College Dublin](https://www.ucd.ie/): C programming and PHP
