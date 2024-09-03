# Evaluating the Predictive Capacity of FLARES Simulations for High Redshift "Little Red Dots"

## Project Overview

This project investigates the predictive capacity of FLARES simulations in replicating the stellar properties of high-redshift galaxies, specifically the "Little Red Dots" (LRDs) observed by the James Webb Space Telescope (JWST). The analysis compares the output of the FLARES simulations with observational data from the COSMOS-Web survey to evaluate the validity of the starburst hypothesis.

```

### Notebooks

- `Galaxy_Stellar_Mass_Functions.ipynb`: Analyses and visualizes galaxy stellar mass functions using data from the FLARES simulations and the COSMOS-Web survey.
- `star_formation_histories_code.ipynb`: Analyses the star formation histories of galaxies.
- `Jupyter Notebook stellar_main_sequence_plots.ipynb`: Visualises the stellar main sequence for different datasets.
- `corner_plots.ipynb`: Generates corner plots for visualising the relationships between different galaxy properties .

### Data Files

- `filtered_FLARES_data.csv`: Processed FLARES simulation data after applying selection criteria (mock observations).
- `LRD_data.csv`: Observational data from the COSMOS-Web survey.
- `raw_FLARES_data.hdf5`: Simulated data from the FLARES simulation suite.

## Installation

To run the notebooks, you'll need to install the required Python packages. The dependencies are listed in the `requirements.txt` file. You can install them using pip:

```bash
pip install -r requirements.txt
```

## Usage

1. **Clone the repository**

2. **Set up your environment**:

    Ensure all dependencies are installed using the provided `requirements.txt` file.

3. **Run the notebooks**:

    Start Jupyter Notebook in the `code` directory and open any of the provided `.ipynb` files:

    ```bash
    jupyter notebook
    ```

    Select the notebook you wish to run and execute the cells to perform the analysis. Note: some diagrams might differ slightly from the original paper but display exactly the same information.


## Contact

For any questions or issues, please contact the author.

