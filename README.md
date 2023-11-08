## Drug Repurposing using Knowledge Graph Embeddings 💊
This repository relates to the paper **"Drug repurposing using knowledge graph embeddings with a focus on vector-borne diseases: a model comparison"**, as developed by Diego López Yse and Diego Torres for the Conference on Cloud Computing, Big Data &amp; Emerging Topics 2023.

You can find here the data and code used for developing and evaluating the predictive models.

### Repository structure
- **[dataset](dataset)**: Contains the compound IDs and names used to map predictions against the model's ground truth.

- **[embedding_models](embedding_models)**: Contains the embedding models and predictions on target diseases performed on the DRKG dataset.

- **[KGE_system.py](KGE_system.py)**: Outputs a drug ranking prediction based on chosen disease and embedding model

### Environment
The project was developed in Spyder 4 IDE using Python 3.8.8
