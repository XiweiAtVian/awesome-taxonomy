# awesome-taxonomy
A curated resource for taxonomy research


## Datasets / Shared Tasks

1. SemEval-2015 Task 17: Taxonomy Extraction Evaluation (TExEval-1), [Home](http://alt.qcri.org/semeval2015/task17/), [Report](http://aclweb.org/anthology/S15-2151)

2. SemEval-2016 Task 13: Taxonomy Extraction Evaluation (TExEval-2), [Home](http://alt.qcri.org/semeval2016/task13/), [Report](http://www.aclweb.org/anthology/S16-1168)

3. SemEval-2016 Task 14: Semantic Taxonomy Enrichment, [Home](http://alt.qcri.org/semeval2016/task14/), [Report](https://www.aclweb.org/anthology/S16-1169)

4. SemEval-2018 Task 9: Hypernym Discovery, [Home](https://competitions.codalab.org/competitions/17119), [Report](http://aclweb.org/anthology/S18-1115)

5. UnsupervisedHypernymy, [Home](https://github.com/vered1986/UnsupervisedHypernymy), [EACL 2017 paper](https://www.aclweb.org/anthology/E17-1007), including 4 datasets:

	* (Hypernymy Detection): EVAL, BLESS, LEDS (a.k.a Lenci/Benotto), Weeds

6. HypernymySuite, [Home](https://github.com/facebookresearch/hypernymysuite), [ACL 2018 paper](https://www.aclweb.org/anthology/P18-2057), including (somewhat modified) datasets: 
	
	* (Hypernymy Detection): BLESS, LEDS, EVAL, SHWARTZ, WBLESS
	* (Hypernymy Direction): BLESS, WBLESS, BIBLESS
	* (Graded Entailment):  HyperLex


## Paper


### Survey

- [A Short Survey on Taxonomy Learning from Text Corpora: Issues, Resources and Recent Advances](http://aclweb.org/anthology/D17-1123) \[ACL 2017\]


### Hypernymy  Discovery & Lexical Entailment

- [Learning Term Embeddings for Hypernymy Identification](https://www.ijcai.org/Proceedings/15/Papers/200.pdf) [IJCAI 2015]
- [Improving Hypernymy Detection with an Integrated Path-based and Distributional Method](https://www.aclweb.org/anthology/P16-1226) (HypeNet) \[ACL 2016\] 
	* Code: [https://github.com/vered1986/HypeNET](https://github.com/vered1986/HypeNET)
- [LexNET -- Integrated Path-based and Distributional Method for the Identification of Semantic Relations](https://www.aclweb.org/anthology/W16-5310) (LexNet) \[COLING 2016 CogALex-V\]
	* Code: [https://github.com/vered1986/LexNET](https://github.com/vered1986/LexNET)
- [TAXI at SemEval-2016 Task 13: a Taxonomy Induction Method based on Lexico-Syntactic Patterns, Substrings and Focused Crawling](https://www.aclweb.org/anthology/S16-1206) [SemEval 2016]
- [Relations such as Hypernymy: Identifying and Exploiting Hearst Patterns in Distributional Vectors for Lexical Entailment](https://aclweb.org/anthology/D16-1234) \[EMNLP 2016\]
	* Code: [https://github.com/stephenroller/emnlp2016](https://github.com/stephenroller/emnlp2016)
- [Learning Term Embeddings for Taxonomic Relation Identification Using Dynamic Weighting Neural Network](https://www.aclweb.org/anthology/D16-1039) [EMNLP 2016]
- [Hypernyms under Siege: Linguistically-motivated Artillery for Hypernymy Detection](https://www.aclweb.org/anthology/E17-1007) \[EACL 2017\]
	* Code: [https://github.com/vered1986/UnsupervisedHypernymy](https://github.com/vered1986/UnsupervisedHypernymy)
- [Hierarchical Embeddings for Hypernymy Detection and Directionality](https://aclweb.org/anthology/papers/D/D17/D17-1022/) (HyperVec) \[EMNLP 2017\]
	* Code: [https://github.com/nguyenkh/HyperVec](https://github.com/nguyenkh/HyperVec)
- [Distributional Inclusion Vector Embedding for Unsupervised Hypernymy Detection](https://www.aclweb.org/anthology/N18-1045) \[NAACL 2018\]
- [Specialising Word Vectors for Lexical Entailment](https://www.aclweb.org/anthology/N18-1103) \[NAACL 2018\]
	* Code: [https://github.com/nmrksic/lear](https://github.com/nmrksic/lear)
- [Term Definitions Help Hypernymy Detection](https://www.aclweb.org/anthology/S18-2025) \[SEM 2018\]
- [Hearst Patterns Revisited: Automatic Hypernym Detection from Large Text Corpora](https://www.aclweb.org/anthology/P18-2057) \[ACL 2018\]
	* Code: [https://github.com/facebookresearch/hypernymysuite](https://github.com/facebookresearch/hypernymysuite)
- [Improving Hypernymy Prediction via Taxonomy Enhanced Adversarial Learning](https://chywang.github.io/papers/aaai2019.pdf) \[AAAI 2019\]
	* Code: [https://github.com/chywang/TEAL](https://github.com/chywang/TEAL)
- [A Family of Fuzzy Orthogonal Projection Models for Monolingual and Cross-lingual Hypernymy Prediction](https://chywang.github.io/papers/www2019.pdf) \[WWW 2019\]
	* Code: [https://github.com/chywang/FOP](https://github.com/chywang/FOP)



### Concept Taxonomy Construction (Instance-based Taxonomy)

- [Semantic Taxonomy Induction from Heterogenous Evidence](http://aclweb.org/anthology/P06-1101) \[ACL 2006\]
- [Deriving a Large Scale Taxonomy from Wikipedia](https://pdfs.semanticscholar.org/c360/b473ae80b715c5b725c592b6ab04fd4ac430.pdf) \[AAAI 2007\]
- [A Metric-based Framework for Automatic Taxonomy Induction](http://aclweb.org/anthology/P09-1031) \[ACL 2009\]
- [A Semi-Supervised Method to Learn and Construct Taxonomies using the Web](http://aclweb.org/anthology/D10-1108) \[EMNLP 2010\]
- [MENTA: Inducing Multilingual Taxonomies from Wikipedia](http://gerard.demelo.org/papers/demelo-menta-cikm2010.pdf) \[CIKM 2010\]
- [A graph-based algorithm for inducing lexical taxonomies from scratch](https://www.ijcai.org/Proceedings/11/Papers/313.pdf) \[IJCAI 2011\]
- [Probase: A probabilistic taxonomy for text understanding](https://www.microsoft.com/en-us/research/wp-content/uploads/2012/05/paper.pdf) \[SIGMOD 2012\]
- [Learning Semantic Hierarchies via Word Embeddings](https://www.aclweb.org/anthology/P14-1113) [ACL 2014]
- [Two Is Bigger (and Better) Than One -- the Wikipedia Bitaxonomy Project](http://aclweb.org/anthology/P14-1089) \[ACL 2014\]
	* Resources: [http://wibitaxonomy.org/](http://wibitaxonomy.org/)
- [Structured Learning for Taxonomy Induction with Belief Propagation](http://aclweb.org/anthology/P14-1098) \[ACL 2014\]
- [Taxonomy Construction Using Syntactic Contextual Evidence](http://aclweb.org/anthology/D14-1088) \[EMNLP 2014\]
- [Incorporating Trustiness and Collective Synonym and Contrastive Evidence into Taxonomy Construction](http://aclweb.org/anthology/D15-1117) \[EMNLP 2015\]
- [Automatic Taxonomy Extraction from Bipartite Graphs](https://ieeexplore.ieee.org/document/7373326) [ICDM 2015]
- [Learning Concept Taxonomies from Multi-modal Data](http://aclweb.org/anthology/P16-1169) \[ACL 2016\]
- [Revisiting Taxonomy Induction over Wikipedia](http://www.aclweb.org/anthology/C16-1217) \[COLING 2016\]
- [Taxonomy Induction using Hypernym Subsequences](https://arxiv.org/pdf/1704.07626.pdf) \[CIKM 2017\] 
- [Comparing Constraints for Taxonomic Organization](https://www.aclweb.org/anthology/N18-1030) \[NAACL 2018 \]
- [HiExpan: Task-Guided Taxonomy Construction by Hierarchical Tree Expansion](http://hanj.cs.illinois.edu/pdf/kdd18_jshen.pdf) \[KDD 2018\]
	* Code: [https://github.com/mickeystroller/HiExpan](https://github.com/mickeystroller/HiExpan)
- [End-to-End Reinforcement Learning for Automatic Taxonomy Induction](http://aclweb.org/anthology/P18-1229) \[ACL 2018\]
	* Code: [https://github.com/morningmoni/TaxoRL](https://github.com/morningmoni/TaxoRL)
- [Inferring Concept Hierarchies from Text Corpora via Hyperbolic Embeddings](https://arxiv.org/pdf/1902.00913.pdf) \[ACL 2019\]

### Topic Taxonomy Construction (Clustering-based Taxonomy)

- [Automatic Taxonomy Construction from Keywords](http://cgcad.thss.tsinghua.edu.cn/shixia/publications/brt/paper.pdf) \[KDD 2012\]
- [A Phrase Mining Framework for Recursive Construction of a Topical Hierarchy](https://uofi.app.box.com/v/kdd13-cathy) \[KDD 2013\]
- [Efficient Methods for Inferring Large Sparse Topic Hierarchies](http://aclweb.org/anthology/P15-1075) \[ACL 2015\]
- [TaxoGen: Unsupervised Topic Taxonomy Construction by Adaptive Term Embedding and Clustering](http://hanj.cs.illinois.edu/pdf/kdd18_czhang.pdf) \[KDD 2018\]
	* Code: [https://github.com/franticnerd/taxogen](https://github.com/franticnerd/taxogen)

### Taxonomy Expansion & Enrichment

- [A graph-based approach for ontology population with named entities](https://dl.acm.org/citation.cfm?doid=2396761.2396807) \[CIKM 2012\]
- [A Hierarchical Dirichlet Model for Taxonomy Expansion for Search Engines](http://yichang-cs.com/yahoo/www14_local.pdf) \[WWW 2014\]
- [Reserating the awesometastic: An automatic extension of the WordNet taxonomy for novel terms](https://www.aclweb.org/anthology/N15-1169) \[NAACL 2015\]
- [SemEval-2016 Task 14: Semantic Taxonomy Enrichment](https://www.aclweb.org/anthology/S16-1169) \[SemEval 2016\]
- [Every child should have parents: a taxonomy refinement algorithm based on hyperbolic term embeddings](https://arxiv.org/pdf/1906.02002.pdf) \[ACL 2019\]

### Taxonomy Application

- [Taxonomy-driven computation of product recommendations](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.90.3304&rep=rep1&type=pdf) \[CIKM 2004\]
- [Supercharging Recommender Systems using Taxonomies for Learning User Purchase Behavior](https://arxiv.org/abs/1207.0136) \[VLDB 2012\] 
- [Taxonomy-Aware Multi-Hop Reasoning Networks for Sequential Recommendation](https://dl.acm.org/citation.cfm?id=3290972) \[WSDM 2019\] 
	* Code: [https://github.com/RUCDM/TMRN](https://github.com/RUCDM/TMRN)
- [A User-Centered Concept Mining System for Query and Document Understanding at Tencent 
](https://arxiv.org/pdf/1905.08487.pdf) \[KDD 2019\]
	* Code: [https://github.com/BangLiu/ConcepT](https://github.com/BangLiu/ConcepT)
- [Universal Representation Learning of Knowledge Bases by Jointly Embedding Instances and Ontological Concepts](http://web.cs.ucla.edu/~yzsun/papers/2019_KDD_JOIE.pdf) \[KDD 2019\]
	* Code: [https://github.com/JunhengH/joie-kdd19](https://github.com/JunhengH/joie-kdd19)


### Joint Taxonomy Construction and Application

- [Constructing Task-Specific Taxonomies for Document Collection Browsing](http://aclweb.org/anthology/D12-1117) \[EMNLP 2012\]
- [Taxonomy Discovery for Personalized Recommendation](https://ai.google/research/pubs/pub42499) \[WSDM 2014\]
- [On Interpretation of Network Embedding via Taxonomy Induction](http://www.public.asu.edu/~jundongl/paper/KDD18_Network_Embedding_Interpretation.pdf) \[KDD 2018\]
- [TiFi: Taxonomy Induction for Fictional Domains](https://arxiv.org/pdf/1901.10263.pdf) \[WWW 2019\]
