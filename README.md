# AeroOSP – Aviation Operational Stress Prediction

AeroOSP is a data analysis and machine learning project focused on modelling operational stress in aviation systems.

The aim is to explore whether publicly available aviation data can be used to identify patterns linked with delays, disruption, staffing pressure, airport load, and knock-on operational effects.

This project is being developed as a learning and portfolio project, with the long-term goal of building a practical prediction pipeline that can process aviation data, extract useful features, and produce interpretable outputs.

---

## Project Goals

The main goals of AeroOSP are to:

* collect and clean aviation operational data,
* analyse trends in flight departures, arrivals, delays, and disruption,
* identify factors that may contribute to operational stress,
* build simple predictive models,
* visualise results clearly,
* create a project structure suitable for future academic and professional development.

---

## Current Focus

The current version focuses on building the foundation:

* loading raw aviation data into Python,
* cleaning and preparing data with pandas,
* exploring patterns through graphs and summary statistics,
* creating a repeatable workflow in Jupyter notebooks,
* preparing the project for future machine learning experiments.

Future versions may include models for predicting whether operational disruption or staffing pressure is likely to affect following flights after a known event.

---

## Technologies Used

This project uses:

* Python
* pandas
* NumPy
* Matplotlib
* Jupyter Notebook
* scikit-learn planned for future modelling

---

## Planned Project Structure

```text
AeroOSP/
│
├── data/
│   ├── raw/              # Original downloaded data
│   ├── processed/        # Cleaned and transformed data
│
├── notebooks/
│   ├── 01_data_loading.ipynb
│   ├── 02_exploratory_analysis.ipynb
│   ├── 03_feature_engineering.ipynb
│   └── 04_model_testing.ipynb
│
├── src/
│   ├── data_cleaning.py
│   ├── feature_engineering.py
│   ├── visualisation.py
│   └── modelling.py
│
├── outputs/
│   ├── charts/
│   └── reports/
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Sherloth/AeroOSP.git
cd AeroOSP
```

Create a virtual environment:

```bash
python -m venv .venv
```

Activate it:

On Windows PowerShell:

```bash
.venv\Scripts\Activate.ps1
```

On Git Bash or Linux/macOS:

```bash
source .venv/Scripts/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Example Workflow

The basic workflow is:

1. Download or place raw aviation data into `data/raw/`.
2. Load the data using pandas.
3. Clean missing or inconsistent values.
4. Generate summary statistics.
5. Create visualisations.
6. Build simple baseline models.
7. Compare model results against real outcomes.

---

## Possible Research Questions

This project may explore questions such as:

* Are delays more likely during specific times of day?
* Do delays cluster around certain airports or routes?
* Can one delayed flight increase the probability of following flights being disrupted?
* Are there patterns that suggest operational stress building up over time?
* Can simple models provide useful predictions before more advanced machine learning is introduced?

---

## Current Status

This project is in early development.

The current priority is not to create a perfect model immediately, but to build a reliable data pipeline and understand the structure of the available data.

---

## Roadmap

Planned future work:

* [ ] Add raw data import notebooks
* [ ] Build data cleaning scripts
* [ ] Add exploratory charts
* [ ] Create first baseline model
* [ ] Add feature engineering
* [ ] Compare different model approaches
* [ ] Add project report or technical write-up
* [ ] Create simple web or dashboard interface

---

## Disclaimer

This project is for educational, research, and portfolio purposes only.

It is not intended for real-world aviation safety, operational control, or commercial decision-making without proper validation, professional review, and access to verified operational data.

---

## Author

Created by Damian Kmiecik.

GitHub: [Sherloth](https://github.com/Sherloth)
