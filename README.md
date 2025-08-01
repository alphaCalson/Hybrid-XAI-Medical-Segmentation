# Hybrid Explainability Framework for Transformer-Based Medical Image Segmentation

This repository contains the implementation of a novel hybrid explainability framework for Transformer-based medical image segmentation, focusing on chest X-rays for TB and pneumonia detection in South Africa. The project follows the CRISP-DM methodology and aims to enhance clinical trust through transparent AI.

## Setup Instructions
1. Clone the repository: `git clone https://github.com/alphaCalson/Hybrid-XAI-Medical-Segmentation.git`
2. Create a virtual environment: `python -m venv .venv`
3. Activate the environment:
   - Windows: `.venv\Scripts\activate`
   - Linux/Mac: `source .venv/bin/activate`
4. Install dependencies: `pip install -r requirements.txt`
5. Download datasets (e.g., CheXmask) from [PhysioNet](https://physionet.org/content/chexmask-cxr-segmentation-data/1.0.0/).

## Project Structure
- `data/`: Dataset storage (not committed).
- `src/`: Source code for data loading, models, and explainability.
- `notebooks/`: Jupyter notebooks for exploration.
- `docs/`: Documentation for each CRISP-DM phase.
- `visualizations/`: Plots and heatmaps.

## License
Creative Commons Attribution 4.0 International