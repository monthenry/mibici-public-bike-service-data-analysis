# Network Analysis of 'MiBici' Public Bike Service in Guadalajara's Metropolitan Area

This repository contains a comprehensive network analysis of the public shared bike service known as "MiBici" in Guadalajara's metropolitan area (ZMG) in Jalisco, Mexico, spanning from December 2014 to January 2024. The analysis delves into the network structure, dynamics, and user behaviors of the "MiBici" system using advanced network analysis techniques. The findings contribute significantly to the understanding of public bike-sharing systems and offer valuable recommendations for improving service operations and urban planning efforts.

## Repository Structure

- **data/**: Contains datasets used in the analysis.
  - `mibici_2014-2024/mibici_compact.csv`: Preprocessed dataset containing public bike trips.
  - `nomenclature_2024.csv`: Dataset detailing bike station locations.
- **notebooks/**: Contains the Jupyter Notebook for the analysis.
  - `mibici_public_bike_analysis.ipynb`: Jupyter Notebook with code and analysis.
- **reports/**: Contains figures and the research paper.
  - `figures/`: Visualizations generated during the analysis.
    - `mibici-network-communities.png`: Network community structure.
    - `guadalajara_all_stations.png`: Map of all bike stations.
    - `mibici-weekday.png`: Analysis of trips by weekday.
    - `mibici-hour.png`: Analysis of trips by hour.
    - `guadalajara_central_stations.png`: Map of central bike stations.
  - `Network_Science_Project_Henry_Marie_MONT_Matteo_MATONE.pdf`: Final research paper.
  - `Network_Science_Project_Henry_Marie_MONT_Matteo_MATONE.tex`: LaTeX source file of the research paper.
- **.gitignore**: Specifies files to ignore in version control.
- **README.md**: This file, providing an overview of the project.

## Running the Project

To run the project, follow these steps:

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/monthenry/mibici-public-bike-service-data-analysis.git
    ```

2. Navigate to the project directory:
    ```bash
    cd mibici-public-bike-service-data-analysis
    ```

3. Open the Jupyter Notebook `mibici_public_bike_analysis.ipynb` using Jupyter Notebook or JupyterLab:
    ```bash
    jupyter notebook notebooks/mibici_public_bike_analysis.ipynb
    ```

4. Execute the cells in the notebook to reproduce the analysis and visualize the results.
