# Hierarchical Bayesian Modeling of English Premier League Matches

This repository provides the code and analysis for predicting English Premier League (EPL) match outcomes using hierarchical Bayesian modeling techniques. The project utilizes data from 1993 to 2024 and employs advanced Bayesian methods for improved prediction accuracy.

## Project Overview

### Objectives
- Forecast match outcomes (win, draw, loss) using historical EPL data.
- Model team dynamics, home-field advantage, and goal statistics.
- Compare the effects of informative (Half-Normal) and non-informative priors on prediction accuracy.

### Key Features
- **Hierarchical Bayesian Models:** Capture team-level and league-level dynamics.
- **Home Advantage Analysis:** Quantify the impact of home-field advantage on match results.
- **Time-Dependent Models:** Account for changes in team strength over multiple seasons.
- **Efficient Sampling:** Use PyMC's No-U-Turn Sampler (NUTS) for robust parameter estimation.

### Research Contributions
- Demonstrates the use of informative priors to reduce overshrinkage in Bayesian models.
- Introduces a reproducible workflow for sports analytics using Python and PyMC.

## Dataset
The dataset includes 31 years of EPL match records:
- Variables: home and away goals, match outcomes, and team identities.
- Source: [football-data.co.uk](https://www.football-data.co.uk).

### Limitations
- The analysis focuses on goal statistics and does not incorporate additional factors such as player-level details or weather conditions.

## How to Run the Analysis

### Requirements
To run the project, you need Python 3.8+ and the following libraries:
- `pandas`
- `numpy`
- `pymc`
- `matplotlib`
- `arviz`

### Running the Code
1. Clone this repository:
   ```bash
   git clone https://github.com/byMatematician/hierarchical-bayesian-epl-modeling.git
