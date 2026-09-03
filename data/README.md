# Data

This directory is intentionally empty in the repository. The raw dataset is not tracked by Git; see the project's `.gitignore` file.

## Downloading the dataset

Download the **Online Retail II** dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/502/online+retail+ii).

Dataset details:

- File name: `online_retail_II.xlsx`
- File size: 43.5 MB
- Number of records: 1,067,371
- Time period: 1 December 2009 to 9 December 2011

Place the downloaded file at:

```text
data/online_retail_II.xlsx
```

Then open and run:

```text
notebooks/capstone_analysis.ipynb
```

The notebook expects the dataset at the path shown above.

## Generated data

Running the notebook generates the following working dataset:

```text
cleaned_online_retail.csv
```

This generated file is excluded from version control through `.gitignore`.

## Citation

Chen, D. (2012). *Online Retail II* [Dataset]. UCI Machine Learning Repository.  
https://doi.org/10.24432/C5CG6D

## Licence

The dataset is distributed under the [Creative Commons Attribution 4.0 International licence](https://creativecommons.org/licenses/by/4.0/).
