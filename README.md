# Minimum Spanning Tree Visualizer

A Streamlit web application that demonstrates the implementation of Kruskal's Algorithm and Prim's Algorithm for finding the Minimum Spanning Tree (MST) of a weighted graph.

## Live Demo

https://minimum-spanning-tree-ggeyj8ertacgkm5a3d5yff.streamlit.app/

## Features

* Interactive Streamlit interface
* Kruskal's Algorithm implementation
* Prim's Algorithm implementation
* MST edge visualization
* Total MST cost calculation
* Graph representation using NetworkX and Matplotlib

## Technologies Used

* Python
* Streamlit
* NetworkX
* Matplotlib

## Project Structure

```text
minimum-spanning-tree/
│
├── mini_span_tree.py
├── requirements.txt
├── README.md
```

## Installation

Clone the repository:

```bash
git clone <repository-url>
cd minimum-spanning-tree
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run mini_span_tree.py
```

## Algorithms Implemented

### Kruskal's Algorithm

Constructs the Minimum Spanning Tree by selecting edges in increasing order of weight while avoiding cycles using the Union-Find data structure.

### Prim's Algorithm

Constructs the Minimum Spanning Tree by growing the tree one vertex at a time, selecting the minimum-weight edge connecting the tree to a new vertex.

## Output

The application displays:

* MST edges
* Total MST cost
* Graph visualization
* Comparison of Kruskal's and Prim's results

## Deployment

The application is deployed using Streamlit Community Cloud.

## Author

Subash Prakash
