# Intro to Interactive Data Analysis Tutorial

## Requirements

- Python 3.8 or higher
- Git

## Setup Instructions

1. **Clone the repository:**
   ```sh
   git clone https://github.com/aashishpanta0/Intro-to-Interactive-Data-Analysis-Tutorial.git
   cd Intro-to-Interactive-Data-Analysis-Tutorial
   ```

2. **Create a virtual environment:**
   ```sh
   python -m venv .venv
   source .venv/bin/activate  # On Windows use `.venv\Scripts\activate`
   ```

3. **Install required libraries:**
   ```sh
   pip install -r requirements.txt
   ```

## Notebooks

### Part 1: Read CMIP6

- [1-Read-CMIP6.ipynb](1-Read-CMIP6.ipynb): Instructions to read Nex GDDP CMIP6 data from a server using the OpenVisus framework. Includes steps for selecting variables, reading metadata, loading data, and visualizing results.

### Part 2: Working with Netcdfs

- [2-Working-with-Netcdfs.ipynb](2-Working-with-Netcdfs.ipynb): Shows how to download NetCDF files, extract relevant data, and convert them to OpenVisus IDX format. Includes code for downloading from S3, reading with xarray, writing IDX, compressing, and verifying.

### Part 3: Bring Your Own Data (BYOD)

- [3-BYOD.ipynb](3-BYOD.ipynb): Template for users to load their own dataset and convert it to IDX format. Users set their file paths, variable names, and dimensions, then follow the steps to create and verify their IDX dataset.


### Part 4: Launch OpenVisus Dashboard

- [4-Launch-Dashboard.ipynb](4-Launch-Dashboard.ipynb): Step-by-step instructions to set up and launch the OpenVisus dashboard for interactive data analysis. Covers cloning the dashboard repo, setting up the environment, installing dependencies, configuring environment variables, and launching the dashboard server.

### Part 5: Using Intake with OpenVisus

- [5-Using-Intake.ipynb](5-Using-Intake.ipynb): Demonstrates how to explore NASA NEX-GDDP-CMIP6 data using Intake and OpenVisus. Shows how to subset by time, region, and resolution, and visualize results with xarray and matplotlib.


## References

- [OpenVisus Framework](https://github.com/sci-visus/OpenVisus)
- [Quarto Documentation for NEX-GDDP-CMIP6](https://aashishp.quarto.pub/nex-gddp-cmip6/)

## Acknowledgements

- Aashish Panta (aashishpanta0@gmail.com)
- Giorgio Scorzelli (scrgiorgio@gmail.com)
- Valerio Pascucci (pascucci.valerio@gmail.com)