# Introduction to Interactive Data Analysis Tutorial
<p align="center">
  <img src="images/nsdf.png" height="60" alt="NSDF Logo"/>
  <img src="images/nasajpl.png" height="60" alt="NASA JPL Logo"/>
  <img src="images/scientistCloudLogo_storage.png" height="60" alt="ScientistCloud Logo"/>
  <img src="images/PelicanPlatformLogo.png" height="60" alt="Pelican Platform Logo"/>
  <img src="images/OSG-logo.svg" height="60" alt="OSG Logo"/>
</p>


--- 

## Overview

This tutorial introduces interactive data analysis using the OpenVisus framework and NASA NEX-GDDP-CMIP6 datasets. It provides step-by-step instructions for reading, converting, and visualizing climate data, and launching interactive dashboards for exploration.

**By the end of the tutorial, you will learn how to:**

- Read and visualize large-scale climate datasets directly from the cloud using OpenVisus.
- Download NetCDF files, extract relevant variables, and convert them to the OpenVisus IDX format for efficient analysis.
- Bring your own NetCDF or array-based data and convert it to IDX format for scalable visualization and exploration.
- Launch and configure the OpenVisus dashboard for interactive data analysis in your browser.
- Use Intake to subset, stream, and visualize NASA NEX-GDDP-CMIP6 data by time, region, and resolution using Python tools like xarray and matplotlib.

---

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

---

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

---

## References

- [OpenVisus Framework](https://github.com/sci-visus/OpenVisus)
- [Quarto Documentation for NEX-GDDP-CMIP6](https://aashishp.quarto.pub/nex-gddp-cmip6/)

---

## Acknowledgements

- Aashish Panta (aashishpanta0@gmail.com)
- Giorgio Scorzelli (scrgiorgio@gmail.com)
- Valerio Pascucci (pascucci.valerio@gmail.com)