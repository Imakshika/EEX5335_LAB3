# EEX5335 - Operating Systems - Lab 3

A memory management simulator implementing TLB, Page Table, and Cache functionality.

## How to Run This Simulator

This project is implemented as a Google Colab notebook (.ipynb file). You can run it in two ways:

### Option 1: Run directly in Google Colab (Recommended)
1.  **Click the Open in Colab badge below:**  
    [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO_NAME/blob/main/EEX5335_Lab3_Memory_Simulator.ipynb)

2.  Once the notebook opens in Colab, click **"Runtime"** in the top menu.
3.  Select **"Run all"** from the dropdown menu.
4.  The simulator will execute all cells and show the output below each one.

### Option 2: Download and run locally
1.  Download the `EEX5335_Lab3_Memory_Simulator.ipynb` file from this repository.
2.  Install Jupyter Notebook or Jupyter Lab on your local machine:
    ```bash
    pip install jupyterlab
    ```
3.  Launch Jupyter:
    ```bash
    jupyter lab
    ```
4.  Open the downloaded `.ipynb` file and click **"Run" > "Run All Cells"**.

## Simulator Output
The simulator will automatically run several test cases demonstrating:
- TLB hits and misses
- Page table lookups
- Cache hits and misses
- Page fault handling
- Step-by-step address translation process

The output for each virtual address access will be printed directly in the notebook.
