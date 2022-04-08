

# Exploritory Data Analysis
---
## Multiple Hypothesis Testing

Family-Wise Error Rate
- Bonferroni Correction
- Holm-Bonferroni Correction

False Discovery Rate
- Benjamini-Hochberg Correction

## Dimensionality Reduction

Principal Component Analysis
- Spectral Decomposition Theorem

Stochastic Neighbor Embedding

# Networks
---
## Terminology

Network = Graph (G)
Nodes = Vertices (V)
Links = Edges (E)
*G = (V, E)*

Representing a Network
- Adjacency List
- Adjacency Matrix

## Summary Statistics of Networks

- Connected Components
	- Set of nodes that are reachable from one another.
- Degree Distribution
	- Number of edges connected to a node.
	- Degree plots are often in log scale. Power-Law Degree Distribution.
- Diameter and Average Path Length
	- Diameter is the largest distance between any two nodes in the network.
	- Geodesic Path is the shortest path between two nodes.
- Homophily or Assortative Mixing
	- A tendency of people or nodes to associate with others that are similar.

## Centrality Measures of Networks

A measure that capures the importance of a nodes poisition in the network.

- Degree Centrality
	- Measurement of the connections a single node has.
	- Does not capture cascading effects
- Betweenness Centrality
	- Measurement of all the paths that pass through a node.
- Closeness Centrality
	- Measurement of how close one node is to any other node or nodes.
- Eigenvector Centrality
	- Measurement of how well connected one node is to the rest of the network.
	- *Builds the foundation for Google's PageRank algorithm.*
















# Data Sets

This is a public repository to store the collection of data sets I use in my work.
All of the data sets in this repository are listed below and stored in the data folder. Documentation, when available, is saved in the documentation folder.

### Filename - Retrieved Date - URL

Welcome! This is a public repository to store the collection of data sets I use in my work.

All of the data sets in this repository are listed below and stored in the data folder. Documentation, when available, is saved in the documentation folder.

## Using Data
You are welcome to download and use data however you'd like. If you'd prefer for your code to connect directly to a url, navigate to the file and view the data in its raw format. You can then use that url to paste into your code. See the screenshots below to help explain how to view in raw and an example R script that will scrape the file.

**Access Raw File URL**

![View_Raw_Data](https://user-images.githubusercontent.com/46005933/160300222-9bd53597-a675-4740-a772-117ff6d0115f.png)

**Connect to File in Code**

![R_scrape_script](https://user-images.githubusercontent.com/46005933/160300106-8e99b411-33ec-4709-9819-4f9e125008d7.png)

## Data Set List
**Filename - Retrieved Date - URL**

USA_Counties_Demographics.csv - March 2022 - https://hub.arcgis.com/datasets/esri::usa-counties/about

USA_Counties_Presidential_Elections_2000_2020 - March 2022 - https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/VOQCHQ
