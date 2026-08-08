# IoT Botnet DDoS Detection

Detection of IoT botnet-driven DDoS attacks using machine learning.

## Project Structure

```
iot-botnet-ddos-detection/
├── data/              # Raw + processed data (gitignored, too large for git)
│   ├── raw/
│   └── processed/
├── notebooks/         # Jupyter notebooks for EDA, modeling
├── src/               # Reusable Python scripts
├── results/           # Tables, plots, model outputs
├── paper/             # LaTeX/Word draft, references
├── .gitignore
└── README.md
```

## Setup

```bash
python -m venv iot-ml-env
iot-ml-env\Scripts\activate
pip install -r requirements.txt
```

## Data

Place raw datasets in `data/raw/`. Processed/feature-engineered datasets go in `data/processed/`. Data files are excluded from version control via `.gitignore`.
