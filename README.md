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

<h2>📦 Installation/Set up of environment</h2>

<pre><code>python -m venv <env_name_as_per_your_choice>
</code></pre>
<pre><code><env_name>/Scripts/activate
</code></pre>
<pre><code>pip install -r requirements.txt
</code></pre>

<hr>

<h2>🚀 Running the Project</h2>

<ol>
  <li>Open the notebook: <code>main_Explainable_RS.ipynb</code></li>
  <li>Run all cells to:
    <ul>
      <li>Load the knowledge graph</li>
      <li>Train the PGPR model</li>
      <li>Generate recommendations and explanations</li>
    </ul>
  </li>
</ol>

<hr>

<h2>💡 Features</h2>
<ul>
  <li>Multi-hop reasoning over knowledge graphs</li>
  <li>Policy-guided explanation generation / **Reinforcement Learning in RS**</li>
  <li>Human-interpretable recommendation paths</li>
  <li>Built using the MovieLens-1M dataset</li>
</ul>

<hr>

<h2>📚 References</h2>
<ul>
  <li>MovieLens Dataset: <a href="https://grouplens.org/datasets/movielens/" target="_blank">https://grouplens.org/datasets/movielens/</a></li>
  <li>Tutorial: <a href="https://explainablerecsys.github.io/recsys2022/">Project Page</a></li>
</ul>

<hr>

<h2>📝 License</h2>
<p>This project is for <strong>educational purpose only</strong>.</p>
