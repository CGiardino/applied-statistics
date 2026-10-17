# Applied Statistics

This repository contains my submission for the Applied Statistics module.
The project uses Python and a Jupyter notebook to investigate the distribution
of petal lengths in the Iris dataset.

## Quick Look

- Click [problems.ipynb](./problems.ipynb) to view the analysis and histogram.
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
   cd my-applied-statistics
   ```

4. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

5. Start the Jupyter server:

   ```bash
   jupyter notebook
   ```

## Dependencies

The notebook uses the pinned versions listed in
[requirements.txt](./requirements.txt):

 - pandas 3.0.6 for loading and describing the data
 - matplotlib 3.11.2 for creating the histogram
 - Jupyter 4.2.5 for running the notebook
 - NumPy 2.5.4 for numerical computing

## About the Notebook

The notebook downloads the Iris dataset from the Seaborn data repository,
checks that it contains 150 flowers and valid `petal_length` values, calculates
summary statistics, and plots a histogram of all petal lengths. The notebook
is designed to run from top to bottom in less than three minutes.
