---
title: "VT-KGNN: A Valid Time Knowledge Graph Neural Network"
date: 2022-03-18
publishDate:  2022-03-18
authors: ["**Andreas Auer**"]
publication_types: ["2"]
abstract: "Temporal Knowledge Graphs, a form of a graph-structured knowledge bases, gained increased interest in both academia and industry in the last years. Most Knowledge Graphs suffer from incompleteness, ie from facts which are valid in the real world that are not represented in the Knowledge Graph at hand. A set of methods to counter this problem are Knowledge Graph Embeddings, which learn vector embeddings for the knowledge graph elements in a way that the underlying structure of the Knowledge Graph is preserved and utilize the learned embeddings to predict missing facts. Knowledge Graph Embeddings show good results but allow only transductive link prediction. In addition their integration of prior information of the entities as well as of temporal information is insufficient and they suffer from scalability problems for large graphs.
In this thesis we propose the temporal knowledge graph neural network VT-KGNN. The model overcomes the limitations of Knowledge Graph Embeddings by using a multirelational adaption of local message passing graph neural networks as encoder and a Knowledge Graph Embedding score function as decoder. VT-KGNN especially focuses on the integration of temporal facts, more concretely on facts annotated with a valid time. It does not rely on snapshots but utilizes the temporal information by directly encoding it as a feature used in the Graph Neural Network. The model considers the start and end time of a fact individually, as well as in combination in the form of its duration. In addition it can utilize temporal relationships between facts that share entities"
featured: true
publication: "Master Thesis, Technical University Vienna"
links:
  - icon_pack: fas
    icon: download
    name: Download
    url: 'https://repositum.tuwien.at/handle/20.500.12708/19898'
  - icon_pack: fas
    icon: award
    name: Award
    url: 'https://informatics.tuwien.ac.at/news/2358'
---