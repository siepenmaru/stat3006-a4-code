# STAT3006 A4 Source Code

This is the repository for the code associated with my final report for the Statistical Learning (STAT3006) course in the University of Queensland.

The final written report itself can be found in [this repository](https://github.com/siepenmaru/STAT3006-A4).

## Files
[STAT3006_7305_assignment4_2023.pdf](STAT3006_7305_assignment4_2023.pdf): Assignment description and requirements

[Aaroe2010_Gene_expression_profiling_blood_detection_breast_cancer.pdf](Aaroe2010_Gene_expression_profiling_blood_detection_breast_cancer.pdf): Primary reference study for the report

[data](data): Datasets provided by the course, sourced from Aaroe et al. (2010)

[A4.ipynb](A4.ipynb): Jupyter Notebook used to analyse the data for the report

[figures](figures): Figures generated for the report

[supplementary](supplementary): Text-based data generated for the report. Includes things like model coefficients and feature rankings and such.

[requirements.txt](requirements.txt): List of python dependencies

## Running it yourself
```bash
python -m venv env
source env/bin/activate
pip install -r requirements.txt
jupyter-notebook . # alternatively, use vscode or your preferred text editor that supports ipynb
```

