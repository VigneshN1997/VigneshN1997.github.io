---
layout: archive
# title: "Resume"
permalink: /resume/
author_profile: true
---

<p style="text-decoration:underline;"><a href="https://vigneshn1997.github.io/files/Vignesh_resume.pdf">Download my resume here</a></p>

Education
======
* Bachelor of Engineering (Honours) Computer Science, Birla Institute of Technology and Science Pilani, Pilani Campus  **Aug '15 - Jun '19**  


Professional Experience
======
* **Research Engineer**, **AI Labs, American Express (Amex)**, Bengaluru, India,     **Jul '19 - Present**
  * Responsibilities: Developing new features and maintaining existing features for the AXGBoost algorithm (have contributed to 4 releases till date); exploring new research problems relevant to the business for future products.
  * Projects:
    * **Improvement of XGBoost Distributed Algorithm**
        * Researching on weights used in Weighted Quantile Sketch algorithm by comparing trees built using Single Machine and Distributed XGBoost algorithm.
        * Proved empirically and theoretically the scope for optimising weights used by the Distributed XGBoost algorithm. Working on deriving weights more faithful to the XGBoost objective function.
    * **Development of a Universal Search Pipeline**
        * Developed an end-to-end system that enables context-aware search for enterprise wide unstructured information retrieval using Neo4j, Machine Reading Comprehension algorithm, and Django. (Amongst the 5 projects selected out of 13 as part of an internal ideation workshop).
        * Set up internal end-user tests and found that 73% of the queries are answered in the top 10 results.
    * **Development of features for AXGBoost**
        * Optimized the distributed algorithm code base from a 2400+ lines code to \textless 500 lines for the new version of AXGBoost (Amex XGBoost) in C++ for better maintainability (has been used in building 10,000+ models internally).
        * Working on providing GPU support using CUDA for the new version of AXGBoost algorithm.

Internships
======
* **Research Intern**, **AI Labs, American Express (Amex)**, Bengaluru, India,     **Jan '19 - Jun '19**
    * Researched on open-source XGBoost algorithm with a focus on the distributed algorithm (in the Amex context).
    * Improved the Approximate Split Point Proposal Algorithm used in distributed AXGBoost, which improved the capture rate on Amex datasets by 4%.
    * Inherited functionality from XGBoost to design and implement the architecture for CSV data reading in AXGBoost.
    * Improved column distributed data reading of CSV files in AXGBoost so that no column is skipped while reading.

* **Summer Analyst**, **Goldman Sachs**, Bengaluru, India,     **May '18 - Jul '18**
    * Developed a generic parallel email scanner to enable easy access to conversations that went down for a deal.
    * Developed the scanner using Microsoft Exchange Web Services and Java Spring Framework.
    * Set up RabbitMQ queues for storing mails at intermediate steps, processed the mails to remove redundant information using text processing techniques, and finally stored them in MongoDB.

* **Summer Intern**, **Gnowledge Lab, Homi Bhabha Centre for Science Education**, Mumbai, India,     **May '17 - Jul '17**
    * Developed a feature-rich offline search engine using Django for a digital learning platform (CLIx) to enable quick content access in schools with poor internet connectivity (deployed in 500 government schools).
    * Worked on document ingestion and database initialization using Elasticsearch for diverse types of documents.
    * Implemented functions to support suggestions, advanced triplet search, contribution search, and search filters.