# Network Analysis of "MiBici" Public Bike Service in Guadalajara's Metropolitan Area

This repository contains the code and data for the network analysis of the public shared bike service known as "MiBici" in Guadalajara's metropolitan area (ZMG) in Jalisco, Mexico, from December 2014 to January 2024.

## Overview

The project aims to explore the network structure, dynamics, and user behaviors of the "MiBici" public bike service using network analysis techniques. It includes the following components:

- Data preprocessing: Cleaning and preparing the raw data for analysis.
- Network construction: Building the network representation of the bike service system.
- Analysis scripts: Implementing various network analysis techniques to study the system's characteristics.
- Visualization: Creating visualizations to interpret and present the analysis results.
- Paper: Documenting the findings in a research paper.

## Repository Structure

|-- data  
| |-- raw_data.csv # Raw data obtained from the "MiBici" service  
| |-- processed_data.csv # Processed data ready for analysis  
|-- scripts  
| |-- data_preprocessing.py # Python script for data preprocessing  
| |-- network_construction.py# Python script for network construction  
| |-- analysis.py # Python script for network analysis  
| |-- visualization.py # Python script for visualization  
|-- paper  
| |-- paper.tex # LaTeX source file for the research paper  
| |-- paper.bib # Bibliography file for the research paper  
| |-- figures # Directory for storing figures used in the paper  
|-- README.md # This README file  


## Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your_username/network-analysis-mibici.git
   ```

2. **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

3. **Data preprocessing:**

    ```bash
    python scripts/data_preprocessing.py
    ```

4. **Network construction:**

    ```bash
    python scripts/network_construction.py
    ```

5. **Analysis:**

    ```bash
   python scripts/analysis.py
    ```

6. **Visualization:**
   
     ```bash
    python scripts/visualization.py
    ```

## Contributors

Henry Marie Mont (@monthenry)
Matteo Matone (@matone098)
