# Hierarchical Classification

This repo provide an implementation of a Hierarchical Classifier.

Hierarchical classification can be seen as a particular type of structured
classification problem, where the output of the classification algorithm is
defined over a class taxonomy; whilst the term structured classification is
broader and denotes a classification problem where there is some structure
(hierarchical or not) among the classes. It is important then to define what
exactly is a class taxonomy.

#### Definition 1 (Class taxonomy).
A class taxonomy is a tree structured regular concept hierarchy defined over a
partially ordered set $(C,\prec)$, where $C$ is a finite set that enumerates all class concepts in
the application domain, and the relation $\prec$ represents the “IS-A” relationship and has the following properties: asymmetric, anti-reflexive and transitive.

- $\forall c_i,c_i \in C,$ if $c_i \prec c_j$ then $c_j \nprec c_i $
- $\forall c_i \in C, c_i \nprec c_i $
- $\forall c_i, c_j, c_k \in C,c_i \prec c_j$ and $c_j \prec c_k$ imply $c_i \prec c_k $






For more information look at the pdf document called HierarchicalClassification.pdf
