# G2ACO
G2ACO
# Requirements
torch_geometric==2.4.0
# G2ACO

**Unsupervised Graph Attention Autoencoder Clustering-Oriented (G2ACO)** is a lightweight and effective model for **community detection in attributed networks**. By combining graph attention mechanisms with an autoencoder framework and a clustering-oriented loss, G2ACO captures both topological and attribute information, guiding representation learning directly toward meaningful community assignments.

## Features

- 📊 **Graph Attention Encoder**: Multi-head attention layers to learn expressive node embeddings.
- 🔄 **Inner-Product Decoder**: Reconstructs graph structure and node attributes.
- 🧠 **Clustering-Oriented Loss**: Integrates k-means as a target distribution loss for community detection.
- ⚡ **Faster Runtime**:  Faster runtime.

## Requirements

```bash
python >=3.8
torch >=2.0.0
torch_geometric==2.4.0
numpy
scikit-learn
```



## Datasets

G2ACO has been evaluated on:

- **Citation Networks**: Cora, Citeseer, and Pubmed
- **Social Network**: BlogCatalog

## Citation
---
*If you find our paper and code useful in your research, please consider giving a star ⭐ and citation 📝.*

```bibtex
@article{Bekkair2025,
  author  = {Bekkair, Abdelfateh and Bellaouar, Slimane and Oulad-Naoui, Slimane},
  title   = {Unsupervised graph attention autoencoder clustering-oriented for community detection in attributed networks},
  journal = {International Journal of Data Science and Analytics},
  year    = {2025},
  month   = may,
  day     = {29},
  doi     = {10.1007/s41060-025-00800-4},
  url     = {https://doi.org/10.1007/s41060-025-00800-4},
  issn    = {2364-4168},
}
```

