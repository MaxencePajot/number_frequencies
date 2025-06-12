# The compositional nature of number concepts: Insights from number frequencies.

This is a repository for the data and code of:

Pajot, M., Sablé-Meyer, M., & Dehaene, S. (2025). The compositional nature of number concepts: Insights from number frequencies. PsyArXiv. https://osf.io/8bakh/download

# Environment

The environment is a python 3.10 environment. The list of dependencies is listed in the pyproject.toml file. To reproduce the environment used, use the command line:

`uv sync`

You also need R for the plots. The R version used is 4.5.0

# Use

Since these are notebooks for visualisation, it is best to run all cells sequentially.
To run all notebooks, run the command line:

'for f in *.ipynb; do uv run --with jupyter jupyter nbconvert --to notebook --inplace --execute "$f"; done'
