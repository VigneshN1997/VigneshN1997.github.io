---
layout: archive
title: "UCSD"
permalink: /ucsd_updates/
author_profile: true
---

Summer 2022
======
* Software Engineering Intern @**ServiceNow**
    * Developed a database agnostic producer-consumer based architecture for database compaction.
    * Implemented Java API for periodic and user triggered compaction, job cancellation and managing compaction statistics.
    * Introduced guard rails for safe execution of compaction, along with
    ensuring race conditions are avoided when multiple nodes contest for compaction jobs.

Spring 2022
======
* **CSE 256: Statistical Natural Language Processing**
    * This course explored statistical techniques for the automatic analysis of natural language data. Specific topics covered include: probabilistic language models, which define probability distributions over text sequences; text classification; sequence models; parsing sentences into syntactic representations; machine translation, and machine reading.
    * The course was a good hands-on introduction to Natural Language Processing with multiple projects including implementing NLP models from scratch in Python.
    * The projects gave a good experience in building baseline models and then building improvements on top of baselines and also learning to ensure reproducibility. Also, a good exposure to technical report writing was given through the projects.
    * The projects were implemented using Object-Oriented programming concepts to design the models in a modular and extensible fashion.
        * **Language models**: Implemented a trigram language model with linear interpolation smoothing and analyzed its performance on texts from different domains.
        * **Sequence tagging**: Designed a Trigram-HMM sequence tagging model and the Viterbi decoding algorithm in Python.
        * **Machine Translation**: Implemented IBM Models 1 and 2 for the task of finding alignments in a parallel corpus containing English and Spanish sentences. 

* **CSE 291: Structured Prediction for Natural Language Processing**
    * This course  explored structured probabilistic modeling techniques in NLP, with a split focus between supervised and unsupervised methods.
    * This course is also a hands-on project based course with projects in PyTorch. The projects gave a good experience in implementing the algorithm in PyTorch along with writing up reports in research paper format.
        * **Decoding strategies in Neural Machine Translations**: 
        * **Neural Conditional Random Field for Named Entity Recognition**:
        * **Neural Conditional Random Field for Constituency Parsing**: 

* [CSE 293: Research project](https://adalabucsd.github.io/)
    * Completed the implementation of ETL pipeline for multimodal data to be used for deep learning model selection.
    * Developed Model Hopper Parallelism technique for scalable model selection using XML-RPC in Python.
    * Integrating the ETL pipeline with Model Hopper on a Kubernetes cluster setup to enable scalable model selection workloads on multimodal datasets.

Winter 2022
======
* [CSE 224: Graduate Network Systems](https://cseweb.ucsd.edu/~gmporter/)
    * This was a “learn by doing” course (in **Go**) where the material is learned by implementing a number of hands-on projects using real cloud computing environments.
    * The course provided a graduate-level understanding of networked systems design and implementation. Topics include techniques for building distributed applications, basics of networking, sockets programming, Remote Procedure Calls, managing scalability, networked storage, distributed consensus and state management, fault tolerance.
    * Projects done in the course: (Github repositories will be updated soon)
        * Socket programming
            * **Multi-node file record sort**
                * Given multiple files with records distributed across multiple machines designed a multi-node system to partition the records, send relevant records to peer servers, and sort then records according to a custom comparator. 
                * The system was designed using socket level programming in Go and tested by instantiating virtual machines using Docker.
            * **HTTP web server**
                * Designed a web server that implements a subset of the HTTP/1.1 protocol specification (200, 400, 404 responses) using socket level programming in Go.
                * The server supports HTTP pipelining of requests/responses and also implements a timeout mechanism. 
                * Implemented a HTTP request parser to parse the HTTP request into a request object and generate a HTTP response accordingly. 
                * Followed test driven development approach for developing features and wrote multiple unit tests and end-to-end tests for maximizing testing coverage. (Learnings coming soon)
        
        * Remote Procedure Calls (RPC)
            * **Dropbox-like file storage service**: Developed a cloud-based file storage service that is based on Dropbox. Implemented the cloud service, and a client which interacts with the service via gRPC.
            * **Fault tolerant file storage service**: Implemented the RAFT distributed consensus protocol using gRPC in Go. 


* [CSE 293: Research project](https://adalabucsd.github.io/)
    * Worked on designing a extensible and generic data loader for deep learning tasks pertaining to multi modal datasets. (more details coming soon)
* Teaching Assistant [DSC 102: Graduate Network Systems](https://cseweb.ucsd.edu/~arunkk/dsc102_winter22/index.html)
    * Led discussions for the programming assignment on Data Exploration with Dask on an AWS cluster.
    * Conducted regular office hours to help with students' doubts for the  programming assignments and exams.
    * Designed and verified questions for the midterm and final exam.

Fall 2021
======
* [CSE 234: Data Systems for Machine Learning](https://cseweb.ucsd.edu//classes/fa21/cse234-a/)
    * Research based course on Machine Learning Systems, at the intersection of ML, Data management and Systems. I opted for the project pathway in the course where me along with another student partner worked on a quarter long project.
    * The course included weekly paper reviews, pertaining to seminal papers in the ML Systems area raning across source, build and deploy phases of an ML system.
    * Integrating Cerebro with Dask: [Technical report of project](https://drive.google.com/file/d/1e-chrx22wGqx5fTEnND5NJvyzkfP4ERL/view?usp=sharing)
    * Project featured on: [ADALab Cerebro](https://adalabucsd.github.io/cerebro.html) 
* [CSE 240A: Computer Architecture](https://sites.google.com/eng.ucsd.edu/cse240a-f21/lecture-materials)
    * The course covered core concepts of computer architecture including CPU performance evaluation, instruction set architecture, pipelining, branch prediction, cache and memory hierarchy and GPU architecture.
    * The course included homework, exams, paper reviews, and a course project of implementing different branch prediction schemes.
    * Paper review of [Fat Loads: Exploiting Locality Amongst Contemporaneous Load Operations to
Optimize Cache Accesses](https://dl.acm.org/doi/abs/10.1145/3466752.3480104) 
    * Branch prediction algorithms comparison
* [CSE 130: Programming Languages](https://nadia-polikarpova.github.io/cse130-web/)
    * The course introduced Lambda Calculus and went through programming languages concepts using a pure functional language Haskell.
    * The course included programming assignments on lambda calculus, Haskell, higher order functions, tail recursion, recursive datatypes, environments and closures, and type classes.
