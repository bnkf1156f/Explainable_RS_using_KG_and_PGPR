# Explainable_RS_using_KG_and_PGPR Project
This repository implements an Explainable Recommender System using the Policy-Guided Path Reasoner (PGPR) over a knowledge graph built from the MovieLens-1M dataset. The system not only recommends items but also generates concise, human-readable explanations derived from multi-hop reasoning paths. <br><br>

First access to this link for all the required files: 
<a href="https://drive.google.com/drive/folders/1FBnh8SJvdTgmJoUoMvrzg7BppiHO8oIc">Drive Link</a>

Explainable_RS_using_KG_and_PGPR/
│
├── data/                  # Dataset and KG files (download from Drive)
├── models/                # Pretrained models (download from Drive)
├── results/               # Generated while running the code
│
├── knowledge_graph_utils.py   # Utility functions for building and querying the KG
├── main_Explainable_RS.ipynb  # Main notebook to run the system
├── mapper.py                  # Maps IDs to human-readable formats
├── requirements.txt           # List of required Python packages
├── setup.py                   # Setup script for the project
└── utils.py                   # General utility functions
