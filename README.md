# Explainable Recommender System using Knowledge Graph and PGPR
This repository implements an Explainable Recommender System using the Policy-Guided Path Reasoner (PGPR) over a knowledge graph constructed from the MovieLens-1M dataset. The system provides both item recommendations and human-readable explanations via multi-hop reasoning paths.

## 📁 Dataset and Pretrained Models
📥 Download all required files (datasets, pretrained models, etc.) from the following Google Drive link: <br>
👉 Google Drive – <a href="https://drive.google.com/drive/folders/1FBnh8SJvdTgmJoUoMvrzg7BppiHO8oIc">Required Files</a>
<br><br>
**After downloading, ensure your project directory has the following structure:**
<br>
Explainable_RS_using_KG_and_PGPR/<br>
│<br>
├── data/                  # Dataset and KG files (download from Drive)<br>
├── models/                # Pretrained models (download from Drive)<br>
├── results/               # Generated while running the code<br>
│<br>
├── knowledge_graph_utils.py   # Utility functions for building and querying the KG<br>
├── main_Explainable_RS.ipynb  # Main notebook to run the system<br>
├── mapper.py                  # Maps IDs to human-readable formats<br>
├── requirements.txt           # List of required Python packages<br>
├── setup.py                   # Setup script for the project<br>
└── utils.py                   # General utility functions<br>
