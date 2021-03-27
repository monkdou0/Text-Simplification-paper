# Text Simplification Paper

This repo contains a list of paper related to the topic of text simplification.

Text simplification is the process of reducing the linguistic complexity of a text,while still retaining the oroginal information and meaning. There are  three main research directions currently. First, Few datasets are available in this field.In order to get more data,we need **data augmentation**. Second,We need to establish scientific and practical **evaluation metric** for this task. Third,the **approach** to do text simplification is important obviously. There are three approach to do text simplification:**Lexical simplification**,**syntactice simplification** and **text generation**.

The following is a list of related papers,If any error, please open an issue.

---

![outline](./outline.png)



## Survey

**A Survey on Text Simplification** <font color=blue>arXiv2020</font>  [pdf](https://arxiv.org/pdf/2008.08612.pdf)

**Data-Driven Sentence Simplification: Survey and Benchmark** <font color=blue>arXiv2020</font>  [pdf](https://www.mitpressjournals.org/doi/pdf/10.1162/coli_a_00370)

**A Survey of Automated Text Simplification**  <font color=blue>IJACSA2014</font>  [pdf](https://thesai.org/Downloads/SpecialIssueNo9/Paper_9-A_Survey_of_Automated_Text_Simplification.pdf)

---

## Leaderboard

**Text simplification on TurkCorpus** [link](https://paperswithcode.com/sota/text-simplification-on-turkcorpus)

**Text simplification on ASSET** [link](https://paperswithcode.com/sota/text-simplification-on-asset)

---



## data augmentation

**ASSET: A Dataset for Tuning and Evaluation of Sentence Simplification Models with Multiple Rewriting Transformations** <font color=red>ACL2020</font> [pdf](https://arxiv.org/pdf/2005.00481.pdf)

**Neural CRF Model for Sentence Alignment in Text Simplification** <font color=red>ACL2020</font> [pdf](https://www.aclweb.org/anthology/2020.acl-main.709.pdf)

**Neural Text Simplification in Low-Resource Conditions Using Weak Supervision**  <font color=red>ACL2019</font> [pdf](https://www.aclweb.org/anthology/W19-2305/)

**Text Simplification from Professionally Produced Corpora**  <font color=red>ACL2018</font> [pdf](https://www.aclweb.org/anthology/L18-1553/)

**CATS: A Tool for Customized Alignment of Text Simplification Corpora**  <font color=red>ACL2018</font> [pdf](https://www.aclweb.org/anthology/L18-1615/)

**Sentence Alignment Methods for Improving Text Simplification Systems**  <font color=red>ACL2017</font> [pdf](https://www.aclweb.org/anthology/P17-2016.pdf)

**Semantic Features Based on Word Alignments for Estimating Quality of Text Simplification**   <font color=red>ACL2017</font> [pdf](https://www.aclweb.org/anthology/I17-2019/)

---



## evaluation metric

**The GEM Benchmark:Natural Language Generation, its Evaluation and Metrics** <font color=red>Arxiv2021</font> [pdf](https://arxiv.org/abs/2102.01672)

**EASSE: Easier Automatic Sentence Simplification Evaluation** <font color=red>EMNLP2019</font> [pdf](https://www.aclweb.org/anthology/D19-3009/)

**BLEU is Not Suitable for the Evaluation of Text Simplification** <font color=red>EMNLP2018</font> [pdf](https://www.aclweb.org/anthology/D18-1081/) [code](https://github.com/eliorsulem/HSplit-corpus)

**Semantic Structural Evaluation for Text Simplification**  <font color=red>NAACL2018</font> [pdf](https://www.aclweb.org/anthology/N18-1063/) [code](https://github.com/eliorsulem/SAMSA)

**Benchmarking Lexical Simplification Systems** <font color=red>ACL2016</font> [pdf](https://www.aclweb.org/anthology/L16-1491/) [code](https://github.com/ghpaetzold/LEXenstein)

**Optimizing Statistical Machine Translation for Text Simplification** <font color=blue>TACL2016</font>  [pdf](https://www.aclweb.org/anthology/Q16-1029/)  [code](https://github.com/cocoxu/simplification)



---



## lexical simplification

**Recursive Context-Aware Lexical Simplification** <font color=red>EMNLP2019</font> [pdf](https://www.aclweb.org/anthology/D19-1491/)

**A Word-Complexity Lexicon and A Neural Readability Ranking Model for Lexical Simplification** <font color=red>EMNLP2018</font> [pdf](https://www.aclweb.org/anthology/D18-1410/)

**Simplification Using Paraphrases and Context-based Lexical Substitution** <font color=red>ACL2018</font> [pdf](https://www.aclweb.org/anthology/N18-1019/)

**SV000gg at SemEval-2016 Task 11: Heavy Gauge Complex Word Identification with System Voting** <font color=red>ACL2016</font> [pdf](https://www.aclweb.org/anthology/S16-1149/)

**PLUJAGH at SemEval-2016 Task 11: Simple System for Complex Word Identification** <font color=red>ACL2016</font> [pdf](https://www.aclweb.org/anthology/S16-1146/)

**UWB at SemEval-2016 Task 11: Exploring Features for Complex Word Identification** <font color=red>ACL2016</font> [pdf](https://www.aclweb.org/anthology/S16-1162/)

**LTG at SemEval-2016 Task 11: Complex Word Identification with Classifier Ensembles** <font color=red>ACL2016</font> [pdf](https://www.aclweb.org/anthology/S16-1154/)

**A Simple Word Embedding Model for Lexical Substitution**  <font color=red>ACL2015</font> [pdf](https://www.aclweb.org/anthology/W15-1501/)

**Simplifying Lexical Simplification: Do We Need Simplified Corpora?**  <font color=red>ACL2015</font> [pdf](https://www.aclweb.org/anthology/P15-2011/)

**LEXenstein: A Framework for Lexical Simplification** <font color=red>ACL2015</font> [pdf](https://www.aclweb.org/anthology/P15-4015/)

**Text Simplification as Tree Transduction**  <font color=red>ACL2013</font> [pdf](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.393.9757&rep=rep1&type=pdf)

**Selecting Proper Lexical Paraphrase for Children** <font color=red>ACL2013</font> [pdf](https://www.aclweb.org/anthology/O13-1007/)

**The CW Corpus: A New Resource for Evaluating the Identi cation of Complex Words**  <font color=red>ACL2013</font> [pdf](https://www.aclweb.org/anthology/W13-2908/)

**UOW-SHEF: SimpLex – Lexical Simplicity Ranking based on Contextual and Psycholinguistic Features** <font color=red>ACL2012</font> [pdf](https://www.aclweb.org/anthology/S12-1066/)

**Putting it Simply: a Context-Aware Approach to Lexical Simplification** <font color=red>ACL2011</font> [pdf](https://www.aclweb.org/anthology/P11-2087/)

**For the sake of simplicity: Unsupervised extraction of lexical simplifications from Wikipedia** <font color=red>NAACL2010</font> [pdf](https://www.aclweb.org/anthology/N10-1056/)

**Mining a Lexicon of Technical Terms and Lay Equivalents**   <font color=red>ACL2007</font> [pdf](https://www.aclweb.org/anthology/W07-1007/)

**The Unified Medical Language System (UMLS): integrating biomedical terminology**   [pdf](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC308795/)

---



## syntactice simplification

**Simple, readable sub-sentences** <font color=red>ACL2013</font> [pdf](https://www.aclweb.org/anthology/P13-3021/)

---



## Machine learning

### statistical machine translation

 **Hybrid simplification using deep semantics and machine translation**  <font color=red>ACL2014</font> [pdf](https://www.aclweb.org/anthology/P14-1041.pdf)

**Sentence Simplification by Monolingual Machine Translation** <font color=red>ACL2012</font> [pdf](https://www.aclweb.org/anthology/P12-1107.pdf)

**Learning to Simplify Sentences Using Wikipedia**  <font color=blue>arXiv2011</font>  [pdf](https://www.aclweb.org/anthology/W11-1601/)

---



### deep learning

**Iterative Edit-Based Unsupervised Sentence Simplification** <font color=red>ACL2020</font> [pdf](https://www.aclweb.org/anthology/2020.acl-main.707/)

**EditNTS: An Neural Programmer-Interpreter Model for Sentence Simplification through Explicit Editing** <font color=red>ACL2019</font> [pdf](https://www.aclweb.org/anthology/P19-1331/)

**Integrating Transformer and Paraphrase Rules for Sentence Simplification** <font color=red>EMNLP2018</font> [pdf](https://www.aclweb.org/anthology/D18-1355/)

 **A Detailed Evaluation of Neural Sequence-to-Sequence Models for In-domain and Cross-domain Text Simplification**  <font color=red>ACL2018</font> [pdf](https://www.aclweb.org/anthology/L18-1479/)

**Reference-less Quality Estimation of Text Simplification Systems**  <font color=red>ATA 2018</font> [pdf](https://www.aclweb.org/anthology/W18-7005.pdf)

**Simple and Effective Text Simplification Using Semantic and Neural Methods** <font color=red>ACL2018</font> [pdf](https://www.aclweb.org/anthology/P18-1016/)

**Dynamic Multi-Level Multi-Task Learning for Sentence Simplification**  <font color=red>COLING2018</font> [pdf](https://arxiv.org/pdf/1806.07304.pdf)

**Exploring Neural Text Simplification Models**  <font color=red>ACL2017</font> [pdf](https://www.aclweb.org/anthology/P17-2014.pdf)

**Text Simplification as Tree Labeling** <font color=red>ACL2016</font> [pdf](https://www.aclweb.org/anthology/P16-2055/)

---



### unsupervised learning

**Multilingual Unsupervised Sentence Simplification** <font color=red>Arxiv2020</font> [pdf](https://arxiv.org/abs/2005.00352) 

**CUT: Controllable Unsupervised Text Simplification** <font color=red>Arxiv2020</font> [pdf](https://arxiv.org/abs/2012.01936)

**Semi-Supervised Text Simplification with Back-Translation and Asymmetric Denoising Autoencoders** <font color=red>AAAI2020</font> [pdf](https://arxiv.org/abs/2004.14693)

**Zero-Shot Crosslingual Sentence Simplification** <font color=red>EMNLP2020</font>   [pdf](https://www.aclweb.org/anthology/2020.emnlp-main.415/)

**Unsupervised Neural Text Simplification** <font color=red>ACL2019</font> [pdf](https://www.aclweb.org/anthology/P19-1198/)



---



### Reinforcement Learning

**Sentence Simplification with Deep Reinforcement Learning**  <font color=red>EMNLP2017</font> [pdf](https://www.aclweb.org/anthology/D17-1062/)

---



## Analysis

**Metaphors in Text Simplification:To change or not to change, that is the question**  <font color=red>ACL2019</font> [pdf](https://www.aclweb.org/anthology/W19-4444/)

---

##Controllable Text Simplification

**Controllable Text Simplification with Explicit Paraphrasing** <font color=red>Arxiv2020</font> [pdf](https://arxiv.org/abs/2010.11004)

**Controllable Text Simplification with Lexical Constraint Loss** <font color=red>ACL2019</font> [pdf](https://www.aclweb.org/anthology/P19-2036/)

**Controllable Sentence Simplification** <font color=red>Arxiv2019</font> [pdf](https://arxiv.org/pdf/1910.02677.pdf)

**Learning Simplifications for Specific Target Audiences**   <font color=red>ACL2018</font> [pdf](https://www.aclweb.org/anthology/P18-2113/)

   

## Application

**Neural Text Simplification of Clinical Letters with a Domain Specific Phrase Table**  <font color=red>ACL2019</font> [pdf](https://www.aclweb.org/anthology/P19-1037/)

**Lexi: A tool for adaptive, personalized text simplification** <font color=red>ACL2018</font> [pdf](https://www.aclweb.org/anthology/C18-1021/)

**Simple PPDB: A Paraphrase Database for Simplification** <font color=red>ACL2016</font> [pdf](https://www.aclweb.org/anthology/P16-2024/)

