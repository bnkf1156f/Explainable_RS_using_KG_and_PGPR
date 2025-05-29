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
├── data/ <pre>                 # Dataset and KG files (download from Drive)<br>
├── models/ <pre>               # Pretrained models (download from Drive)<br>
├── results/ <pre>              # Generated while running the code<br>
│<br>
├── knowledge_graph_utils.py<pre>   # Utility functions for building and querying the KG<br>
├── main_Explainable_RS.ipynb<pre>  # Main notebook to run the system<br>
├── mapper.py<pre>                  # Maps IDs to human-readable formats<br>
├── requirements.txt<pre>           # List of required Python packages<br>
├── setup.py<pre>                   # Setup script for the project<br>
└── utils.py<pre>                   # General utility functions<br>
