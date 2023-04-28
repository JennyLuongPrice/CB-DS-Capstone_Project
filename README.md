# CB-DS-Capstone_Project
Capstone Project for Data Science Bootcamp

Community Learning and Network Analysis of Cancer Metabolites

Metabolomics is the study of small molecules, known as metabolites, that are present in a biological specimen, such as a cell, tissue, organism or biofluids. These metabolites include amino acids, lipids, sugars, and other molecules that are involved in many different biological pathways.
Metabolomics aim to analyze and understand the metabolic state of a biological component at a biochemical level by identifying and quantifying the metabolites present in a sample. This can provide insights into the underlying biochemical processes, as well as the effects of environmental and genetic factors on metabolism.

Metabolomics can be used in a variety of applications, including disease diagnosis and treatment, drug discovery, nutrition research, and much more. It is often used in conjunction with other techniques, such as genomics and proteomics, to provide a more comprehensive understanding of biological systems.

For the data sources available, I used an online database (https://hmdb.ca/) of different metabolites and conditions for specific biological specimens and web scraped the database to create my own dataset of the metabolites found in 12 cancers from the clinical data available.

For the capstone project, I wanted to leverage the power of machine learning for disease modelling and possibly classification, regression, or clustering of metabolomics data. However, clustering and supervised machine learning methods were not suited as the data was very sparse. Instead, using Networkx and Louvain Community Detection gave better results.
