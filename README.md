# DataBench Ontology and Knowledge Graph Monitoring

The DataBench Aggregated Graph is a knowledge graph built upon several aggregated resources applicable for DataBench project and described above as data sources.


## DataBench Ontology

In order to develop the DataBench Aggregated Graph we have composed an ontology based on Artificial Intelligence, Big Data, Benchmarking related topics from Microsoft Academic Graph and extended/populated the ontology with tools and technologies from the relevant areas.

Microsoft Academic Graph (MAG) taxonomy has been expanded with DataBench terms – over 1,700 tools and technologies related to Benchmarking, Big Data, Artificial Intelligence.

New concepts have been aligned with MAG topic, MAG keyword, Wikipedia (for analysis in wikification) and Event Registry concepts.

The DataBench ontology is used in the semantic annotation process of the unstructured textual information from the available data sources. Wikification or semantic annotation with Wikipedia concepts is an intermedia step in the process of annotation with DataBench ontology.

In wikification a global disambiguation method based on constructing a mention-concept graph and computing PageRank over it is used to identify a coherent set of relevant concepts for the document. Since several of our data sources are multi-lingual, wikification is a suitable approach that supports any language for which a sufficiently large Wikipedia is available.

The task of wikifying an input document can be broken down into several closely interrelated subtasks:

1.  identify phrases (or words) in the input document that refer to a Wikipedia concept;
2.  determine which concept exactly a phrase refers to;
3.  determine which concepts are relevant enough to the document as a whole that they should be included in the output of the system (i.e. presented to the user).

As a result of wikification, each item from the dataset (with available textual information) obtains a set of possible annotations from Wikipedia. Since DataBench ontology is aligned with Wikipedia and Event Registry concepts, following the wikification process, we automatically obtain a semantically annotated documents with DataBench ontology.

Similar approach applies to the news dataset (from Event Registry), pre-annotated with Event Registry concepts. Since DataBench ontology is aligned with ER concepts, we automatically obtain news annotations with DataBench ontology.

## DataBench Aggregated Graph

The modelled ontology contributes to the development of the DataBench Aggregated Graph that aligns the knowledge obtained from different available data sources.  
In particular, the entities of the graph represent tools, topics, Github repositories, news articles, job postings, EU research projects, Categories et al.

DataBench Ontology Formalization presents an overview of the Aggregated Graph development. In our work on the aggregated graph we have focused on representing topics and tools (from the DataBench Observatory), providing the appropriate information about topic/tools and technology popularity.

The DataBench ontology and Aggregated Graph are published in Github on the following link: [https://github.com/besher-massri/DataBenchKnowledgeGraph](https://github.com/besher-massri/DataBenchKnowledgeGraph)  

Below is a visual representation of the DataBench ontology:

![Knowledge graph ontology](https://raw.githubusercontent.com/besher-massri/DataBenchKnowledgeGraph/main/databench_ontology.svg)</section>
