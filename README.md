# Robustness of School Contact Networks to Immunization

The repository contains code accompanying the following paper: Raina Tandon, Gabrielle Zupan, Noor Khan, Maggie Bothwell, Robustness of School Contact Networks to Immunization (2026).

# Contents

- [Contents](#contents)
- [Getting Started](#getting-started)
  - [Repository layout](#repository-layout)
  - [Installing](#installing)
- [Other Information](#other-information)
  - [Authors](#authors)
  - [License](#license)

# Getting started

## Repository layout

| Path | Role |
|---|---|
| `Data/Raw/Contact-diaries-networks_data_2013.csv` | Raw contact diary network data downloaded from https://sociopatterns.org/datasets/high-school-contact-and-friendship-networks/|
| `Data/Raw/Friendship-network_data_2013.csv` | Raw friendship network data downloaded from https://sociopatterns.org/datasets/high-school-contact-and-friendship-networks/|
| `Data/Raw/Highschool2013_proximity_net.csv` | Raw contact sensor data downloaded from https://sociopatterns.org/datasets/high-school-contact-and-friendship-networks/|
| `Code/11-09-2026_code001.ipynb` | Construction of friendship and contact diary networks |
| `Code/11-09-2026_code002.ipynb` | Construction of the temporal network of the sensor data |
| `Code/11-09-2026_code003.ipynb` | Reference code to import the constructed networks across notebooks |
| `Code/11-09-2026_code004.ipynb` | SIR simulations using targetted versus random immunization on the temporal network |
| `Code/11-11-2026_code005.ipynb` | Construction of temporal sensor network, friendship network, and contact diary network using only students in all three datasets |
| `Code/11-11-2026_code006.ipynb` | Comparison of SIR simulations using targetted versus random immunization on all three networks|
| `Code/simulation_results.csv` | Includes the all the SIR simulaton results, including immunizaton strategy,immunization coverage, trial number, and epidemic size |
| `Code/student_rankings.csv` | Ranking of each student based on thier degree centrality, betweenness centrality, and reachability in the different networks|








## Installation

```bash
pip install -r requirements.txt
```

# Other information

## Authors

- Raina Tandon
- Gabrielle Zupan
- Noor Khan
- Maggie Bothwell

## License

This project is licensed under the [BSD-3 License](LICENSE) - see the [LICENSE](LICENSE) file for details.
