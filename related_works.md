
# Related Works


## Mis-annotations in the public databases
* TODO: what is the latest update on this?

##### [Strategies to improve usability and preserve accuracy in biological sequence databases](https://onlinelibrary.wiley.com/doi/full/10.1002/pmic.201600034)
* "we propose five strategies to address fundamental issues in the annotation of sequence databases: (i) to clearly separate experimentally verified and unverified sequence entries; (ii) to enable a system for tracing the origins of annotations; (iii) to separate entries with high‐quality, informative annotation from less useful ones; (iv) to integrate automated quality‐control software whenever such tools exist; and (v) to facilitate postsubmission editing of annotations and metadata associated with sequences. "
* <span style="color:red"> TODO: [citations](https://scholar.google.com/scholar?biw=1920&bih=1089&um=1&ie=UTF-8&lr&cites=11661652185920513381) </span>

##### ISU PHD thesis' 13 on misannotations
* [Discovering meaning from biological sequences: focus on predicting misannotated proteins, binding patterns, and G4-quadruplex secondary](https://lib.dr.iastate.edu/cgi/viewcontent.cgi?article=4540&context=etd)

* [Exploring inconsistencies in genome-wide protein function annotations: a machine learning approach](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-8-284)
*


##### [Biological Databases and Protein Sequence Analysis](https://www.mrc-lmb.cam.ac.uk/genomes/madanm/pdfs/biodbseq.pdf)
* "The problem in the reliability of the data is the possibility of misannotations. The
misannotations are some time introduced due to the process of automation of annotation process which are carried out extensively with the help of computers. Misannotations, if introduced, multiplies in subsequent additions and may accumulate to an unbelievable extent and create confusion. A possible solution to prevent this from happening is to flag the protein sequence which has been annotated by sequence comparison but whose function has not been validated by experimental methods. "

##### [Automated Detection of Records in Biological Sequence Databases that are Inconsistent with the Literature](https://www.biorxiv.org/content/10.1101/101246v3.full)
* Then, we use these quality indicators to train an anomaly detection algorithm to classify records as “confident” or “suspicious”.


##### [Annotation Error in Public Databases: Misannotation of Molecular Function in Enzyme Superfamilies](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1000605)

## Data cleaning\curation

##### [Ontology-Based Data Cleaning]()
* Broadly speaking, a data cleaning process is composed of a detection step in which the existing conflicts are identified, and a resolution step in which the inconsistencies are solved.
* Data Cleaning: Problems and Existing Solutions: conflicts in data model, etc
* difference btw equality vs similarity

##### [KATARA: A Data Cleaning System Powered by Knowledge Bases and Crowdsourcing](https://dl.acm.org/citation.cfm?id=2749431)
* Dataset:
* implementation link?
* contributions:
 - "Table pattern definition and discovery."
* experiments?:


##### [On expert curation and scalability: UniProtKB/Swiss-Prot as a case study ](https://academic.oup.com/bioinformatics/article/33/21/3454/3964379)
* With the assistance of the PubTator text-mining tool, we tagged more than 10 000 articles to assess the ratio of papers relevant for curation.

##### [Metaxa2 Database Builder: enabling taxonomic identification from metagenomic or metabarcoding data using any genetic marker ](https://academic.oup.com/bioinformatics/article/34/23/4027/5038464)
* "correct taxonomic identification of DNA sequences is central to studies of biodiversity using both shotgun metagenomic and metabarcoding approaches. "


##### [GROOLS: reactive graph reasoning for genome annotation through biological processes](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-018-2126-1)
* Despite improvements in bioinformatics methods, millions of sequences in databanks are not
assigned reliable functions.
* The curation of protein functions in the context of biological processes is a way to evaluate
and improve their annotation.


## Data validation\database integration


##### Ontologies:
 * BioPortal: http://bioportal.bioontology.org/

##### [Ontology-based validation and identification of regulatory phenotypes](https://academic.oup.com/bioinformatics/article/34/17/i857/5093216)


##### On2Vec: Embedding-based Relation Prediction for Ontology Population
* This paper proposes a greatly improved translation-based graph embedding method that helps ontology population by way of relation prediction.
* Extensive experiments on four data sets show promising capability
of On2Vec on predicting and verifying relation facts.
* TODO: <span style="color:red" > Energy function</span>



##### [Detection of Relation Assertion Errors in Knowledge Graphs](https://dl.acm.org/citation.cfm?id=3148033)

##### [Enhanced ontology-based indexing and searching](https://www.emeraldinsight.com/doi/pdfplus/10.1108/AJIM-08-2014-0098)


##### Ontology-based validation and identification of regulatory phenotypes
* implementation: https://github.com/bio-ontology-research-group/phenogocon

##### [ONTOFUSION: ontology-based integration of genomic and clinical databases.](https://www.ncbi.nlm.nih.gov/pubmed/16144697)

##### [GROOLS: reactive graph reasoning for genome annotation through biological processes](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-018-2126-1)
* Problem: Despite improvements in bioinformatics methods, millions of sequences in databanks are not assigned reliable functions.
*

##### [MOEKA - Memoranda in Ontological Engineering and Knowledge Analytics](http://www.kanoe.org/Reports/RakshaPSMOEKA20144Report.pdf)


##### [Python scripts to find enrichment of GO terms](https://github.com/tanghaibao/goatools)

##### [Large-scale reasoning over functions in biomedical ontologies]()
* Use Apache Jena
* TODO: reproduce the results: https://github.com/bio-ontology-research-group/uniprot2owl
* "Expressing functions in biomedical ontologies currently uses formal representation patterns that renders basic reasoning tasks to fall in complexity classes beyond polynomial time, thereby limiting the potential of
using knowledge-based methods for data integration, querying or quality control."
* future works?
* limitations?

##### [Inferring ontology graph structures using OWL reasoning](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-017-1999-8)
* TOOD: look at citations
* Github repo: https://github.com/bio-ontology-research-group/Onto2Graph
* Ontology is a DAG
* application: semantic similarity
* "While the taxonomy of an ontology can be inferred directly from the axioms of an ontology as one of the standard OWL reasoning tasks, creating general graph structures from OWL ontologies that exploit the ontologies’ semantic content remains a challenge."
* Ontologies are widely applied in biology and biomedicine for annotation and integration of data [3].
* OWL  is a formal language based on Description Logics [8] and offers a formal, model-theoretic semantics.

##### OWL-NETS: Transforming OWL Representations for Improved Network Inference
* create an Abstract network from OWL
* implement in python 2.7
* <span style = "color:red"> use for modularization or partitioning of Ontology </span>



##### [Ontological Pathfinding(OP)](https://dl.acm.org/citation.cfm?id=2882954)
* website [link](https://dsr.cise.ufl.edu/projects/probkb-web-scale-probabilistic-knowledge-base/)
* [Repository](https://bitbucket.org/datasci/ontological-pathfinding/src/master/)
* contributions: "We  propose  the  Ontological  Pathfinding  algorithm (OP) that scales to web-scale knowledge bases via **a series of parallelization and optimization techniques**: a relational knowledge  base  model  to  apply  inference  rules  in  batches,  a  new  rule mining algorithm that parallelizes the join queries, **a novel partitioning algorithm** to break the mining tasks into smaller independent  sub-tasks,  and  **a  pruning  strategy**  to  eliminate  unsound  and resource-consuming rules before applying them. "
* rule mining on top of Spark
* Our primary focus of this paper is scalable mining.
* we model a knowledge base as a collection of (subject, predicate, object) facts Γ = {(s, p, o)}
  - Each predicate specifies relationships among its subjects and
  objects. We call each relationship a fact. For example, the fact
  (Barack Obama, wasBornIn, USA) specifies that Barack Obama
  was born in the USA.
* **Limitations?**
 - inference rules in batches using join queries
* **Future works?**

## node2vec, word embedding, sequence embedding

### [Graph embedding techniques, applications, and performance: A survey](https://www.sciencedirect.com/science/article/pii/S0950705118301540)
* challenges of embedding: **scalability, choice of dimensionality, and features to be preserved**
* Github repo: https://github.com/hamid58b/GEM
* One application of graph analysis is clustering
*


### [Sequence Embedding for Clustering and Classification](https://towardsdatascience.com/sequence-embedding-for-clustering-and-classification-f816a66373fb)
* https://github.com/cran2367/sgt


### [Learned protein embeddings for machine learning](https://academic.oup.com/bioinformatics/article/34/15/2642/4951834)
* TODO: related works on pubmed: https://www.ncbi.nlm.nih.gov/pubmed/29584811

### [Learning protein sequence embeddings using information from structure](https://arxiv.org/abs/1902.08661)
* Source code: https://github.com/tbepler/protein-sequence-embedding-iclr2019


### [MetaMLP: A fast word embedding based classifier to profile target gene databases in metagenomic samples](https://www.biorxiv.org/content/10.1101/569970v1)
* Source code: https://bitbucket.org/gaarangoa/metamlp/src/master/src/


### Translate words to Ontology


##### [Mapping Text to Knowledge Graph Entities using Multi-Sense LSTMs](https://www.aclweb.org/anthology/D18-1221)
*  Source code: https://bitbucket.org/dimkart/ms-lstm/src/master/


##### [Linking entities through an ontology using word embeddings and syntactic re-ranking, BMC Bioinformatics 2019](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-019-2678-8)
* unsupervised learning
* Linking each identified entity mention in text to an ontology/dictionary concept is an essential task to make sense of the identified entities.
* This paper presents an unsupervised approach for the linking of named entities to concepts in an ontology/dictionary.
* "Word embedding models, which learn distributed representations ofwords from large unlabeled corpora, are promising approaches for capturing seman- tic information [34].""

###### related works:
* [3, 8, 35, 42]  applying word embedding in biomedical domain

##### [ezTag: tagging biomedical concepts via interactive learning](https://academic.oup.com/nar/article/46/W1/W523/4999245)
* Online link: https://eztag.bioqrator.org/
* "To support annotating a wide variety of biological concepts with or without pre-existing training data, we developed ezTag, a web-based annotation tool that allows curators to perform annotation and provide training data with humans in the loop. ezTag supports both abstracts in PubMed and full-text articles in PubMed Central.""

#### [PubTator central: automated concept annotation for biomedical full text articles](https://academic.oup.com/nar/advance-article/doi/10.1093/nar/gkz389/5494727)
* PubTator Central (https://www.ncbi.nlm.nih.gov/research/pubtator/) is a web service for viewing and retrieving bioconcept annotations in full text biomedical articles.


##### [Thinking, Fast and Slow:Combining Vector Spaces and Knowledge Graphs](https://arxiv.org/pdf/1708.03310.pdf)
* <span style ="color:red" > A query processing engine that decomposes an input query to search, list, and infer on the Vectorized Knowledge Graph VKG structure </span>


##### [Short Text Similarity with Word Embeddings](https://dl.acm.org/citation.cfm?id=2806475)

##### [Onto2Vec: joint vector-based representation of biological entities and their ontology-based annotations](https://academic.oup.com/bioinformatics/advance-article/doi/10.1093/bioinformatics/bty933/5165380)
* implementation: https://github.com/bio-ontology-research-group/opa2vec/

##### [OPA2Vec: combining formal and informal content of biomedical ontologies to improve similarity-based prediction](https://academic.oup.com/bioinformatics/advance-article/doi/10.1093/bioinformatics/bty933/5165380)



##### [nod2vec](https://snap.stanford.edu/node2vec/)
* list of projects: http://snap.stanford.edu/projects.html
* [Deep Learning for Network Biology](http://snap.stanford.edu/deepnetbio-ismb/)
* weblog: [node2vec: Embeddings for Graph Data](https://towardsdatascience.com/node2vec-embeddings-for-graph-data-32a866340fef)
* [awesome-network-embedding](https://github.com/chihming/awesome-network-embedding)
* Python 3 implementations: https://github.com/eliorc/node2vec   :heavy_check_mark:

##### [Network embedding in biomedical data science](https://academic.oup.com/bib/advance-article/doi/10.1093/bib/bby117/5228144)

##### [BioKEEN: a library for learning and evaluating biological knowledge graph embeddings](https://academic.oup.com/bioinformatics/advance-article/doi/10.1093/bioinformatics/btz117/5320556)
* Implementation : https://github.com/SmartDataAnalytics/PyKEEN

## Text similarity

##### [Text Similarities : Estimate the degree of similarity between two texts](https://medium.com/@adriensieg/text-similarities-da019229c894)


## Review Papers:

##### [**RDF Data Storage and Query Processing Schemes: A Survey**](https://doi.org/10.1145/3177850)
* we focus on data storage techniques, indexing strategies, and query execution mechanisms.
* 5.2 Hadoop-Based RDF Systems


##### Rule Induction and Reasoning over Knowledge Graphs
* "
For rules learned
from incomplete (Knowledge Graphs)KGs, confidence and other measures may be misleading, as
they do not reflect the patterns in the missing facts. This might lead to the
extraction of erroneous rules from incomplete and biased KGs."


##### Knowledge Graph Refinement:A Survey of Approaches and Evaluation Methods
*  


## Modularization
##### [OWL Reasoning: Subsumption Test Hardness and Modularity](https://doi.org/10.1007/s10817-017-9414-8)


##### [Modular reuse of ontologies: Theory and practice](https://www.cs.ox.ac.uk/files/4559/live-2375-3703-jair.pdf)
 * "Such techniques enable the identification of a module of an ontology, i.e., a subset of the ontology’s axioms which then can be used for querying and classifying in, usually, less time than the time that would be required for querying or classifying the whole ontology."
 * limitations of this techniques: modularization techniques that reduce the signature do not enable queries of the whole ontology;


##### UniPort
* provide RDF as a representation format as well as a public SPARQL endpoint to facilitate querying.
* [Automatic annotations by UniProt](https://www.uniprot.org/help/automatic_annotation)
  * UniRule
  * SAAS


## Tools and implementations

##### GOATOOLS: A Python library for Gene Ontology analyses
* [Github repo](GOATOOLS: A Python library for Gene Ontology analyses)
* Process the obo-formatted file from Gene Ontology website. The data structure is a directed acyclic graph (DAG) that allows easy traversal from leaf to root.




##### Apache Jena https://jena.apache.org/index.html
* Q: Could it be run on top of Hadoop?
 * [link](A: https://jena.apache.org/documentation/hadoop/)
* https://jena.apache.org/documentation/ontology/
* [An Introduction to RDF and the Jena RDF API](https://jena.apache.org/tutorials/rdf_api.html)
* [Apache Jena - Examples](https://github.com/castagna/jena-examples)
*

##### Neo4j for graph Processing

##### SPARQL: RDF Query language.

##### Implementation: Semantic Search Based on Domain Ontology Using Apache Spark and Jena:
* [link](https://www.upwork.com/hiring/for-clients/semantic-search-based-on-domain-ontology-using-apache-spark-and-jena/)

### Implementation by MapReduce and Spark:
###### [RDF Data Storage Techniques for Efficient SPARQL Query Processing Using Distributed Computation Engines](https://ieeexplore.ieee.org/abstract/document/8424727)
* Hadoop has been adopted for RDF data management systems.
* we introduce distributed RDF data stores, namely VPExp and 3CStore, based on the existing vertical partitioning (VP) approach
*

###### [Scalable OWL Ontology Reasoning using Cloud Computing ](http://www.globalcis.org/ijact/ppl/IJACT1685PPL.pdf)

###### [Scalable visualization for DBpedia ontology analysis using Hadoop](https://onlinelibrary.wiley.com/doi/pdf/10.1002/spe.2310)
###### [OWL Reasoning Framework over Big Biological Knowledge Network](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4022201/pdf/BMRI2014-272915.pdf)

###### [SPOWL: Spark-based OWL 2 Reasoning Materialisation](http://delivery.acm.org/10.1145/3080000/3070609/a3-liu.pdf?ip=129.186.252.23&id=3070609&acc=ACTIVE%20SERVICE&key=B63ACEF81C6334F5%2EBC2F47327A8E8D08%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35&__acm__=1551829281_2a807486a76804f6c8411042a266f0a2)

###### [Scalable distributed reasoning using MapReduce](https://doi.org/10.1007/978-3-642-04930-9_40)


## Incremental reasoning
##### [An Incremental Reasoning Algorithm for Large Scale Knowledge Graph](https://link.springer.com/chapter/10.1007/978-3-319-99365-2_45)
* we propose an incremental reasoning algorithm which can effectively avoid re-reasoning over the entire knowledge graph
*


## Ontology reasoner
* elk: https://github.com/liveontologies/elk-reasoner



## Clustering
##### [Comparative Analysis of Sequence Clustering Methods for Deduplication of Biological Databases]()
* CD-HIT clustering
* TODO: ** re-implement this approach: What would be the computational and heuristic approach to increase this work**
* Future work?


* ISU Biological Ontologies
 - https://digital.ag.iastate.edu/isu-biological-ontologies-fall-seminar-series-september-17

##### [Biomolecular Data Resources: Bioinformatics Infrastructure for Biomedical Data Science](https://www.annualreviews.org/doi/abs/10.1146/annurev-biodatasci-072018-021321)
* Applying Ontology
* Update ontologies


##### PHD thesis' 14
* [Provenance, propagation and quality of biological annotation](https://theses.ncl.ac.uk/jspui/handle/10443/2774)



