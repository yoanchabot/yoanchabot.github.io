---
permalink: code.html
title: "Open-source Code"
author_profile: true
---

## Table Annotation (DAGOBAH)

[GitHub](https://github.com/Orange-OpenSource/Table-Annotation)🔗

TableAnnotation is a semantic annotation tool for tables leveraging three steps: 
1) Table Preprocessing: a set of comprehensive heuristic to clean the table (e.g. fix encoding error), determine table orientation, data types of columns.
2) Entity Lookup: retrieve a number of entity candidates for mentions in the table, using an elastic search-based entity lookup.
3) Annotation: disambiguate retrieved entity candidates, select the most relevant entity for each mention. This consists of three tasks, namely Cell-Entity Annotation, Column-Type Annotation, Column-Pair Annotation.

## Radar Station

[GitHub](https://github.com/Orange-OpenSource/radar-station)🔗

Radar Station is cell-entity disambiguation tool for the domain semantic table interpretation (STI). It leverages graph embeddings to optimize the result of a given previous cell-entity annotation system.

## NORIA-O 

[GitHub](https://github.com/Orange-OpenSource/noria-ontology)🔗

The NORIA-O project is a data model for IT networks, events and operations information. The ontology is developed using web technologies (e.g. RDF, OWL, SKOS) and is intended as a structure for realizing an IT Service Management (ITSM) Knowledge Graph (KG) for Anomaly Detection (AD) and Risk Management applications. The model has been developed in collaboration with operational teams, and in connection with third parties linked vocabularies.

## SMASSIF-RML

[GitHub](https://github.com/Orange-OpenSource/SMASSIF-RML)🔗

A Semantic Web stream processing solution with declarative data mapping capability based on a modified version of the RMLMapper-java tool and extensions to the StreamingMASSIF framework.

## ssb-consum-up

[GitHub](https://github.com/Orange-OpenSource/ssb-consum-up)🔗

A Semantic Service Bus (SSB) consumer to SPARQL Update.
The ssb-consum-up (scu thereafter) solution consumes Kafka messages from some topic where the <k,v> message structure contains RDF data in JSON-LD syntax.
* v (value): graph data payload, whether part or not of a named graph (i.e. derived from N-Quads or Trig data vs derived from triples )
* k (key): optional metadata for complementary downstream SPARQL Update behavior configuration, such as providing the SPARQL Update action to use, a payload provenance, etc.
Processed semantic messages trigger SPARQL Update queries to some downstream SPARQL end point, thus enabling tasks such as inserting streams of RDF data.

## Graphameleon Web extension

[GitHub](https://github.com/Orange-OpenSource/graphameleon)🔗

Graphameleon is a Web Browser Extension which collects and semantizes Web navigation traces.
Following research on the NORIA-O and DynaGraph projects, the Graphameleon Web extension brings visualization and recording of Web navigation traces at the browser level. Then, leveraging knowledge graph representations, to perform User and Entity Behavior Analytics (UEBA) and Anomaly Detection (AD).
The extension incorporates an internal semantical mapping module that relies on the RMLmapper library to construct a RDF knowledge graph during navigation. Additionally, it utilizes the React-Force-Graph visualization library, allowing users to view their navigation traces in a 3D representation of the knowledge graph.
