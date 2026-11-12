# Applied Statistics

This repository contains my submission for the Applied Statistics module.
The project uses Python and a Jupyter notebook to investigate the distribution
of petal lengths and the relationship between petal length and width in the
Iris dataset.

## Quick Look

- Click [problems.ipynb](./problems.ipynb) to view the analysis, histograms, and
  species-wise scatter plots.
- You can view and run the notebook in [Google Colab](https://colab.research.google.com/).

## Running the Notebook

To run `problems.ipynb`, you can follow these steps:

1. Ensure you have [Python](https://www.python.org/) and [Jupyter](https://jupyter.org/) installed on your machine. You can install them using [Anaconda](https://www.anaconda.com/products/distribution/) or [uv](https://docs.astral.sh/uv/).

2. Clone the repository to your local machine using the following command:

   ```bash
   git clone https://github.com/CGiardino/applied-statistics.git
   ```

3. Navigate to the cloned repository:

   ```bash
   cd applied-statistics
   ```

4. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

5. Start the Jupyter server:

   ```bash
   jupyter notebook
   ```

   Open `problems.ipynb`, choose **Kernel > Restart Kernel and Run All Cells**,
   and confirm that all cells execute without errors.

## Dependencies

The notebook uses the packages listed in
[requirements.txt](./requirements.txt):

 - `pandas` for loading and describing the data
 - `matplotlib` for creating the histograms and scatter plot
 - `numpy` for numerical computing and the fitted normal/regression curves
 - `scipy` for normal probability plots and the Shapiro-Wilk normality test
 - `notebook` and `ipykernel` for running the notebook

## About the Notebook

The notebook downloads the Iris dataset from the
[Seaborn data repository](https://github.com/mwaskom/seaborn-data), checks that
it contains 150 flowers and valid measurements, calculates summary statistics,
plots histograms of petal lengths, and examines the relationship between
`petal_length` and `petal_width` both overall and separately for each species.
