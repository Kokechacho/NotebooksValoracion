# Financial Derivatives Valuation Methods

Welcome to the Financial Derivatives Valuation repository! This project contains a collection of Jupyter notebooks designed to introduce key concepts and valuation methods for financial derivatives such as options and futures. Each notebook provides detailed explanations, practical exercises, and visualizations to enhance understanding.

## Table of Contents

- [Files Included](#files-included)
- [Notebooks Overview](#notebooks-overview)
- [Data Files](#data-files)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)

## Files Included

- **AMZN.csv**: Historical price data for Amazon, used for valuation exercises.
- **ContratosForwardsyFuturos.ipynb**: Introduction to forward contracts and futures.
- **ContratosOpciones.ipynb**: Introduction to options pricing models, including:
  - **Binomial Model**: Overview and applications.
  - **Black-Scholes Model**: Detailed analysis and calculations.
- **Estrategias.ipynb**: Various strategies related to derivatives trading.
- **MatplotIntro.ipynb**: Introduction to Matplotlib for data visualization.
- **ModeloBinomial.ipynb**: Detailed implementation of the binomial pricing model.
- **ModeloBlack-Scholes.ipynb**: Comprehensive exploration of the Black-Scholes pricing model.

## Notebooks Overview

### ContratosOpciones.ipynb
- **Topic 8.1**: Introduction to the Binomial Model
  - Small introduction to the Binomial Model.
  - A cascading exercise reviewing associated formulas.
  - A final function that plots the resulting tree.

- **Topic 8.2**: Introduction to the Black-Scholes Model
  - Detailed exploration of the Black-Scholes formulas.
  - Two exercises: pricing an option and calculating d1 and d2.
  - Comparison of pricing between Put and Call options.
  - A final exercise for valuing multiple options using the generated functions.
  - A guided explanation on creating an options calculator.

## Data Files

The `AMZN.csv` file contains historical price data for Amazon, which is used in various exercises across the notebooks. Make sure to check the data format and columns when running the notebooks.

## Installation

To run the notebooks, you'll need to have Python and Jupyter Notebook installed. You can install the required packages using pip:

```bash
pip install pandas numpy matplotlib
