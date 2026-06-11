# ML Workshop

This repository is a hands-on collection of machine learning, deep learning and NLP notebooks covering classical models, PyTorch examples, sequence models, transformers and a small time-series pipeline. Notebooks are intended to be runnable in Google Colab or locally via Jupyter.

**Structure**

- **Classical ML/**
	- `introduction_to_scikit_learn.ipynb` — End-to-end scikit-learn workflow (data prep, model fit, evaluate, save/load).
	- `end-to-end-heart-disease-classification (1).ipynb` — Heart disease prediction using a 6-step ML modelling framework (EDA → modelling → tuning).
	- `breastCancer_classification_project.ipynb` — End-to-end breast cancer classification (EDA, preprocessing, several classifiers).

- **Deep Learning/**
	- `ANN.ipynb` — Simple artificial neural network implemented with NumPy.
	- `FFN.ipynb` — Feed-forward network and backpropagation examples.
	- `Pytorch_basics.ipynb` — PyTorch fundamentals: tensors, operations and basic APIs.
	- `building_neural_network_with_pytorch.ipynb` — Practical PyTorch NN example (data preparation → model → training).
	- `RNN.ipynb` — Recurrent Neural Network example for sequence prediction / text generation.

- **NLP/**
	- `Movie_Review_Sentiment_Classification.ipynb` — Movie review sentiment classification using sklearn pipelines (vectorization → logistic regression).
	- `Transformer_HuggingFace_Tutorial.ipynb` — Hugging Face transformers tutorial for text generation and tokenizer usage.

- **Time Series/**
	- `stock_prediction1.ipynb` — Stock price movement prediction pipeline using `yfinance`, feature engineering and tree-based models.

**Getting started (quick)**

- Recommended Python (3.9+). Create and activate a virtual environment:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

- Install common dependencies (adjust as needed):

```powershell
pip install --upgrade pip
pip install numpy pandas scikit-learn matplotlib seaborn jupyterlab notebook torch torchvision torchaudio transformers yfinance xgboost lightgbm statsmodels
```

- Start Jupyter locally:

```powershell
jupyter lab
```

Or open any notebook in Google Colab (many notebooks include a Colab badge and are Colab-ready).

**Data and file paths**

- Several notebooks expect data in a `data/` folder (e.g. `data/heart-disease.csv`) or use Google Drive paths (`/content/drive/My Drive/...`) when run in Colab. If running locally, place datasets under a `data/` folder or update the path variables in the notebooks.

**Notes & recommendations**

- Notebooks are mostly self-contained educational examples; some cells mount Google Drive or assume Colab — remove or adapt those cells when running locally.
- Transformer and large-model examples require internet access to download model weights and may need a GPU for reasonable performance.
- If you want, I can:
	- Generate a `requirements.txt` locked to the environment used here.
	- Add a small launcher script to open favorite notebooks.
	- Extract key cells into runnable .py scripts or automated experiments.

---
Updated: concise project overview and run instructions. If you'd like, I can add a `requirements.txt` now or generate short descriptions for each notebook's important cells.

