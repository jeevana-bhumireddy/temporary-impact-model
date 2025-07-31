# Temporary Market Impact Modeling

This repository contains a Python Jupyter notebook and supporting files for modeling the temporary market impact function \(g_t(x)\) via simulated order book liquidity from three tickers. The model improves on classical linear assumptions by simulating realistic order book snapshots and computing nonlinear, piecewise temporary impact functions suitable for optimal trade execution analysis.

## Repository Structure

- `notebooks/`: Jupyter notebooks with the modeling and analysis
- `src/`: Optional Python modules for reusable code (if any)
- `data/`: Folder for raw and processed data files
- `results/`: Output figures and reports (usually gitignored)
- `scripts/`: Helper scripts (if any)
- `requirements.txt`: Python package dependencies
- `.gitignore`: Specifies files/folders to exclude from git
- `LICENSE`: Open source license file

## Getting Started

### Installation

Install required Python packages:


### Running the Notebook

Open the main notebook with Jupyter Lab, Jupyter Notebook, or Google Colab:


Or upload the notebook directly to Google Colab for interactive use.

### Using Real Data

By default, the notebook simulates order book data.  
To use real ticker Level 2 order book data:

- Place your data files in the `data/raw/` folder.
- Modify the data loading section in the notebook accordingly.

## Features

- Nonlinear modeling of temporary market impact beyond simple linear assumptions.
- Stepwise impact functions derived from simulated order book liquidity.
- Interpolation to produce continuous impact functions for optimization.
- Example analysis and visualization of three tickers with varying liquidity profiles.
- Framework easily extendable to real market data and optimal execution strategies.

-----

*Feel free to open issues or contribute to improve this project!*

