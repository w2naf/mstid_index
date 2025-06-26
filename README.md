# MSTID Index and Plotting Tools

This repository contains data and tools for visualizing Medium-Scale Traveling Ionospheric Disturbance (MSTID) activity observed by SuperDARN radars.

# Rules of the Road
Please contact Nathaniel Frissell at nathaniel.frissell@scranton.edu before using this code or data.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/w2naf/mstid_index.git
   cd mstid_index
   ```

2. **Set up a Python environment** (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install required packages**:
   ```bash
   pip install -r requirements.txt
   ```

## Running the Code

To generate MSTID index plots from SuperDARN data, run the main script:

```bash
python superdarn_mstid_plot.py
```

## Output

- Figures and CSV output files will be automatically saved in the `output/` directory.

## Contact

For questions or contributions, please open an issue or contact the repository maintainer.