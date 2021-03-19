---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

Research Projects
======
* **Parallelization of K-Medoids Clustering Algorithm**, BITS Pilani, **Aug '18 - Dec '18**
    * Developed parallel K-Medoids algorithm using Adaptive Gridding for spatial partitioning in Spark Java.
    * Improved the algorithm’s efficiency of selecting initial medoids without compromising the clustering error (average sample size is 10x less than the state of the art - [PAMAE](https://www.kdd.org/kdd2017/papers/view/pamae-parallel-k-medoids-clustering-with-high-accuracy-and-efficiency) given any skewed data set.

* **Parallelization of Union-find Algorithm**, BITS Pilani, **Jan '18 - May '18**
    * Developed a communication efficient distributed Union-find algorithm using Open MPI in C++.
    * Reduced the number of message passing operations between processes using deferred bulk updates.

Course Projects
======
* **[Kinship Verification from Facial Images of Parents and their Kids](https://1drv.ms/b/s!Avpe_Wh3r4Bfg4I5m5y8E6r0dl9w-Q?e=KugDQZ)**, **Machine Learning**, **Nov '18 - Dec '18**
    * Compared qualitatively and quantitatively the existing techniques (Artificial Neural Networks, SVM, CNN, ensemble of SVMs) for Kinship Verification in R using Keras library.
    * Used the results to design and implement an ensemble of Metric Learning based CNN architecture.
    * Improved accuracy by 2.8\% on the KinFaceW-1 dataset and by 3.1\% on the KinFaceW-2 dataset.

* **[Data Analysis and Modelling of Student Course Grades](https://1drv.ms/b/s!Avpe_Wh3r4Bfg4I1OFsB7IxLlPSafA?e=DflKKs)**, **Machine Learning**, **Sep '18 - Oct '18**
    * Created a Bayesian Belief Network using bnlearn library in R based on grades of students, incorporating various hypotheses as to how attributes in data are related. 
    * The network can answer complex queries without being adversely affected by missing values, irrelevant attributes, and size of data.
    * The network can be used to assess teaching pedagogies by modelling natural language queries as conditional probabilities.

* **[Foster’s Design Methodology on a Distributed Data Structure (RAQ)](https://1drv.ms/b/s!Avpe_Wh3r4BfgvcVSlIvhp9oIuwjOQ?e=ZQghW1)**, **Parallel Computing**, **Apr '18 - May '18**
    * Designed a parallel algorithm to facilitate joining and leaving of peers from a peer to peer network (represented as [RAQ data structure](http://faculty.marshall.usc.edu/Hamid-Nazerzadeh/pdf/raq.pdf)) using Foster’s Design methodology with a commodity cluster as the target platform.
    * Obtained logarithmic speedup and improved time complexity of joining mechanism compared to sequential execution.

* **[Compiler for C-Like Language](https://github.com/VigneshN1997/Toy-Compiler-in-C)**, Compiler Construction, **Jan '18 - Apr '18**
    * Developed lexical, syntax, semantic analyzers, and code generator modules of a compiler for a language in C.
    * Implemented functionalities to support simple functions, simple matrix operations, and conditional statements.

* **[Design Word Document Index Creation for Shared Memory Systems](https://github.com/VigneshN1997/Word-Document-Frequency-PRAM-Algorithm)**, **Parallel Computing**, **Jan '18 - Feb '18**
    * Designed a PRAM algorithm for document index creation using OpenMP in C++ for a UNIX based file system.
    * Developed a scalable divide and conquer algorithm on a file system with up to 160,000 files.
    * Reduced time taken to create an index from 43 seconds on 1 CPU core to 9 seconds on 32 CPU cores.