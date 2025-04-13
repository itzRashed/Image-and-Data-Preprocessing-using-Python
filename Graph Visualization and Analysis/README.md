# 📈 Graph Visualization and Analysis
This project is a basic exploration of **graph theory** concepts using the **NetworkX** library in Python.  
It demonstrates how to create, analyze, visualize, and modify graphs through various fundamental operations.

> 📍 Implemented in **Python** using **NetworkX** and **Matplotlib**

## 🧠 **Project Overview**
The code walks through:
- Creating undirected graphs
- Analyzing connectivity, paths, and centrality
- Drawing graphs and subgraphs
- Modifying structure by removing nodes/edges
- Exploring connected components

## 🗃️ **Dataset**
🚫 **No external dataset required**.  
All nodes and edges are defined within the code.

## ⚙️ **Code Functionality**

### ✅ **Installation**
Install required libraries using pip:

```bash
pip install networkx matplotlib

🧱 Graph Construction
- Create empty undirected graph
- Add nodes: G.add_nodes_from([1, 2, 3, 4, 5])
- Add edges: G.add_edges_from([...])

🖼️ Graph Visualization
- Draw graph using nx.draw() with bold node labels
- Display using plt.show()

📊 Graph Analysis
**Basic Info:**
- G.nodes()
- G.edges()
- G.number_of_nodes(), G.number_of_edges()

**Connectivity Check:**
- nx.is_connected(G)
- Shortest Path:
- nx.shortest_path(G, source=1, target=5)

**Degree & Centrality:**
- Node degrees using G.degree()
- Degree centrality with nx.degree_centrality(G)

**Clustering Coefficient:**
- nx.clustering(G)

🧩 Subgraph Visualization
- Create subgraph with nodes [1, 2, 4]
- Visualize it using the same drawing method

🔧 Graph Modification
- Create a copy using G.copy()
- Remove node 5: G_copy.remove_node(5)
- Remove edge (1, 2) from another copy
- Visualize modified versions

🔗 Connected Components
- Use nx.connected_components(G1)
- Draw each component individually
- Print total number of components

🧠 What I Learned
- How to create and manipulate graphs in Python
- How to check connectivity and find shortest paths
- Visualization of subgraphs and components
- Graph metrics like degree and clustering coefficient

📜 License
This project is licensed under the MIT License – free to use, modify, and share.
