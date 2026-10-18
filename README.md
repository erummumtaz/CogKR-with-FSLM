\# CogKR with FSLM: Learning Style Prediction



This repository contains the official implementation of the \*\*CogKR (Cognitive Knowledge Reasoning)\*\* framework applied to the \*\*Felder-Silverman Learning Style Model (FSLSM)\*\*. 



\## ⚠️ Data Availability \& Privacy

To protect participant privacy, this repository \*\*does not\*\* contain the raw RDF files containing student names and email addresses. 



The model was trained on a de-identified dataset. The re-identification key is securely held offline. If you require access to the data for academic verification, please contact the authors under a data-use agreement.



\## 📂 Repository Structure

\- `CogKR\_Implementation\_train (5).ipynb`: Notebook used for preprocessing, knowledge graph construction, and training the RL agent.

\- `CogKR\_Implementation\_Test\_\&\_Visuals (5).ipynb`: Notebook used for testing, evaluation (Hit@k, MAP), and generating the visualizations (UMAP, cognitive profiles).

\- `\*.png`: The output visualizations presented in the paper.



\## 🚀 Setup \& Reproduction

1\. Clone this repository:

&#x20;  ```bash

&#x20;  git clone https://github.com/erumumtaz/CogKR-with-FSLM.git



2\. Install the required Python packages:



bash

pip install -r requirements.txt

Run the Jupyter Notebooks to reproduce the training and visualizations.



📝 Citation

If you use this code in your research, please cite our paper (Citation details to be added upon publication).

