# 03_crypto_arbitrage
Financial analysis to determine if any arbitrage opportunities exist for Bitcoin

## Technologies

Crypto Arbitrage is a Jupyter notebook built with the following technologies:

### Language

| Language | Version |
|----------|---------|
| Python   | 3.7.11  |
### Libraries and Frameworks

| Component | Version |
|-----------|---------|
| Anaconda  | 1.9.0   |
| Conda     | 4.11.0  |
| Jupyter   | 3.2.1   |

### Operating System

This version of Crypto Arbitrage is operating system agnostic.

---
## Installation Guide

### Pre-requisites

- Python 3.7
- Anaconda 1.9.0
- Conda 4.11.0
- Jupyter 3.2.1
- A conda environment created specially for this project.

### Installation

Install a new conda environment for this project. We will be using `python 3.7.11` for this repository.

```bash
conda create -n 03_crypto_arbitrage python=3.7.11 anaconda
```

Activate the newly created environment and verify the python version.

```bash
conda activate 03_crypto_arbitrage
python --version
```

Clone the remote repository to your local developer environment and `cd` into the folder.
```bash
git clone git@github.com:msashokkumar/03_crypto_arbitrage.git
cd 03_crypto_arbitrage
```

Start the jupyter lab server from the terminal as follows:

```bash
jupyter lab
```

Once started successfully, the terminal will look like below and a browser will open automatically.

![Jupyter Lab Started](/media/images/01_start_jupyter_labs.png?raw=true "Start jupyter labs server from terminal.")

The jupyter homepage will look like as follows:

![Jupyter Lab Homepage](/media/images/02_jupyter_lab_homepage.png?raw=true "Jupyter homepage.")

From the file browser on the left side, open crypto_arbitrage.ipynb.