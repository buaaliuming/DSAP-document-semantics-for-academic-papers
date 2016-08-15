# DSAP-document-semantics-for-academic-papers

Here we provide a annotated corpus for the long document semantic similarity evaluation. This semantic similarity dataset between documents are using the academic papers in computational linguistics domain. A set of paper pairs are generated from ACL Anthology Network (AAN) corpora(Dragomir R. Radev, Pradeep Muthukrishnan, and Vahed Qazvinian. 2009. The ACL anthology network corpus. In Proceedings of the 2009 Workshop on Text and Citation Analysis for Scholarly Digital Libraries. Association for Computational Linguistics, pages 54-61.), which consist of papers published in the past ACL conferences.

Twelve experts of our research group annotated and cross validated the coherence of 1021 pairs of documents. Each paper pair get a second annotation by a different person after the first annotation. If the second annotation is in accordance with the first one, it will be annotated as the ground truth, else a third person will annotate the paper pair to get the ground truth.

Each paper pair is annotated by both a 2-level and by a 5-level annotation as ground truth. Each paper pair is marked as 1 if semantically similar or 0 if dissimilar in 2-level annotation. In 5-level annotation a paper pair is marked by integers ranging from 1 to 5 according to their semantic similarity degree. If they are totally equal in semantic, similarity between papers will be annotated as 5, and if they have nothing to do with each other, similarity is annotated as 1.

For anything about the dateset please contract liuming@nlsde.buaa.edu.cn
