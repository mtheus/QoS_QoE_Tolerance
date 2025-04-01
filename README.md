# Incorporating User Tolerance into QoE Prediction

This repository contains the dataset and analysis scripts for the study titled:

**"Incorporating User Tolerance into QoE Prediction"**

To be presented at **The 36th IEEE International Symposium on Software Reliability Engineering (ISSRE 2025)**.

## Overview

The study investigates how incorporating user tolerance improves the prediction of Quality of Experience (QoE) in software systems. A sigmoidal model is proposed, where tolerance acts as a modulating variable, extending traditional approaches that rely solely on binary success/failure data.

## Repository Structure

```
.
├── data/
│   └── user_tolerance_responses.csv        # Raw survey responses and scenario evaluations
├── notebooks/
│   └── qoe_tolerance_analysis.ipynb        # Jupyter notebook with model fitting and evaluation
├── README.md                               # Project documentation
└── LICENSE                                 # Creative Commons Attribution 4.0 License
```

## Requirements

To run the analysis, the following Python packages are required:

```bash
pip install pandas numpy scipy matplotlib seaborn scikit-learn
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/mtheus/QoS_QoE_Tolerance.git
cd QoS_QoE_Tolerance
```

2. Run the Jupyter Notebook:

```bash
jupyter notebook notebooks/qoe_tolerance_analysis.ipynb
```

3. The notebook includes:
   - Data preprocessing
   - Sigmoidal model fitting (with and without tolerance)
   - F1-score evaluation
   - Paired statistical tests (t-test and Wilcoxon)

## Author

**Matheus Bastos Neves**  
Feel free to reach out via [mtheus@gmail.com](mailto:mtheus@gmail.com)

## License

This project is licensed under the **Creative Commons Attribution 4.0 International License**.  
You are free to share and adapt the material, provided appropriate credit is given.  
For more details, see: [https://creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/)

## Citation

If you use this dataset or code in your research, please cite:

```
@inproceedings{Neves2025,
  title={Incorporating User Tolerance into QoE Prediction},
  author={Matheus Bastos Neves},
  booktitle={Proceedings of the 36th IEEE International Symposium on Software Reliability Engineering (ISSRE)},
  year={2025},
  note={Under review}
}
```
