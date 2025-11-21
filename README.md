# Part Dimension and Material Changes Impact Overall Structure

> Structural-analysis project: how part dimensions and material changes affect overall structural performance. Implemented as a Jupyter notebook and analysis scripts.

## Table of contents
- [About](#about)
- [Files](#files)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Quick start](#quick-start)
- [How to run](#how-to-run)
- [Reproducibility](#reproducibility)
- [License](#license)
- [Contact](#contact)

## About
This project studies how changes in part dimensions and material selections affect structural performance indicators (for example, maximum stress, displacement, weight, and factor of safety). The analysis is performed on a **synthetically generated** dataset to demonstrate workflows for data preprocessing, exploratory analysis, feature engineering, and simple predictive modeling.

## Files
- `Part_Dimension_and_Material_Changes_Impact_Overall_Structure.ipynb` — main Jupyter notebook (rename or upload your notebook to this filename)  
- `data/boeing_737_change_management_dataset.csv` — synthetic dataset (included)  
- `data_dictionary.md` — auto-generated data dictionary describing columns and types  
- `DATASET_DOCUMENTATION.md` — notes about dataset generation, assumptions, limitations  
- `requirements.txt` — Python dependencies  
- `.gitignore` — common ignores (keeps large data out of the repo by default)  
- `LICENSE` — project license (MIT placeholder included)  
- `CONTRIBUTING.md` — how to contribute

## Dataset
This repository uses a **synthetically generated** dataset intended for experimentation and demonstration. **Do not** treat it as real operational data. See `DATASET_DOCUMENTATION.md` for generation details and limitations.

**Dataset quick facts (auto-detected):**
- Rows: 5000  
- Columns: 27  

If you prefer not to store the dataset in the repo, keep it locally and ensure `data/` is in `.gitignore`. See `DATASET_DOCUMENTATION.md` for instructions.

## Requirements
Recommended Python 3.9+. Create a virtual environment and install the dependencies:

```bash
python -m venv venv
source venv/bin/activate   # macOS / Linux
venv\Scripts\activate      # Windows (PowerShell)
pip install -r requirements.txt
```

## Quick start
```bash
git clone https://github.com/<your-username>/Part-Dimension-and-Material-Changes-Impact-Overall-Structure.git
cd Part-Dimension-and-Material-Changes-Impact-Overall-Structure
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
jupyter lab
# open the notebook: Part_Dimension_and_Material_Changes_Impact_Overall_Structure.ipynb
```

## How to run
1. Ensure `data/boeing_737_change_management_dataset.csv` exists in the `data/` directory (or follow the download instructions if stored externally).  
2. Open and run the notebook in order. Cells at the top print package versions to aid reproducibility.  
3. Follow notes in the notebook for long-running experiments — use checkpoints or run sections selectively.

## Reproducibility
- Use `pip install -r requirements.txt` or run the included `Dockerfile` if running in a container.  
- Avoid committing large trained model files; place them under `models/` and add those to `.gitignore`.

## License
This project is licensed under the MIT License — see `LICENSE`.

## Contact
Ojas Bodke — link to your GitHub profile or email.
