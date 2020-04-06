## Covid19 text network
In this work, we develop a dense graph network of words to summarize thousands of research articles into topics related to coronavirus. We used COVID-19 Open Research Dataset (CORD-19), which is prepared by the White House and a coalition of leading research groups. CORD-19 is a resource of over 47,000 scholarly articles, including over 36,000 with full text, about COVID-19, SARS-CoV-2, and related coronaviruses. This freely available dataset is provided to the global research community to apply recent advances in natural language processing and other AI techniques to generate new insights in support of the ongoing fight against this infectious disease. 

## Graph
graph_data.zip file contains all the graph files (.gephi and .gexf). You need to install Gephi to visualize the network. 
1. covid19_abstract.geph is the graph network of all the available abstracts.
2. covid19_abstract.gexf is the graph meta data of all the abstracts.
3. covid19_title.geph is the graph network of all the titles of 29K articles.
4. covid19_title.gexf is the graph meta data of all the titles of 29K articles.

<!-- There are some .csv files in the folder. Each .csv file is the saved node data of a subgraph. For example, drug.csv includes all the neighboring nodes of the drug and associated information. -->


## Figures
All the figures inside this folder are generated from Gephi.


## Codes
The Jupyter notebooks have all the necessary codes for graph and analysis:

1. covid_19_text_network.ipynb: In this notebook, all the preprocessing and networking building process has been written. I used Neo4J to save the graph.

2. covid_19_analysis.ipynb: This file is  used to analyze the CSV files located in the graph folder

Covid19 dataset can be downloaded from https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge

## Paper:

I this folder, the manuscript is located. The paper is being written on overleaf.com.