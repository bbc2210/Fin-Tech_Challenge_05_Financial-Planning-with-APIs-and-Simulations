# Financial-Planning-with-APIs-and-Simulations

You’ll create two financial analysis tools by using a single Jupyter notebook:

Part 1: A financial planner for emergencies. The members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund.

Part 2: A financial planner for retirement. This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

You’ll use the information from the Monte Carlo simulation to answer questions about the portfolio in your Jupyter notebook.

---

## Technologies

This project leverages python 3.7 with the following packages:

* [Pandas](https://pandas.pydata.org/) - Pandas is a Python library that’s designed speci cally for data analysis. It offers a streamlined way of reviewing datasets and includes
  various functions that simplify importing, updating, and analyzing data.

* [JupyterLab](https://jupyter.org/) - JupyterLab is a web-based user interface that you use to run and review Python-based programs. It easily integrates with the Anaconda
  software package and your Conda development environment.

---

## Installation Guide

Before running the application first install the following dependencies.

```python
sourse activate 
conda activate dev
conda list pandas
conda list jupyterlab
conda deactivate
conda remove --name dev --all
conda info --envs
conda update conda
conda create -n dev python=3.7 anaconda
python -m pip install pandas
pip install jupyter 
#check if pandas is installed successfully
conda list pandas
#check if jupyterlab is listed successfully
conda list jupyterlab
```

---

## Usage

To use the Crypto Arbitrage application simply clone the repository, download whale_navs.csv,   and run the **risk_return_analysis.ipynb** with:

```python
jupyter lab
```

---

## Contributors


---

## License