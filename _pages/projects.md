---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

Research Projects
======
* **Data ETL for Deep Learning Model Selection Tasks with Dask**, UCSD, **Jan '22 - present**
    * Working on designing a extensible and generic data loader for deep learning tasks pertaining to multi modal datasets.
    * Developing a data parallel approach for scalable data preprocessing ETL.

* **[Integrate Cerebro (deep learning model selection system) with Dask](https://drive.google.com/file/d/1e-chrx22wGqx5fTEnND5NJvyzkfP4ERL/view?usp=sharing)**, UCSD, **Sep '21 - Dec '21**
    * Developed a new backend for Cerebro using Dask that completely removes the Spark dependency while still implementing MOP.
    * Implemented and showed the parallelism achieved by MOP using the Dask backend in a distributed cluster environment. 
    * Evaluated the system performance on the Criteo dataset and performed an extensive analysis of results and comparison with the Spark backend.

* **Parallelization of K-Medoids Clustering Algorithm**, BITS Pilani, **Aug '18 - Dec '18**
    * Developed parallel K-Medoids algorithm using Adaptive Gridding for spatial partitioning in Spark Java.
    * Improved the algorithm’s efficiency of selecting initial medoids without compromising the clustering error (average sample size is 10x less than the state of the art - [PAMAE](https://www.kdd.org/kdd2017/papers/view/pamae-parallel-k-medoids-clustering-with-high-accuracy-and-efficiency) given any skewed data set.

* **[Parallelization of Union-find Algorithm](https://github.com/VigneshN1997/unionfind)**, BITS Pilani, **Jan '18 - Oct '18**
    * Developed a communication efficient distributed Union-find algorithm using Open MPI in C++.
    * Reduced the number of message passing operations between processes (15% reduction) using deferred bulk updates.

Course Projects
======
* **[Implementing and simulating performance of branch predictors](https://github.com/Abhiram-Medisetti/CSE240A)**, **Computer Architecture**, **Oct '21 - Dec '21**
    * Implemented the GShare, Tournament and Perceptron branch predictors in C.
    * Compared qualitatively and quantitatively the performance of the branch predictors on the Championship Branch Prediction traces.
    * Showed the improvement in the branch prediction performance (10% improvement on average) when using Perceptron predictor over Tournament and GShare predictors.

* **[Kinship Verification from Facial Images of Parents and their Kids](https://drive.google.com/file/d/1oJjtbW8Rp8cT_gGW8kv5S4PLYX5Z-1_2/view?usp=sharing)**, **Machine Learning**, **Nov '18 - Dec '18**
    * Compared qualitatively and quantitatively the existing techniques (Artificial Neural Networks, SVM, CNN, ensemble of SVMs) for Kinship Verification in R using Keras library.
    * Used the results to design and implement an ensemble of Metric Learning based CNN architecture.
    * Improved accuracy by 2.8% on the KinFaceW-1 dataset and by 3.1% on the KinFaceW-2 dataset.

* **[Compare and Contrast Linear Regression Models - Machine Learning](https://docs.google.com/document/d/1uwPI-bd95bbtZUWy3hwK7Suhg5BiddN8/edit?usp=sharing&ouid=110756118847265203158&rtpof=true&sd=true)**, **Machine Learning**, **Sep '18 - Oct '18**
    * Linear regression is used for finding relationship between a target variable and one or more predictors.
    * Compared Simple Linear Regression and Bayesian Linear Regression models both qualitatively and quantitatively.

* **[Data Analysis and Modelling of Student Course Grades](https://drive.google.com/file/d/1Hw2y56NvogpiB1pxx8AstbfZN7h4Hwoa/view?usp=sharing)**, **Machine Learning**, **Sep '18 - Oct '18**
    * Created a Bayesian Belief Network using bnlearn library in R based on grades of students, incorporating various hypotheses as to how attributes in data are related. 
    * The network can answer complex queries without being adversely affected by missing values, irrelevant attributes, and size of data.
    * The network can be used to assess teaching pedagogies by modelling natural language queries as conditional probabilities.

* **[Foster’s Design Methodology on a Distributed Data Structure (RAQ)](https://drive.google.com/file/d/12tTptQ4D-PfePyNMwuDZJK5R1P3maXoR/view?usp=sharing)**, **Parallel Computing**, **Apr '18 - May '18**
    * Designed a parallel algorithm to facilitate joining and leaving of peers from a peer to peer network (represented as [RAQ data structure](http://faculty.marshall.usc.edu/Hamid-Nazerzadeh/pdf/raq.pdf)) using Foster’s Design methodology with a commodity cluster as the target platform.
    * Obtained logarithmic speedup and improved time complexity of joining mechanism compared to sequential execution.

* **[Compiler for C-Like Language](https://github.com/VigneshN1997/Toy-Compiler-in-C)**, **Compiler Construction**, **Jan '18 - Apr '18**
    * Developed lexical, syntax, semantic analyzers, and code generator modules of a compiler for a language in C.
    * Implemented functionalities to support simple functions, simple matrix operations, and conditional statements.

* **[Designing Sieve of Eratosthenes Algorithm for Distributed Memory Systems](https://github.com/VigneshN1997/Sieve-of-Eratosthenes-Parallel-Algorithm)**, **Parallel Computing**, **Feb '18 - Mar '18**

* **[Designing Word Document Index for Distributed Memory Systems](https://github.com/VigneshN1997/Word-Document-Index-Application)**, **Parallel Computing**, **Feb '18 - Mar '18**


* **[Design Word Document Index Creation for Shared Memory Systems](https://github.com/VigneshN1997/Word-Document-Frequency-PRAM-Algorithm)**, **Parallel Computing**, **Jan '18 - Feb '18**
    * Designed a PRAM algorithm for document index creation using OpenMP in C++ for a UNIX based file system.
    * Developed a scalable divide and conquer algorithm on a file system with up to 160,000 files.
    * Reduced time taken to create an index from 43 seconds on 1 CPU core to 9 seconds on 32 CPU cores.

* **[Implement and Validate “AnyDBC” Algorithm (a variant of DBSCAN)](https://github.com/VigneshN1997/AnyDBC_C_Code)**, **Parallel Computing**, **Jun '17 - Jul '17**
    * Implemented [AnyDBC](https://www.kdd.org/kdd2016/subtopic/view/anydbc-an-efficient-anytime-density-based-clustering-algorithm-for-very-lar) sequential algorithm in C++ to compare its execution time results against those of DBSCAN.
    * The algorithm performs fewer range queries compared to DBSCAN and produces an approximate result quickly and improves the result over time until the correct solution is obtained.

* **[Night Canteen Data Analysis](https://github.com/VigneshN1997/Night-Canteen-Data-Analysis)**, **Data Mining**, **Nov '17 - Dec '17**
    * Given a dataset comprising of all transactions that happened at the Night Canteen analysed the data using Data Mining techniques and also draw inferences on the dataset.
    * Proposed questions that can be answered using Data Mining techniques.

* **[Analysis of Rank-Indexed Hashing](https://drive.google.com/file/d/1WDzH8YlzRBK0r2UO4XGSxRMzW-Dhyq1T/view?usp=sharing)**, **Data Structures and Algorithms**, **Nov '17 - Dec '17**
    * Analysis of the research paper: “Rank-Indexed Hashing: A Compact Construction of Bloom Filters and Variants”. The paper describes a new hash table which performs similar to a counting bloom filter while using lesser space. 
    * The analysis includes explaining rank indexed hashing, pseudo codes for insert, find, time and space complexity analysis and advantages, limitations and its applications.

* **[Microprocessor: Design and Simulation](https://github.com/rajatjain1997/Washing-Machine-Microprocessor)**, **Microprocessors and Interfacing**, **Mar '17 - Apr '17**
    * Designed a microprocessor for an automatic washing machine using the 80x86 processor.
    * Designed and simulated the circuit on Proteus with assembly code written in MASM.