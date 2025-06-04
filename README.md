# Biological Network Clustering Analysis

This project explores the structural and functional organization of large-scale biological interaction networks using two clustering algorithms: **Markov Clustering (MCL)** and **Molecular Complex Detection (MCODE)**. By identifying densely connected subgraphs, we aim to uncover potential protein complexes, pathways, and functional modules within biological systems.

## Objective

Compare MCL and MCODE in:
- Clustering quality
- Biological relevance
- Computational efficiency

## Hypothesis

- MCL will identify broader functional modules.
- MCODE will detect smaller, tightly interconnected complexes.
- MCL is expected to be more scalable and efficient on large biological networks.

## Dataset

- Source: [Pathway Commons](https://www.pathwaycommons.org/)
- Format: `.sif` (Simple Interaction Format)

## Technologies Used

- Python
- NetworkX
- Cytoscape-compatible data formats
- Google Colab / Jupyter Notebooks

## Results

- MCL performed well in identifying broader communities.
- MCODE showed high specificity for tightly-knit protein complexes.
- Both algorithms offer complementary insights for network-based biology.

## Future Work

- Implement hybrid clustering techniques.
- Apply machine learning to automate motif discovery.
- Validate results using biological annotations (e.g., GO terms).

## Authors

- **Santhos Kamal Arumugam Balamurugan**
- **Aditya Kwatra**

## License

This project is for academic purposes only. Contact the authors for reuse or collaboration.
