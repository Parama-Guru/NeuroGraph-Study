Social Network Data Analytics 
20XDAG - BRAIN CONNECTIVITY AND GRAPH THEORY ANALYSIS 
IN ALZHEIMER’S AND PARKINSON’S DISEASE

PROJECT SUMMARY

This project draws on concepts from the paper by Miraglia et al. (2022) 
on brain connectivity and graph theory analysis in Alzheimer’s and Parkinson’s 
diseases. The study leverages electrophysiological data to understand the 
synaptic disruptions and changes in functional connectivity associated with 
these neurodegenerative diseases. This project aims to analyze brain 
connectivity using graph theory, with a focus on the electrophysiological 
techniques that provide a cost-effective, non-invasive, and accessible method 
for large-scale population screening.

INTRODUCTION

The brain, one of the most complex systems in the human body, consists 
of billions of neurons that communicate through intricate networks. The 
concept of “brain connectivity analysis” has been developed to elucidate the 
mechanisms underlying these neuronal interactions. This analysis can be 
categorized into three main types: structural, functional, and effective 
connectivity. Structural connectivity is based on anatomical constraints and 
physical connections, functional connectivity captures the statistical correlation 
of neuronal activity, and effective connectivity describes the causal 
interactions between neural assemblies.

METHODS

Graph theory provides a mathematical framework to model the brain as a 
network of nodes (neurons or brain regions) and edges (connections). This 
project employs various graph theory parameters to study brain connectivity in 
Alzheimer’s and Parkinson’s patients, including:
        • Clustering Coefficient (C): Measures the number of connections that 
        exist between the nearest neighbors of a node as a proportion of the 
        maximum number of possible connections. It reflects the tendency of a 
        network to form topologically organized circuits and is often interpreted as a 
        metric of information segregation in networks.
        • Path Length (PL): The minimum number of edges that must be traversed 
        to go from one node to another. It is used as a measure of global integration 
        of the network.
        • Small-world (SW) Index: The ratio of the normalized clustering 
        coefficient and normalized path length. It describes a balance between 
        segregation and integration network properties, integrating the information 
        of global and local network characteristics.
        • Divergence: Measures the broadness of the weighted degree distribution, 
        where the weighted degree is the summed weights of all edges connected 
        to a node.
        • Modularity: The ratio of the intra- and intermodular connectivity strength, 
        where modules are subgraphs containing nodes that are more strongly 
        connected to themselves than to other nodes. Modularity is a measure of 
        the strength of the modules.
        • Efficiency: The ability of information exchange within the network.
        • Global Efficiency: Measures network integration and its overall 
        performance for information transferring. This measure is inversely related 
        to the average shortest path length.
        • Local Efficiency: Similar to clustering coefficient, local efficiency 
        measures the compactness of the subnetwork and provides insight into the 
        resilience of the network to node removal.
        • Centrality: Measures the importance of a node and its direct impact on 
        adjacent brain areas.
        • Betweenness Centrality: Used to investigate the contribution of each 
        node to all other node pairs on the shortest path. It measures not only 
        the importance of the nodes but also the amount of information flowing 
        through the node.
        • Strength: The sum of weights of connections (edges) of a node. The 
        strength can be averaged over the whole network to obtain a global 
        measure of connection weights.
        • Degree: The degree of a node is the sum of its incoming (afferent) and 
        outgoing (efferent) edges.
        • In-degree: Number of afferent connections to the node.
        • Out-degree: Number of efferent connections from the node.
        • Assortativity Coefficient: Represents a measure of a network’s 
        resilience. It is a correlation coefficient between the degrees of all vertices 
        on two opposite ends of an edge.

RESULTS :

Alzheimer’s Disease

        Graph theory has been applied to EEG data to study Alzheimer’s 
        disease, revealing significant disruptions in network properties. Key findings 
        include:
        • Increased Path Length: Indicating reduced global efficiency and slower 
        information transfer.
        • Decreased Clustering Coefficient: Suggesting a loss of local 
        connectivity and network complexity.
        • Altered Small-world Index: Reflecting a shift towards a more random 
        network organization, particularly in the alpha frequency band.
        • Changes in Global and Local Efficiency: Reduced efficiency in 
        information transfer both globally and locally.
        • Altered Divergence and Strength: Changes in the spread of weighted 
        degrees and the overall connection strengths.

Parkinson’s Disease

        Similarly, studies on Parkinson’s disease using graph theory have shown:
        • Reduced Clustering Coefficient and Path Length: Especially in the 
        theta and alpha bands, indicating impaired local and global connectivity.
        • Changes in Modularity: Highlighting disrupted community structures 
        within the brain network.
        • Variations in Small-world Index: Decreased in the theta and increased 
        in the alpha bands, describing a more ordered structure for lower 
        frequencies and more random for higher frequencies.

INFERENCE

An assortativity coefficient of approximately -0.056 indicates a slight 
negative assortativity in the graph. Here’s what this means:
        1.  Negative Assortativity: A negative assortativity coefficient suggests 
        that nodes with high degrees (nodes with many connections) are more 
        likely to be connected to nodes with low degrees (nodes with fewer 
        connections). In other words, the graph exhibits a tendency for nodes to 
        connect with nodes that have different degrees.
        2.  Magnitude: The value -0.056 is quite close to zero, indicating that the 
        graph has weak assortative mixing. In general, the closer the assortativity 
        coefficient is to -1, the stronger the disassortative mixing. Since -0.056 is 
        relatively small in magnitude, the negative assortativity is weak.
        • Sigma (\sigma): This metric compares the clustering coefficient and the 
        average shortest path length of the graph to those of a random graph with 
        the same number of nodes and edges. A value of \sigma > 1 indicates that 
        the graph is more clustered than a random graph and has a comparable 
        average shortest path length, which is characteristic of a small-world 
        network.
        • Omega (\omega): This metric compares the graph to a regular lattice and 
        a random graph. Values of \omega close to 0 indicate that the graph has 
        properties similar to both regular lattices (high clustering) and random 
        graphs (short average path lengths). Typically, a value of \omega between 
        -0.5 and 0.5 is indicative of a small-world network.
        CONCLUSION

This project demonstrates the utility of graph theory in analyzing brain 
connectivity and highlights the potential of electrophysiological techniques as 
tools for large-scale screening and monitoring of neurodegenerative diseases. 
Future research should focus on standardizing methods and exploring the 
integration of multiple biomarkers to enhance the accuracy and reliability of 
disease characterization.


