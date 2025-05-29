<h1>🎬 Explainable Recommender System using Knowledge Graph and PGPR</h1>

<p>This repository implements an <strong>Explainable Recommender System</strong> using the <strong>Policy-Guided Path Reasoner (PGPR)</strong> over a knowledge graph built from the <em>MovieLens-1M</em> dataset. The system provides both item recommendations and human-readable explanations through multi-hop reasoning paths.</p>

<hr>

<h2>📁 Dataset and Pretrained Models</h2>

<p>📥 <strong>Download all required files</strong> (datasets, pretrained models, etc.) from the following Google Drive link:</p>

<p>👉 <a href="https://drive.google.com/drive/folders/1FBnh8SJvdTgmJoUoMvrzg7BppiHO8oIc" target="_blank">Google Drive – Required Files</a></p>

<hr>

<h2>📂 Project Directory Structure</h2>

<p>After downloading, ensure your project directory is structured as follows:</p>

<pre>
Explainable_RS_using_KG_and_PGPR/
├── data/                     # Dataset and KG files (downloaded from Drive)
├── models/                   # Pretrained models (downloaded from Drive)
├── results/                  # Automatically generated during runtime

├── knowledge_graph_utils.py  # Functions for building and querying the KG
├── main_Explainable_RS.ipynb # Main notebook to run the system
├── mapper.py                 # Maps IDs to human-readable formats
├── requirements.txt          # List of required Python packages
├── setup.py                  # Setup script for the project
└── utils.py                  # General utility functions
</pre>

<hr>
