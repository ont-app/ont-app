
# Ont-app

This repo contains several projects providing tools for interacting with graph-shaped data in Clojure.

Here are the primary projects:

| Project | Notes |
| --- | --- |
| [ont-app/igraph](https://github.com/ont-app/igraph) <img width=100 comment="dummy for spacing"> | Defines a set of protocols for dealing with graph data as a primitive Clojure container alongside lists, vectors, sets, and maps |
| [ont-app/vocabulary](https://github.com/ont-app/vocabulary) | Tools to provide a mapping between Clojure keywords and RDF-type URIs and language-tagged literals. |
| [ont-app/sparql-endoint](https://github.com/ont-app/sparql-endpoint) | Tooling to interact in Clojure with a SPARQL endpoint |
| [ont-app/sparql-client](https://github.com/ont-app/sparql-client) | Porting the IGraph protocols to a SPARQL endpoint |
| [ont-app/igraph-jena](https://github.com/ont-app/igraph-jena) | Porting the IGraph protocols to [Jena](https://jena.apache.org/) |
| [ont-app/datascript-graph](https://github.com/ont-app/datascript-graph) | Porting the IGraph protocols to [tonsky/datascript](https://github.com/tonsky/datascript) |
| [ont-app/grafter](https://github.com/ont-app/grafter) | Porting the IGraph protocols to [Swirrl/grafter](https://github.com/Swirrl/grafter) |
| [ont-app/datomic-client](https://github.com/ont-app/datomic-client) | Porting the IGraph protocols to the [datomic client](https://docs.datomic.com/cloud/client/client-api.html) |
| [ont-app/graph-log](https://github.com/ont-app/graph-log) | Tools to log execution events to an IGraph implementation in addition to standard string-based logging |
| [ont-app/cedict](https://github.com/ont-app/cedict) | An RDF translation of the Chinese-English dictionary [CEDICT](https://www.mdbg.net/chinese/dictionary?page=cedict)|
| [ont-app/igraph-vocabulary](https://github.com/ont-app/igraph-vocabulary) | A layer of logic in Clojure to support libraries that use both `IGraph` and `vocabulary`|
| [ont-app/rdf](https://github.com/ont-app/igraph-vocabulary) | A layer of logic in Clojure to support libraries that use both `IGraph` and RDF|
